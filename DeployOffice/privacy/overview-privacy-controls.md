---
title: Tổng quan về kiểm soát quyền riêng tư cho Office 365 ProPlus
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: conceptual
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Cung cấp cho người quản trị Office thông tin tổng quan về kiểm soát quyền riêng tư cho Office 365 ProPlus, bao gồm dữ liệu chẩn đoán và trải nghiệm được kết nối.
hideEdit: true
ms.openlocfilehash: 708c8b1dae02f54d4c6a6195cec9513c8639b62d
ms.sourcegitcommit: aed9a0908021ffc80baa7159a66b63dd4f9f28e4
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 10/08/2019
ms.locfileid: "37417457"
---
# <a name="overview-of-privacy-controls-for-office-365-proplus"></a>Tổng quan về kiểm soát quyền riêng tư cho Office 365 ProPlus

Microsoft cam kết cung cấp cho bạn thông tin và kiểm soát mà bạn cần để đưa ra lựa chọn về cách thu thập và sử dụng dữ liệu của bạn khi bạn sử dụng Office 365 ProPlus.

Bắt đầu với Phiên bản 1904 của Office 365 ProPlus (được phát hành trên Kênh hàng tháng vào ngày 29/4/2019), chúng tôi sẽ cung cấp cho bạn các kiểm soát quyền riêng tư mới, cập nhật và được cải thiện cho các khu vực sau:
- ***Dữ liệu chẩn đoán*** được thu thập và gửi cho Microsoft về phần mềm máy khách Office đang được sử dụng trên các máy tính chạy Windows trong tổ chức của bạn.
- ***Trải nghiệm được kết nối*** sử dụng chức năng dựa trên đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.

Là một phần của những thay đổi này, có các cài đặt chính sách và thành phần giao diện người dùng (UI) mới và được cập nhật.

> [!IMPORTANT]
> - Những thay đổi này áp dụng cho Access, Excel, OneNote, Outlook, PowerPoint, Publisher và Word.
> - Những thay đổi này cũng được áp dụng cho những phiên bản sau đây:
>   - Phiên bản 16.28 trở lên của các ứng dụng Office dành cho máy Mac sau: Excel, Outlook, OneNote, PowerPoint và Word.
>   - Phiên bản 1904 trở lên của Project và Visio trên máy tính đi kèm với một số gói đăng ký, chẳng hạn như gói Project Online Professional hoặc Visio Online Plan 2.
> - Các điều khiển về quyền riêng tư này được tích hợp trong phiên bản 1908 của Kênh nửa năm một lần (Nhóm mục tiêu) được phát hành vào ngày 10/9/2019. Dự kiến, chúng sẽ sẵn dùng trong các Kênh nửa năm một lần vào tháng 01/2020.
> - Theo kế hoạch, các biện pháp kiểm soát quyền riêng tư này sẽ được áp dụng trong nửa sau của tháng 10/2019 đối với các phiên bản iOS của Excel, OneNote, PowerPoint, Visio và Word. Chúng tôi sẽ cung cấp thêm thông tin vào đầu tháng 10.
> - Hầu hết các ứng dụng Office dành cho web được lên lịch để bắt đầu sử dụng biện pháp kiểm soát quyền riêng tư mới cho [các trải nghiệm được kết nối tùy chọn](optional-connected-experiences.md) vào giữa tháng Mười năm 2019. Các ứng dụng đó được liệt kê sau đây: Excel dành cho web, OneNote dành cho web, PowerPoint dành cho web, Visio dành cho web và Word dành cho web. Trước khi bắt đầu, bạn có thể sử dụng [dịch vụ chính sách trên nền điện toán đám mây Office](../overview-office-cloud-policy-service.md) để đặt cấu hình cho [cài đặt chính sách](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences) thích hợp.
> - Chúng tôi sẽ mở rộng các biện pháp kiểm soát quyền riêng tư mới và được tăng cường này cho các máy khách Office bổ sung, bao gồm cả Teams và ứng dụng dành cho di động của chúng tôi. Chúng tôi sẽ cung cấp thêm thông tin về những thay đổi đó trong những tháng sắp tới. Chúng tôi sẽ tiếp tục thận trọng lắng nghe phản hồi của bạn và cải thiện tất cả các ứng dụng máy khách và dịch vụ của Office 365.

