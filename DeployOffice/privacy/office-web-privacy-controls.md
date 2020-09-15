---
title: Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với các ứng dụng Office trên web
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Cung cấp cho người quản trị Office thông tin về cách quản lý kiểm soát quyền riêng tư cho Office trên các ứng dụng web.
hideEdit: true
ms.openlocfilehash: b5131d5ffc09b28a3b5731a417fcd6d383fb7d01
ms.sourcegitcommit: da41d41b443c8392c96e64a4d2fc674957abddf5
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 09/11/2020
ms.locfileid: "47432013"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-for-the-web-applications"></a>Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với các ứng dụng Office trên web

> [!NOTE]
> Để biết danh sách các sản phẩm Office nằm trong thông tin về quyền riêng tư này, hãy xem [Kiểm soát về quyền riêng tư sẵn có cho các sản phẩm Office](products-versions-privacy-controls.md).

Với tư cách là quản trị viên tổ chức của bạn, bạn có thể kiểm soát việc liệu người dùng của mình có lựa chọn sử dụng trải nghiệm được kết nối tùy chọn khi họ sử dụng Office trên các ứng dụng web hay không, chẳng hạn như Word cho web hay PowerPoint cho web. Lựa chọn này chỉ sẵn dùng cho người dùng của bạn nếu họ đăng nhập bằng tài khoản cơ quan hoặc trường học của mình khi sử dụng Office cho các ứng dụng web. Để kiểm soát xem các loại trải nghiệm được kết nối này có khả dụng cho người dùng của bạn hay không, bạn có thể sử dụng thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tuỳ chọn bổ sung trong Office*.

## <a name="overview-of-optional-connected-experiences"></a>Tổng quan về trải nghiệm được kết nối tuỳ chọn

Trải nghiệm được kết nối tùy chọn là các dịch vụ được hỗ trợ qua điện toán đám mây khả dụng cho người dùng của bạn khi họ đang sử dụng Office. Các ví dụ về trải nghiệm kết nối tùy chọn bao gồm việc tạo biểu đồ dạng bản đồ trong Excel hoặc chèn ảnh trực tuyến vào tài liệu Word của bạn, cả hai ví dụ này đều dựa vào các dịch vụ được cung cấp bởi Microsoft Bing. Việc sử dụng các dịch vụ dựa trên đám mây này là tùy chọn. 

Các trải nghiệm được kết nối tuỳ chọn không nằm trong thỏa thuận thương mại của tổ chức của bạn với Microsoft. Thay vào đó, các trải nghiệm được kết nối tùy chọn do Microsoft cung cấp trực tiếp cho người dùng của bạn và chịu sự điều chỉnh của [Thỏa thuận Dịch vụ của Microsoft](https://www.microsoft.com/servicesagreement). Trong một số trường hợp, nội dung hoặc chức năng của bên thứ ba được cung cấp thông qua các trải nghiệm được kết nối tùy chọn này và các điều khoản khác cũng có thể được áp dụng.

Một số trải nghiệm được kết nối tùy chọn có thể không sẵn dùng trong Office cho các ứng dụng web nhưng sẵn dùng khi sử dụng các phiên bản khác của Office, chẳng hạn như phiên bản dành cho máy tính trên thiết bị chạy Windows.

Để tìm hiểu thêm thông tin, hãy xem [Tổng quan về trải nghiệm kết nối tuỳ chọn trong Office](optional-connected-experiences.md).

## <a name="configure-the-policy-setting-by-using-the-office-cloud-policy-service"></a>Đặt cấu hình cho thiết đặt chính sách bằng cách sử dụng Dịch vụ chính sách đám mây Office

Bạn có thể sử dụng thiết đặt chính sách *Cho phép sử dụng các trải nghiệm được kết nối tuỳ chọn bổ sung trong Office* để kiểm soát xem liệu người dùng của bạn có lựa chọn sử dụng trải nghiệm kết nối tuỳ chọn hay không. Để đặt cấu hình thiết đặt chính sách này cho các ứng dụng Office dành cho web, bạn cần sử dụng [dịch vụ chính sách đám mây Office](../overview-office-cloud-policy-service.md).  

Nếu bạn không cấu hình các cài đặt chính sách này, việc chọn sử dụng những trải nghiệm được kết nối tuỳ chọn này sẽ có sẵn cho người dùng của bạn. Nếu bạn tắt cài đặt chính sách này, người dùng của bạn sẽ không thể sử dụng bất cứ trải nghiệm kết nối tùy chọn nào.

Đối với Office trên các ứng dụng web, cài đặt chính sách sẽ áp dụng cho khi người dùng của bạn đang làm việc trên các tài liệu Office được lưu vào dung lượng lưu trữ dựa trên web từ Microsoft, chẳng hạn như OneDrive cho Doanh nghiệp hoặc SharePoint Online.

Vì bạn đang sử dụng Dịch vụ chính sách đám mây Office, cài đặt chính sách này cũng được áp dụng khi người dùng của bạn đang sử dụng Office trên các thiết bị chạy Windows, máy Mac, iOS hoặc Android. Bạn không thể đặt cấu hình cho các thiết đặt chính sách này khi người dùng của bạn đang sử dụng Office trên các ứng dụng web. Tuy nhiên, bạn có thể tạo cấu hình chính sách bao gồm cài đặt chính sách này và chỉ áp dụng cấu hình chính sách đó cho người dùng có thể truy nhập tài liệu ẩn danh sử dụng Office cho các ứng dụng web.

Nếu bạn chọn tạo ra trải nghiệm được kết nối tùy chọn sẵn dùng với người dùng của mình thì người dùng của bạn sẽ được hiển thị thông báo về quyền riêng tư khi họ lần đầu sử dụng Office trên ứng dụng web. Thông báo này cho người dùng của bạn biết rằng bạn đã cung cấp tùy chọn này để sử dụng các trải nghiệm được kết nối tùy chọn này. Thông báo cũng cho người dùng của bạn biết rằng các trải nghiệm kết nối tùy chọn được cung cấp theo Thỏa thuận Dịch vụ của Microsoft. Vì thông báo này là thông tin quan trọng đối với người dùng của bạn, bạn phải hiển thị thông báo này và không thể tắt, ẩn hoặc chấp nhận thay mặt người dùng của bạn.

## <a name="users-can-choose-to-turn-off-optional-connected-experiences"></a>Người dùng có thể chọn tắt trải nghiệm được kết nối tùy chọn

Nếu bạn chọn tạo trải nghiệm kết nối tùy chọn sẵn dùng với người dùng của mình, người dùng của bạn có thể truy nhập [thiết đặt quyền riêng tư của tài khoản](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Online), rồi chọn tắt tính năng truy nhập vào trải nghiệm được kết nối tùy chọn. Lựa chọn này chỉ sẵn dùng trong thiết đặt quyền riêng tư của tài khoản nếu người dùng của bạn đã đăng nhập bằng tài khoản cơ quan hoặc trường học của họ. Với tư cách là quản trị viên, bạn không thể ngăn người dùng cá nhân trong tổ chức của mình tắt tính năng truy nhập vào trải nghiệm kết nối tùy chọn trong thiết đặt quyền riêng tư của tài khoản nếu bạn đã cấp cho người dùng của mình lựa chọn sử dụng trải nghiệm liên kết tùy chọn.

## <a name="related-articles"></a>Bài viết liên quan

- [Tổng quan về các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md)
- [Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](manage-privacy-controls.md)
- [Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office cho Mac](mac-privacy-preferences.md)
- [Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS](ios-privacy-preferences.md)
- [Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android](android-privacy-controls.md)