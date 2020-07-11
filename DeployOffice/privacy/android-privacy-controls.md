---
title: Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android
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
description: Cung cấp cho người quản trị Office thông tin về cách quản lý kiểm soát quyền riêng tư cho Office trên thiết bị Android.
hideEdit: true
ms.openlocfilehash: 6086ecd1b2cd55bbf6cb4577879714f1d20a2f93
ms.sourcegitcommit: 81295dff0f2fa474f0db39fd40560e3a23fff32a
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 07/09/2020
ms.locfileid: "45092140"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a>Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android

Sẽ có các thiết đặt chính sách mới cho Office trên thiết bị Android cho phép bạn kiểm soát các thiết đặt liên quan đến vấn đề sau đây:

- ***Dữ liệu chẩn đoán*** về phần mềm máy khách Office được sử dụng được thu thập và gửi cho Microsoft.

- ***Trải nghiệm được kết nối*** sử dụng chức năng trên nền đám mây để cung cấp các tính năng Office nâng cao cho bạn và người dùng của bạn.

Để biết thêm thông tin về dữ liệu chẩn đoán và trải nghiệm được kết nối, hãy xem mục [Tổng quan về các biện pháp kiểm soát quyền riêng tư](overview-privacy-controls.md).

Các thiết đặt chính sách này sẽ áp dụng cho các ứng dụng sau đây:
- Phiên bản 16.0.12228.20260 trở lên trong Word for Android, Excel for Android và PowerPoint for Android.
- Phiên bản 4.1.71 trở lên trong Outlook for Android.
- Phiên bản 16.0.12228.20004 trở lên trong OneNote for Android.
- Phiên bản 5.47 trở lên trong OneDrive for Android.
- Phiên bản 16.0.12430.20254 trở lên của ứng dụng Office dành cho Android.

## <a name="policy-settings-available-for-office-on-android-devices"></a>Các thiết đặt chính sách sẵn dùng cho Office trên các thiết bị chạy Android

Bảng sau liệt kê các thiết đặt chính sách nào sẵn dùng cho Office trên thiết bị Android và liên kết đến thông tin bổ sung về từng thiết đặt chính sách.

> [!NOTE]
>- Thông tin bổ sung được cung cấp bao gồm các thiết đặt chính sách đối với Office trên các thiết bị chạy Windows. Nhưng thông tin tương tự sẽ áp dụng cho Office trên các thiết bị chạy Android vì chúng là các thiết đặt chính sách tương tự.
>- * cho phép sử dụng các trải nghiệm được kết nối trong thiết đặt chính sách Office* sẵn dùng cho Office trên các thiết bị chạy Windows không áp dụng cho Office trên thiết bị Android. 


|Tên của thiết đặt chính sách  |Thông tin bổ sung |
|---------|---------|
|Cấu hình mức độ dữ liệu chẩn đoán phần mềm máy khách được Office gửi cho Microsoft|[Thiết đặt chính sách dành cho dữ liệu chẩn đoán](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|Cho phép sử dụng trải nghiệm được kết nối phân tích nội dung trong Office| [Thiết đặt chính sách cho các trải nghiệm được kết nối phân tích nội dung của bạn](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|Cho phép sử dụng trải nghiệm được kết nối tải nội dung trực tuyến trong Office |[Thiết đặt chính sách cho các trải nghiệm được kết nối tải xuống nội dung trực tuyến](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|Cho phép sử dụng các trải nghiệm được kết nối tùy chọn bổ sung trong Office |[Thiết đặt chính sách cho các trải nghiệm được kết nối tuỳ chọn](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a>Sử dụng dịch vụ chính sách đám mây của Office để áp dụng các thiết đặt chính sách

Để áp dụng bất kỳ thiết đặt chính sách nào trong số 4 thiết đặt này cho Office trên thiết bị Android, bạn cần sử dụng dịch vụ chính sách đám mây của Office. Để biết thêm thông tin về việc sử dụng dịch vụ chính sách đám mây của Office, hãy xem mục [Tổng quan về dịch vụ chính sách đám mây của Office](../overview-office-cloud-policy-service.md).

> [!NOTE]
> Nếu trước đây bạn đã sử dụng dịch vụ chính sách đám mây của Office để đặt cấu hình các thiết đặt chính sách này cho Office trên các thiết bị chạy Windows, thì các thiết đặt tương tự đó sẽ áp dụng cho Office trên thiết bị Android. Để điều đó xảy ra, bạn chỉ cần đăng nhập vào dịch vụ chính sách đám mây của Office và dịch vụ sẽ tự động áp dụng các thiết đặt cho Office trên thiết bị Android.