## <a name="diagnostic-data-sent-from-office-365-proplus-to-microsoft"></a>Dữ liệu chẩn đoán được gửi từ Office 365 ProPlus đến Microsoft

Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm. Dữ liệu này không bao gồm tên người dùng hoặc địa chỉ email, nội dung của các tệp của người dùng hoặc thông tin về các ứng dụng không liên quan đến Office.

Dữ liệu chẩn đoán được thu thập và gửi cho Microsoft về phần mềm máy khách Office đang được sử dụng trên các máy tính chạy Windows trong tổ chức của bạn.

Có ba cấp dữ liệu chẩn đoán cho phần mềm máy khách Office 365 ProPlus mà bạn có thể chọn:

- **Bắt buộc**: Dữ liệu tối thiểu cần thiết để giúp Office an toàn, cập nhật và hoạt động như mong đợi trên thiết bị mà nó được cài đặt.

- **Tuỳ chọn**: Dữ liệu bổ sung giúp chúng tôi cải tiến sản phẩm và cung cấp thông tin nâng cao để giúp chúng tôi phát hiện, chẩn đoán và khắc phục các sự cố.

- **Không thuộc loại nào**: Không có dữ liệu chẩn đoán nào về phần mềm máy khách Office chạy trên thiết bị người dùng được thu thập và gửi cho chúng tôi. Tuy nhiên, tùy chọn này hạn chế đáng kể khả năng phát hiện, chẩn đoán và khắc phục các sự cố mà người dùng của bạn có thể gặp phải khi sử dụng Office.

Ví dụ, dữ liệu chẩn đoán bắt buộc có thể bao gồm thông tin về phiên bản Office được cài đặt trên thiết bị hoặc bao gồm thông tin cho biết các ứng dụng Office đang gặp sự cố khi cố mở tài liệu. Dữ liệu chẩn đoán tùy chọn có thể bao gồm thông tin về thời gian cần thiết để lưu tài liệu, có thể chỉ ra một sự cố cụ thể đối với việc lưu vào thiết bị của bạn.

Nếu bạn chọn gửi cho chúng tôi dữ liệu chẩn đoán tùy chọn, dữ liệu chẩn đoán bắt buộc cũng sẽ được bao gồm.

Là người quản trị cho tổ chức của bạn, bạn sẽ có thể sử dụng cài đặt chính sách để chọn mức độ dữ liệu chẩn đoán được gửi cho chúng tôi. Dữ liệu chẩn đoán tùy chọn sẽ được gửi đến Microsoft trừ khi bạn thay đổi cài đặt. Việc cung cấp dữ liệu chẩn đoán tùy chọn tốt hơn cho phép nhóm kỹ thuật Office tại Microsoft phát hiện, chẩn đoán và giảm thiểu các sự cố để giảm tác động đến tổ chức của bạn.

Người dùng của bạn sẽ không thể thay đổi cấp độ dữ liệu chẩn đoán cho thiết bị của họ nếu họ đăng nhập vào Office bằng thông tin đăng nhập tổ chức của họ, đôi khi được gọi là tài khoản cơ quan hoặc trường học.

Dữ liệu chẩn đoán này không bao gồm tên của người dùng, địa chỉ email hoặc nội dung của các tệp Office của họ. Hệ thống của chúng tôi tạo một ID duy nhất liên kết với dữ liệu chẩn đoán của người dùng của bạn. Khi chúng tôi nhận được dữ liệu chẩn đoán cho thấy một trong số các ứng dụng của chúng tôi đã gặp sự cố 100 lần, ID duy nhất này sẽ cho phép chúng tôi xác định xem đó có phải là một người dùng đã gặp sự cố 100 lần hay không đó là 100 người dùng khác nhau từng gặp sự cố một lần. Chúng tôi không sử dụng ID duy nhất này để xác định một người dùng cụ thể.

Để xem dữ liệu chẩn đoán nào đang được gửi tới Microsoft, bạn có thể sử dụng Trình xem dữ liệu chẩn đoán mà bạn có thể tải xuống và cài đặt miễn phí từ Microsoft Store.

Để biết thêm thông tin, hãy xem các nguồn sau:

- [Dữ liệu chẩn đoán bắt buộc cho Office](required-diagnostic-data.md)
- [Dữ liệu chẩn đoán tuỳ chọn cho Office](optional-diagnostic-data.md)
- [Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)
- [Sử dụng tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office cho máy Mac](mac-privacy-preferences.md)
- [Sử dụng Trình xem chẩn đoán dữ liệu với Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="connected-experiences-for-office-365-proplus"></a>Các trải nghiệm được kết nối cho Office 365 ProPlus

Office 365 ProPlus bao gồm các ứng dụng phần mềm máy khách và các trải nghiệm được kết nối được thiết kế để cho phép bạn tạo, giao tiếp và cộng tác hiệu quả hơn. Làm việc với những người khác trên một tài liệu được lưu trữ trên OneDrive for Business hoặc dịch nội dung của tài liệu Word sang một ngôn ngữ khác là những ví dụ về trải nghiệm được kết nối.

Chúng tôi hiểu rằng bạn có thể muốn chọn loại trải nghiệm được kết nối có sẵn cho người dùng của mình khi làm việc trong các ứng dụng Office. Là người quản trị cho tổ chức của bạn, bạn sẽ có thiết đặt chính sách cho phép bạn chọn có cung cấp các loại trải nghiệm được kết nối sau cho người dùng của mình hay không:

- **Trải nghiệm phân tích nội dung của bạn** Đây là trải nghiệm sử dụng nội dung Office của bạn để cung cấp đề xuất thiết kế, đề xuất điều chỉnh, dữ liệu thông tin chuyên sâu và các tính năng tương tự. Ví dụ: PowerPoint Designer hoặc Trình soạn thảo trong Word.

- **Trải nghiệm tải xuống nội dung trực tuyến** Đây là trải nghiệm giúp bạn tìm kiếm và tải xuống nội dung trực tuyến, bao gồm các mẫu, hình ảnh, mô hình 3D, video và các tài liệu tham khảo để cải thiện tài liệu của bạn. Ví dụ: mẫu Office hoặc Trình Bắt đầu Nhanh PowerPoint.

Ví dụ: bạn có thể chọn cung cấp cho người dùng của mình trải nghiệm được kết nối tải xuống nội dung trực tuyến, nhưng không phải là trải nghiệm kết nối phân tích nội dung. Nếu bạn không cấu hình các cài đặt chính sách này, tất cả những trải nghiệm được kết nối này sẽ có sẵn cho người dùng của bạn.

Ngoài ra, có một thiết đặt có thể cho phép bạn tắt các trải nghiệm kết nối này, đồng thời cũng sẽ tắt luôn các trải nghiệm kết nối khác, chẳng hạn như tài liệu đồng tác giả và dung lượng lưu trữ tệp trực tuyến. Tuy nhiên, ngay cả khi bạn sử dụng thiết đặt chính sách này để tắt tất cả các trải nghiệm được kết nối, một số chức năng Office sẽ vẫn sẵn dùng, chẳng hạn như đồng bộ hộp thư của bạn trong Outlook, bằng cách sử dụng Teams hoặc Skype for Business, cũng như các dịch vụ thiết yếu được mô tả bên dưới.

Nếu bạn chọn không cung cấp người dùng của bạn với một số loại trải nghiệm được kết nối, hoặc dải băng hoặc menu lệnh cho những trải nghiệm được kết nối sẽ bị mờ đi hoặc những người dùng sẽ có được thông báo lỗi khi tìm cách sử dụng những trải nghiệm được kết nối.

Người dùng của bạn sẽ không thể chọn bật các trải nghiệm được kết nối hoặc tắt nếu họ được đăng nhập vào Office bằng thông tin đăng nhập tổ chức của họ, đôi khi được gọi là tài khoản cơ quan hoặc trường học.

Để biết thêm thông tin, hãy xem các nguồn sau:

- [Các trải nghiệm kết nối trong Office](connected-experiences.md)
- [Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)
- [Sử dụng tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office cho máy Mac](mac-privacy-preferences.md)

## <a name="optional-connected-experiences-for-office-365-proplus"></a>Các trải nghiệm được kết nối tùy chọn cho Office 365 ProPlus

Ngoài các trải nghiệm được kết nối được đề cập ở trên được bao gồm trong Office 365 ProPlus, có những trải nghiệm được kết nối tùy chọn mà bạn có thể chọn để cho phép người dùng của bạn truy cập bằng tài khoản tổ chức của họ. Ví dụ: các tính năng LinkedIn của Trợ lý Sơ yếu lý lịch trong Word hoặc các tính năng bản đồ 3D trong Excel mà sử dụng Bing.

Đây là những trải nghiệm được kết nối tùy chọn không nằm trong thỏa thuận thương mại của tổ chức của bạn với Microsoft nhưng bị chi phối bởi các điều khoản và điều kiện riêng biệt. Các trải nghiệm được kết nối tùy chọn do Microsoft cung cấp trực tiếp cho người dùng của bạn chịu sự điều chỉnh của [Thỏa thuận Dịch vụ của Microsoft](https://www.microsoft.com/servicesagreement) thay vì [Điều khoản Dịch vụ Trực tuyến](https://www.microsoft.com/licensing/product-licensing/products).

Do những trải nghiệm được kết nối tùy chọn này bị chi phối bởi các điều khoản và điều kiện riêng biệt, nên bạn quản lý chúng tách biệt với các trải nghiệm được kết nối được đề cập ở trên. Là người quản trị cho tổ chức của bạn, bạn sẽ có thể sử dụng cài đặt chính sách để chọn có cung cấp các trải nghiệm được kết nối tùy chọn này với tư cách là một nhóm cho người dùng của bạn hay không. Nếu bạn không cấu hình các cài đặt chính sách này, tất cả những trải nghiệm được kết nối tuỳ chọn này sẽ có sẵn cho người dùng của bạn.

Ngay cả khi bạn chọn cung cấp các trải nghiệm được kết nối tùy chọn này cho người dùng của mình, họ sẽ có tùy chọn tắt các trải nghiệm được kết nối tùy chọn này với tư cách là một nhóm bằng cách đi tới [hộp thoại cài đặt quyền riêng tư](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Người dùng của bạn sẽ chỉ có lựa chọn này nếu họ đăng nhập vào Office bằng thông tin đăng nhập tổ chức của họ (đôi khi được gọi là tài khoản cơ quan hoặc trường học), chứ không phải nếu họ đăng nhập bằng địa chỉ email cá nhân.

Để biết thêm thông tin, hãy xem các nguồn sau:

- [Tổng quan về trải nghiệm được kết nối tuỳ chọn trong Office](optional-connected-experiences.md)
- [Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)
- [Sử dụng tùy chọn để quản lý các biện pháp kiểm soát quyền riêng tư đối với Office cho máy Mac](mac-privacy-preferences.md)

## <a name="required-service-data-for-connected-experiences"></a>Dữ liệu dịch vụ bắt buộc cho trải nghiệm được kết nối

Dữ liệu dịch vụ bắt buộc là dữ liệu cho phép chúng tôi mang lại các trải nghiệm được kết nối trên nền điện toán đám mây này và giúp làm cho các trải nghiệm này an toàn và hoạt động như mong đợi. Dữ liệu dịch vụ bắt buộc gồm ba loại thông tin sau:

- **Nội dung khách hàng** là nội dung bạn tạo bằng cách sử dụng Office, chẳng hạn như văn bản đã được nhập trong tài liệu Word.
- **Dữ liệu chức năng** bao gồm thông tin mà trải nghiệm được kết nối cần để thực hiện nhiệm vụ của mình, chẳng hạn như thông tin cấu hình về ứng dụng.
- **Dữ liệu chẩn đoán dịch vụ** là dữ liệu cần thiết để giữ an toàn cho dịch vụ, cập nhật và hoạt động như mong đợi. Vì dữ liệu này liên quan chặt chẽ đến trải nghiệm được kết nối, nên nó tách biệt với các mức độ dữ liệu chẩn đoán bắt buộc hoặc tùy chọn.

Để giúp bạn hiểu về dữ liệu dịch vụ bắt buộc, sau đây là một kịch bản ví dụ, sử dụng PowerPoint Designer, đây là trải nghiệm được kết nối mà bạn có thể sử dụng khi tạo các trang chiếu cho bản trình bày. PowerPoint Designer giúp cải thiện các trang chiếu của bạn bằng cách tự động tạo các ý tưởng thiết kế mà bạn có thể chọn. Khi bạn dự định đưa nội dung vào một trang chiếu, Trình thiết kế sẽ hoạt động trong nền để khớp nội dung đó với các bố trí được thiết kế chuyên nghiệp.

Dữ liệu dịch vụ bắt buộc được gửi tới Microsoft để cho phép trải nghiệm được kết nối dành cho bạn này có thể bao gồm các thông tin sau:

- *Nội dung khách hàng*, chẳng hạn như văn bản hoặc hình ảnh mà bạn đã thêm vào trang chiếu của mình.
- *Dữ liệu chức năng*, chẳng hạn như trang chiếu mà bạn đang làm việc và bố trí.
- *Dữ liệu chẩn đoán dịch vụ*, chẳng hạn như các sự kiện cho chúng tôi biết nếu ý tưởng thiết kế được áp dụng chính xác trang chiếu của bạn và các cuộc gọi dịch vụ đang thực hiện một cách chính xác.

Nếu bạn chọn không cung cấp cho người dùng của bạn loại trải nghiệm được kết nối trong đó có PowerPoint Designer, tính năng sẽ bị tắt và sẽ không có dữ liệu dịch vụ bắt buộc nào được gửi cho chúng tôi.

Để biết thêm thông tin, hãy xem mục [Dữ liệu dịch vụ bắt buộc cho Office](required-service-data.md).

## <a name="essential-services-for-office-365-proplus"></a>Các dịch vụ cần thiết cho Office 365 ProPlus

Ngoài ra còn có một tập hợp các dịch vụ rất cần thiết cho cách thức Office 365 ProPlus hoạt động và không thể bị tắt. Ví dụ: dịch vụ cấp phép xác nhận rằng bạn được cấp phép sử dụng Office 365 ProPlus đúng cách. Dữ liệu dịch vụ bắt buộc về các dịch vụ này sẽ được thu thập và gửi đến Microsoft, không phụ thuộc vào việc bạn đã đặt cấu hình thiết đặt chính sách nào.

Để biết thêm thông tin, hãy xem mục [Các dịch vụ cần thiết cho Office](essential-services.md).

## <a name="related-topics"></a>Chủ đề liên quan
- [Quyền riêng tư tại Microsoft](https://privacy.microsoft.com/)
- [Quyền riêng tư trong Windows](https://docs.microsoft.com/windows/privacy/)
