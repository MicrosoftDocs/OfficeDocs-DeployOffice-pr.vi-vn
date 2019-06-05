---
title: Dữ liệu chẩn đoán bắt buộc cho Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Cung cấp cho quản trị viên Office thông tin về dữ liệu chẩn đoán bắt buộc trong Office và cung cấp danh sách các sự kiện và trường dữ liệu.
hideEdit: true
ms.openlocfilehash: a5ac5dfded3dbb51693b5d15616675b067c59dc3
ms.sourcegitcommit: 3f5de6281b8e92c6c41a800f4374211188460320
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 06/04/2019
ms.locfileid: "34701720"
---
# <a name="required-diagnostic-data-for-office"></a>Dữ liệu chẩn đoán bắt buộc cho Office

> [!IMPORTANT]
> Thông tin trong bài viết này áp dụng cho Phiên bản 1904 trở lên của phần mềm máy khách Office sau được cài đặt trên máy tính chạy Windows:
> - Office 365 Business và Office 365 ProPlus.
> - Office 365 Personal, Office 365 Home hoặc các phiên bản Office khác là một phần của đăng ký Office 365.
> - Project và Visio đi kèm với một số gói đăng ký, chẳng hạn như gói Project Online Professional hoặc Visio Online Plan 2.

Dữ liệu chẩn đoán được sử dụng để giữ cho Office an toàn và cập nhật, phát hiện, chẩn đoán và khắc phục sự cố cũng như giúp cải thiện sản phẩm. Dữ liệu này không bao gồm tên người dùng hoặc địa chỉ email, nội dung của các tệp của người dùng hoặc thông tin về các ứng dụng không liên quan đến Office.

Dữ liệu chẩn đoán được thu thập và gửi cho Microsoft về phần mềm máy khách Office đang được sử dụng trên các máy tính chạy Windows. Một số dữ liệu chẩn đoán là bắt buộc, trong khi một số dữ liệu chẩn đoán là tùy chọn. Chúng tôi cung cấp cho bạn khả năng chọn gửi cho chúng tôi dữ liệu chẩn đoán bắt buộc hoặc tùy chọn thông qua việc sử dụng các kiểm soát quyền riêng tư, chẳng hạn như thiết đặt chính sách cho các tổ chức. Bạn có thể thấy dữ liệu chẩn đoán được gửi cho chúng tôi bằng cách sử dụng Trình xem dữ liệu chẩn đoán.

***Dữ liệu chẩn đoán bắt buộc*** là ữ liệu tối thiểu cần thiết để giúp Office an toàn, cập nhật và hoạt động như mong đợi trên thiết bị mà nó được cài đặt.

Dữ liệu chẩn đoán bắt buộc giúp xác định các sự cố với Office có thể liên quan đến cấu hình thiết bị hoặc phần mềm. Ví dụ: nó có thể giúp xác định xem một tính năng Office có gặp sự cố thường xuyên hơn trên một phiên bản hệ điều hành cụ thể không, với các tính năng mới được giới thiệu hoặc khi một số tính năng Office nhất định bị tắt. Dữ liệu chẩn đoán bắt buộc giúp chúng tôi phát hiện, chẩn đoán và khắc phục các sự cố này nhanh hơn để giảm tác động đối với người dùng hoặc tổ chức.

Để biết thêm thông tin về dữ liệu chẩn đoán, hãy xem các mục sau:

- [Dữ liệu chẩn đoán tuỳ chọn cho Office](optional-diagnostic-data.md)
- [Sử dụng Trình xem chẩn đoán dữ liệu với Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Nếu bạn là người quản trị cho tổ chức của bạn, bạn cũng có thể quan tâm đến những điều sau:

- [Tổng quan về kiểm soát quyền riêng tư cho Office 365 ProPlus](overview-privacy-controls.md)
- [Sử dụng thiết đặt chính sách để quản lý kiểm soát quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)

## <a name="categories-data-subtypes-events-and-data-fields-for-required-diagnostic-data"></a>Danh mục, loại dữ liệu con, sự kiện và trường dữ liệu cho dữ liệu chẩn đoán được yêu cầu

Dữ liệu chẩn đoán bắt buộc được sắp xếp thành các danh mục và những loại dữ liệu con. Trong mỗi loại dữ liệu con là các sự kiện, chứa các trường dữ liệu dành riêng cho sự kiện đó.

Bảng sau đây cung cấp danh sách các danh mục cho dữ liệu chẩn đoán bắt buộc. Các loại dữ liệu con trong mỗi danh mục được liệt kê, cùng với một mô tả về tiêu điểm cho kiểu dữ liệu con đó. Có các liên kết đến từng phần loại dữ liệu con nơi bạn sẽ tìm thấy thông tin sau:

- Danh sách các sự kiện trong loại dữ liệu con đó
- Mô tả về từng sự kiện
- Danh sách các trường dữ liệu trong mỗi sự kiện
- Mô tả về từng trường dữ liệu

| **Danh mục**       | **Loại dữ liệu con**| **Mô tả**    |
| ---------- | ------------- | ---- |
| **Thiết lập phần mềm và hàng tồn kho** | [Thiết lập Office và hàng tồn kho](#office-setup-and-inventory-subtype)   | Sản phẩm được cài đặt và phiên bản và trạng thái cài đặt.  |
| | [Cấu hình phần bổ trợ Office](#office-add-in-configuration-subtype)  | Phần bổ trợ phần mềm và các thiết đặt.     |
| | [Bảo mật](#security-subtype)  | Tài liệu, tính năng và các điều kiện lỗi phần bổ trợ có thể ảnh hưởng đến bảo mật, bao gồm tính sẵn sàng cập nhật sản phẩm.  |
| **Sử dụng sản phẩm và dịch vụ**    | [Mức độ thành công của tính năng ứng dụng ](#application-feature-success-subtype)   | Thành công của chức năng ứng dụng. Giới hạn mở và đóng ứng dụng và tài liệu, chỉnh sửa tệp và chia sẻ tệp (cộng tác). |
| | [Trạng thái ứng dụng và khởi động](#application-status-and-boot-subtype)    | Xác định xem các sự kiện tính năng cụ thể đã xảy ra hay chưa, chẳng hạn như bắt đầu hoặc dừng và tính năng có đang hoạt động hay không.   |
| | [Cấu hình khả năng truy nhập Office](#office-accessibility-configuration-subtype)  | Các tính năng trợ năng của Office       |
| **Hiệu suất sản phẩm và dịch vụ**       | [Ứng dụng bất ngờ (gặp sự cố)](#unexpected-application-exit-crash-subtype)  | Ứng dụng bất ngờ thoát và trạng thái của ứng dụng khi điều đó xảy ra.    |
|  | [Hiệu suất tính năng ứng dụng ](#application-feature-performance-subtype)  | Thời gian phản hồi hoặc hiệu suất kém cho các tình huống như ứng dụng khởi động hoặc mở tệp. |
|  | [Lỗi hoạt động ứng dụng](#application-activity-error-subtype)   | Lỗi về chức năng của một tính năng hoặc trải nghiệm người dùng.  |
| **Khả năng kết nối và cấu hình thiết bị** | [Khả năng kết nối và cấu hình thiết bị](#device-connectivity-and-configuration-subtype) | Trạng thái kết nối mạng và cài đặt thiết bị, chẳng hạn như bộ nhớ. |


> [!NOTE]
> - Các danh mục được hiển thị trong Trình xem dữ liệu chẩn đoán, nhưng các loại dữ liệu con không được hiển thị.
> - Một trường dữ liệu được đánh dấu là *Đã lỗi thời* đã hoặc sẽ sớm bị xóa khỏi dữ liệu chẩn đoán bắt buộc. Một trong số các trường dữ liệu này là các bản sao phát sinh khi dữ liệu chẩn đoán được hiện đại hóa và được sử dụng để đảm bảo không có sự gián đoạn dịch vụ đối với các báo cáo giám sát chẩn đoán trực tiếp.

## <a name="categories-and-data-fields-that-are-common-for-all-events"></a>Danh mục và trường dữ liệu phổ biến cho tất cả các sự kiện

Có một số thông tin về các sự kiện phổ biến cho tất cả các sự kiện, bất kể danh mục hoặc loại dữ liệu con là gì đi chăng nữa. Thông tin phổ biến này, đôi khi được gọi là *hợp đồng dữ liệu*, được sắp xếp vào các danh mục. Mỗi danh mục chứa các trường và các trường này đều là các trường siêu dữ liệu và có thuộc tính của một sự kiện riêng lẻ. Bạn có thể xem thông tin này bằng cách sử dụng Trình xem dữ liệu chẩn đoán.

Danh mục thông tin được thu thập về các sự kiện có thể được chia thành hai nhóm:

  - [Thông tin phổ biến cho tất cả các sự kiện](#information-common-to-all-events)
  - [Thông tin hỗ trợ đặc biệt việc thu thập dữ liệu chẩn đoán](#information-that-specifically-supports-diagnostic-data-collection)

### <a name="information-common-to-all-events"></a>*Thông tin phổ biến cho tất cả các sự kiện*

Thông tin phổ biến cho tất cả các sự kiện được thu thập trong các danh mục sau đây.

#### <a name="app"></a>Ứng dụng 

Thông tin về ứng dụng. Tất cả các trường là không đổi cho tất cả các phiên của một phiên bản ứng dụng nhất định.

Danh mục này chứa các trường sau đây:

  - **Branch** - Nhánh mà từ đó bản dựng nhất định được tạo. Cho phép chúng tôi xác định loại nhánh mà từ đó một bản dựng được tạo để chúng tôi có thể nhắm mục tiêu chính xác các bản sửa lỗi.
  - **InstallType** - Một bộ liệt kê xác định cách người dùng cài đặt ứng dụng. Cho phép chúng tôi xác định xem các cơ chế cài đặt cụ thể có tạo ra các sự cố không được nhận thấy trong các cơ chế cài đặt khác không.
  - **Name** - Tên của ứng dụng đang cung cấp dữ liệu. Cho phép chúng tôi xác định ứng dụng đang hiển thị sự cố để chúng tôi biết cách giải quyết.
  - **Platform** - Việc phân loại rộng rãi của nền tảng mà ứng dụng đang chạy. Cho phép chúng tôi xác định các vấn đề có thể xảy ra trên nền tảng nào để chúng tôi có thể ưu tiên chính xác vấn đề.
  - **Version** - Phiên bản của ứng dụng. Cho phép chúng tôi xác định phiên bản nào của sản phẩm đang hiển thị sự cố để chúng tôi có thể ưu tiên chính xác.

#### <a name="client"></a>Máy khách 

Mã định danh liên quan đến một phiên bản Office trên thiết bị. Không thay đổi cho tất cả các phiên của tất cả các ứng dụng của một phiên bản cài đặt nhất định cho các bộ đa ứng dụng hoặc không đổi cho tất cả các phiên của phiên bản ứng dụng nhất định.

Danh mục này chứa các trường sau đây:

  - **Id** - Mã định danh duy nhất được gán cho máy khách tại thời điểm cài đặt Office. Cho phép chúng tôi xác định xem các sự cố có ảnh hưởng đến một bộ cài đặt đã chọn hay không và có bao nhiêu người dùng bị ảnh hưởng.

#### <a name="consent"></a>Chấp thuận

Thông tin liên quan đến sự chấp thuận của người dùng đối với dữ liệu chẩn đoán và trải nghiệm được kết nối.

Danh mục này chứa các trường sau đây:

  - **UserCategory –** Xác định loại người dùng đã chấp thuận. Một trong số các lựa chọn sau: MSAUser, AADUser hoặc LocalDeviceUser

  - **DiagnosticConsentLevel** – Cho biết mức độ chấp thuận dữ liệu chẩn đoán mà người dùng đã đưa ra

  - **DiagnosticConsentSourceLocation** – Cho biết cách người dùng đã cung cấp sự chấp thuận cho dữ liệu chẩn đoán

  - **DiagnosticConsentConsentTime** – Cho biết khi người dùng cung cấp sự chấp thuận cho dữ liệu chẩn đoán

  - **ServiceConnectionState** – Cho biết người dùng đã chọn sử dụng hay không sử dụng tất cả các trải nghiệm được kết nối

  - **ServiceConnectionStateSourceLocation** – Cho biết cách người dùng cung cấp lựa chọn có sử dụng tất cả các trải nghiệm được kết nối hay không

  - **ServiceConnectionStateConsentTime** – Cho biết thời điểm người dùng chọn có sử dụng tất cả các trải nghiệm được kết nối hay không

  - **ControllerConnectedServicesState** – Cho biết người dùng đã có quyền truy cập vào các trải nghiệm được kết nối tùy chọn hay không

  - **ControllerConnectedServicesStateSourceLocation** – Cho biết cách lựa chọn của người dùng cho các trải nghiệm được kết nối tùy chọn đã được thực hiện

  - **ControllerConnectedServicesStateConsentTime** – Cho biết thời điểm người dùng chọn trạng thái trải nghiệm kết nối tùy chọn

  - **UserContentDependentState** – Cho biết người dùng đã chọn bật hay tắt các trải nghiệm được kết nối để phân tích nội dung

  - **UserContentDependentStateSourceLocation** – Cho biết cách lựa chọn bật hoặc tắt của người dùng được tạo cho các trải nghiệm được kết nối phân tích nội dung

  - **UserContentDependentStateConsentTime** – Cho biết thời điểm người dùng chọn bật hoặc tắt trải nghiệm được kết nối để phân tích nội dung được thực hiện

  - **DownloadContentState** – Cho biết người dùng đã chọn bật hay tắt các trải nghiệm được kết nối để tải xuống nội dung trực tuyến hay chưa

  - **DownloadContentStateSourceLocation** – Cho biết cách người dùng thực hiện lựa chọn bật hoặc tắt trải nghiệm được kết nối tải xuống nội dung trực tuyến

  - **DownloadContentStateConsentTime** – Cho biết thời điểm người dùng đưa ra lựa chọn bật hoặc tắt trải nghiệm được kết nối tải xuống nội dung trực tuyến.

#### <a name="device"></a>Thiết bị 

Thông tin về hệ điều hành và bản dựng.

Danh mục này chứa các trường sau đây:

  - **OsBuild** - Số bản dựng của hệ điều hành được cài đặt trên thiết bị. Cho phép chúng tôi xác định xem các sự cố có ảnh hưởng đến các gói dịch vụ riêng lẻ hoặc các phiên bản của một hệ điều hành nhất định khác với các vấn đề khác hay không để chúng tôi có thể ưu tiên các sự cố.

  - **OsVersion** - Phiên bản chính của hệ điều hành được cài đặt trên thiết bị. Cho phép chúng tôi xác định xem các sự cố có ảnh hưởng đến một phiên bản hệ điều hành cụ thể hơn các sự cố khác hay không để chúng tôi có thể ưu tiên các sự cố.

#### <a name="legacy"></a>Kế thừa 

Cung cấp phiên bản hệ điều hành và ID ứng dụng để tương thích với các thực tiễn thu thập kế thừa hiện có.

Danh mục này chứa các trường sau đây:

  - **AppId** - Giá trị bộ liệt kê cho biết ứng dụng đang gửi dữ liệu. Cho phép chúng tôi xác định ứng dụng đang hiển thị sự cố để chúng tôi biết cách giải quyết.

  - **OsEnv** - Bộ liệt kê cho biết hệ điều hành mà trên đó phiên đang hoạt động. Cho phép chúng tôi xác định hệ điều hành xảy ra sự cố để chúng tôi có thể ưu tiên các sự cố.

#### <a name="release"></a>Bản phát hành 

Thông tin liên quan đến kênh phát hành. Tất cả các trường là không đổi cho tất cả các phiên của tất cả các ứng dụng của một phiên bản cài đặt nhất định. Xác định một nhóm tất cả các thiết bị trong một giai đoạn của chu kỳ phát hành sản phẩm.

Danh mục này chứa các trường sau đây:

  - **Audience** - Xác định người xem phụ của một nhóm đối tượng người dùng nhất định. Cho phép chúng tôi theo dõi các tập hợp con của các nhóm người xem để đánh giá mức độ phổ biến và mức độ ưu tiên của các sự cố.

  - **AudienceGroup** - Xác định vòng mà dữ liệu đến từ. Cho phép chúng tôi triển khai các tính năng theo giai đoạn và xác định các sự cố tiềm ẩn trước khi chúng đến được với hầu hết người dùng.

  - **Channel** - Các kênh mà thông qua đó sản phẩm đang được phát hành. Cho phép chúng tôi xác định xem một sự cố có ảnh hưởng đến một trong các kênh triển khai của chúng tôi khác với các kênh khác không.

  - **Fork** - Xác định nhánh của sản phẩm. Cho phép một cơ chế tổng hợp dữ liệu trên một tập hợp các số bản dựng để xác định các sự cố liên quan đến một bản phát hành nhất định.

#### <a name="session"></a>Phiên 

Thông tin về phiên quy trình. Tất cả các trường đều không đổi cho phiên này.

Danh mục này chứa các trường sau đây:

  - **ABConfigs** - Xác định tập hợp các chuyến bay đang chạy trong một phiên nhất định. Cho phép chúng tôi xác định các chuyến bay riêng lẻ đang chạy trên một phiên để chúng tôi có thể xác định xem chuyến bay đó có phải là nguồn gốc của sự cố ảnh hưởng đến người dùng hay không.

  - **EcsETag** - Một chỉ báo từ hệ thống bay đại diện cho các chuyến bay được gửi đến máy. Cho phép chúng tôi xác định chuyến bay có thể ảnh hưởng đến một phiên nhất định.

  - **Flags** - Cờ theo dõi Bitmask áp dụng cho toàn bộ phiên, hiện chủ yếu tập trung vào các tùy chọn lấy mẫu và dữ liệu chẩn đoán. Cho phép chúng tôi kiểm soát cách một phiên nhất định hoạt động liên quan đến dữ liệu chẩn đoán mà phiên tạo ra.

  - **Id** - Xác định duy nhất một phiên dữ liệu nhất định. Cho phép chúng tôi xác định sự ảnh hưởng của sự cố bằng cách đánh giá số lượng các phiên được bị ảnh hưởng và nếu có các tính năng phổ biến của các phiên đó.

  - **ImpressionId** - Xác định tập hợp các chuyến bay đang chạy trong một phiên nhất định. Cho phép chúng tôi xác định các chuyến bay riêng lẻ đang chạy trên một phiên để chúng tôi có thể xác định xem chuyến bay đó có phải là nguồn gốc của sự cố ảnh hưởng đến người dùng hay không.

  - **MeasuresEnabled** - Cờ cho biết liệu dữ liệu phiên hiện tại có được lấy mẫu hay không. Cho phép chúng tôi xác định cách đánh giá một cách thống kê dữ liệu được thu thập từ phiên nhất định.

  - **SamplingClientId** - ID của máy khách được sử dụng để xác định xem đó có phải là một phần của việc lấy mẫu hay không. Cho phép chúng tôi xác định lý do tại sao một phiên riêng lẻ được bao gồm hoặc loại trừ khỏi việc lấy mẫu.

#### <a name="user"></a>Người dùng

Cung cấp thông tin đối tượng thuê cho SKU phần mềm thương mại.

Danh mục này chứa các trường sau đây:

  - **PrimaryIdentityHash** – Mã định danh giả đại diện cho người dùng hiện tại.

  - **PrimaryIdentitySpace** – Loại danh tính có trong PrimaryIdentityHash. Một trong các lựa chọn sau: MASCID, OrgIdCID hoặc UserObjectId.

  - **TenantGroup** - Loại đối tượng thuê mà đăng ký thuộc về. Cho phép chúng tôi phân loại các sự cố và xác định xem một vấn đề có phổ biến hay bị cô lập đối với một nhóm người dùng hay không.

  - **TenantId** - Đối tượng thuê mà một đăng ký của người dùng được liên kết. Cho phép chúng tôi phân loại các sự cố và xác định xem một vấn đề có phổ biến hay bị cô lập đối với một nhóm người dùng hoặc một đối tượng thuê cụ thể hay không.

### <a name="information-that-specifically-supports-diagnostic-data-collection"></a>*Thông tin hỗ trợ đặc biệt việc thu thập dữ liệu chẩn đoán*

Thông tin hỗ trợ đặc biệt việc thu thập dữ liệu chẩn đoán được thu thập trong các danh mục sau.

#### <a name="activity"></a>Hoạt động

Thông tin để hiểu được sự thành công của chính sự kiện bộ sưu tập.

Danh mục này chứa các trường sau đây:

  - **AggMode** - Thông báo cho hệ thống biết cách tổng hợp kết quả hoạt động. Cho phép chúng tôi giảm lượng thông tin được tải lên từ máy người dùng bằng cách tổng hợp kết quả hoạt động thành một sự kiện duy nhất được gửi định kỳ.

  - **Count** - Số lần hoạt động xảy ra nếu số lượng là từ một sự kiện tổng hợp. Cho phép chúng tôi xác định tần suất một hoạt động thành công hay thất bại dựa trên chế độ tổng hợp của hoạt động.

  - **CV** - Một giá trị xác định mối quan hệ giữa các hoạt động và hoạt động con. Cho phép chúng tôi để xây dựng lại mối quan hệ giữa các hoạt động lồng nhau.

  - **Duration** - Khoảng thời gian hoạt động cần để thực hiện. Cho phép chúng tôi xác định sự cố về hiệu suất ảnh hưởng tiêu cực đến trải nghiệm người dùng.

  - **Result**.**Code** - Một ứng dụng xác định mã để xác định một kết quả nhất định. Cho phép chúng tôi xác định chi tiết cụ thể hơn về một lỗi cụ thể, chẳng hạn như mã lỗi có thể được sử dụng để phân loại và khắc phục các sự cố.

  - **Result.Tag** - Thẻ số nguyên xác định vị trí trong mã nơi kết quả được tạo. Cho phép chúng tôi xác định rõ vị trí trong mã nơi tạo ra kết quả cho phép phân loại lỗi.

  - **Result**.**Type** - Loại mã kết quả. Xác định loại mã kết quả đã được gửi để giá trị có thể được diễn giải chính xác.

  - **Success** - Cờ cho biết xem hoạt động thành công hay thất bại. Cho phép chúng tôi xác định xem các thao tác mà người dùng thực hiện trong sản phẩm sẽ thành công hay thất bại. Điều này cho phép chúng tôi xác định các sự cố đang ảnh hưởng đến người dùng.

#### <a name="application"></a>Ứng dụng 

Thông tin về việc cài đặt ứng dụng mà từ đó các sự kiện sẽ được thu thập.

Danh mục này chứa các trường sau đây:

  - **Architecture** - Kiến trúc của ứng dụng. Hãy để chúng tôi phân loại các lỗi có thể đặc trưng cho kiến trúc của ứng dụng.

  - **Click2RunPackageVersion** - Số phiên bản của gói Click-To-Run đã cài đặt ứng dụng. Cho phép chúng tôi xác định phiên bản nào của trình cài đặt đã được sử dụng để cài đặt Office để chúng tôi có thể xác định các sự cố liên quan đến thiết lập.

  - **DistributionChannel** - Kênh nơi ứng dụng được triển khai. Cho phép chúng tôi phân vùng dữ liệu đến để chúng tôi có thể xác định xem các sự cố có ảnh hưởng đến người xem hay không.

  - **InstallMethod** - Bản dựng hiện tại của Office đã được nâng cấp từ bản dựng cũ hơn, được quay lại bản dựng cũ hơn hay bản cài đặt mới.

  - **IsClickToRunInstall** - Cờ cho biết nếu cài đặt là một thao tác cài đặt click-to-run. Cho phép chúng tôi xác định các sự cố có thể cụ thể đối với cơ chế cài đặt Click-To-Run.

  - **IsDebug** - Cờ cho biết nếu bản dựng office là một bản dựng gỡ lỗi. Cho phép chúng tôi xác định xem các sự cố đến từ các bản dựng Gỡ lỗi có thể hoạt động khác đi hay không.

  - **IsInstalledOnExternalStorage** - Cờ cho biết nếu Office đã được cài đặt trên thiết bị lưu trữ ngoài. Hãy để chúng tôi xác định xem các sự cố có thể được truy tìm đến một vị trí lưu trữ bên ngoài hay không.

  - **IsOEMInstalled** - Cờ cho biết nếu Office được cài đặt bởi nhà sản xuất thiết bị gốc (OEM). Hãy để chúng tôi xác định xem ứng dụng đã được cài đặt bởi OEM có thể giúp chúng tôi phân loại và xác định sự cố.

  - **PreviousVersion** - Phiên bản Office đã được cài đặt trước đó trên máy. Cho phép chúng tôi để quay trở lại phiên bản trước đó nếu phiên bản hiện tại gặp sự cố.

  - **ProcessFileName** - Tên của tên tệp ứng dụng. Cho phép chúng tôi xác định tên của tệp thực thi đang tạo dữ liệu vì có thể có một số tên tệp quy trình khác nhau được báo cáo là cùng một tên ứng dụng.

#### <a name="client"></a>Máy khách

Thông tin về máy khách Office.

Danh mục này chứa các trường sau đây:

  - **FirstRunTime** - Lần đầu tiên máy khách được chạy. Cho phép chúng tôi tìm hiểu về khoảng thời gian máy khách đã cài đặt Office.

#### <a name="device"></a>Thiết bị

Thông tin về cấu hình và chức năng của thiết bị.

Danh mục này chứa các trường sau đây:

  - **DigitizerInfo** - Thông tin về bộ số hóa được sử dụng bởi máy. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **FormFactor** - Xác định các yếu tố biểu mẫu mà thiết bị gửi thông tin. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **FormFactorFamily** - Xác định các yếu tố biểu mẫu mà thiết bị gửi thông tin. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **HorizontalResolution** - Độ phân giải ngang của màn hình thiết bị. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **Id** - Mã định danh duy nhất cho thiết bị. Cho phép chúng tôi xác định phân phối của sự cố trên một tập hợp các thiết bị.

  - **IsEDPPolicyEnabled** - Cờ cho biết nếu bảo vệ dữ liệu nâng cao được bật trên máy. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **IsTerminalServer** - Cờ để xác định xem máy có phải là máy chủ đầu cuối hay không. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **Manufacturer** Nhà sản xuất của thiết bị. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **Model** - Model của thiết bị. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **MotherboardUUIDHash** - Hàm băm của mã định danh duy nhất cho bo mạch chủ. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **Name** - Tên của thiết bị. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **NumProcPhysCores** - Số lượng lõi vật lý trên máy. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **OsLocale** - Ngôn ngữ của hệ điều hành đang chạy. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **Architecture** - Kiến trúc của bộ xử lý. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **ProcessorCount** - Số lượng bộ xử lý trên máy. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **ProcSpeedMHz** - Tốc độ của bộ xử lý. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **RamMB** - Dung lượng bộ nhớ của thiết bị. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **ScreenDepth** - Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **ScreenDPI** - Giá trị DPI của màn hình. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **SusClientId -** ID Windows Update của thiết bị mà Office đang chạy trên đó.

  - **SystemVolumeFreeSpaceMB** Lượng dung lượng sẵn dùng trên dung lượng hệ thống. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **SystemVolumeSizeMB** - Kích cỡ của dung lượng hệ thống trên máy. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **VerticalResolution** - Độ phân giải dọc của màn hình thiết bị. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **WindowErrorReportingMachineId** - Mã định danh máy duy nhất được cung cấp bởi báo cáo lỗi Windows. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

  - **WindowSqmMachineId** - Mã định danh duy nhất cho máy được cung cấp bởi Windows SQM. Cho phép chúng tôi phân loại dữ liệu dựa trên trục thiết bị.

#### <a name="event"></a>Sự kiện 

Thông tin cụ thể cho sự kiện, bao gồm cả mã định danh duy nhất của nó trong phiên.

Danh mục này chứa các trường sau đây:

  - **Contract** - Một danh sách của bất kỳ hợp đồng nào mà sự kiện đang thực hiện. Cho phép chúng tôi đánh giá xem dữ liệu nào là một phần của sự kiện riêng lẻ để chúng tôi có thể xử lý dữ liệu một cách hiệu quả.

  - **CV** - Giá trị cho phép chúng tôi xác định các sự kiện có liên quan đến nhau. Được sử dụng để chẩn đoán cho phép chúng tôi xác định các mẫu hành vi liên quan hoặc các sự kiện liên quan.

  - **Flags** - Thông tin được sử dụng để thay đổi cách một sự kiện nhất định phản ứng. Được sử dụng để quản lý cách xử lý một sự kiện nhất định cho mục đích tải dữ liệu lên Microsoft.

  - **Id** - Mã định danh duy nhất cho sự kiện. Cho phép chúng tôi xác định duy nhất các sự kiện đang được nhận.

  - **Name** - Tên của sự kiện. Cho phép xác định sự kiện đã được gửi từ máy khách.

  - **Rule** - Mã định danh của quy tắc tạo ra dữ liệu nếu nó được tạo bởi quy tắc. Cho phép chúng tôi xác định nguồn của một phần dữ liệu để chúng tôi có thể xác thực và quản lý các tham số của sự kiện đó

  - **RuleId** - Mã định danh của quy tắc tạo ra dữ liệu nếu nó được tạo bởi quy tắc. Cho phép chúng tôi xác định nguồn của một phần dữ liệu để chúng tôi có thể xác thực và quản lý các tham số của sự kiện đó.

  - **RuleInterfaces** - Bất kỳ giao diện nào được thực hiện theo quy tắc cụ thể. Cho phép chúng tôi phân loại và nhập dữ liệu dựa trên cấu trúc của nó nhằm đơn giản hóa việc xử lý dữ liệu.

  - **RuleVersion** - Mã định danh của quy tắc tạo ra dữ liệu nếu nó được tạo bởi quy tắc. Cho phép chúng tôi xác định nguồn của một phần dữ liệu để chúng tôi có thể xác thực và quản lý các tham số của sự kiện đó.

  - **SampleRate** - Một chỉ báo cho biết tỷ lệ phần trăm người dùng đang gửi đoạn dữ liệu này. Điều này cho phép chúng tôi phân tích thống kê dữ liệu và đối với các điểm dữ liệu rất phổ biến không yêu cầu phải gửi cho tất cả người dùng.

  - **SchemaVersion** - Phiên bản của sơ đồ được sử dụng để tạo dữ liệu chẩn đoán. Cần thiết để quản lý dữ liệu được gửi từ máy khách. Điều này cho phép thay đổi theo thời gian trong những dữ liệu được gửi từ mỗi máy khách.

  - **Sequence** - Bộ đếm xác định thứ tự mà một sự kiện đã được tạo trên máy khách. Cho phép dữ liệu được nhận được xếp theo thứ tự để chúng tôi có thể xác định các bước có thể dẫn đến sự cố đang ảnh hưởng đến máy khách.

  - **Source** - Quy trình nguồn đã được sử dụng để tải lên dữ liệu. Cần thiết để theo dõi từng quy trình tải lên của chúng tôi về trạng thái tổng thể và để giúp xác định các vấn đề với quy trình tải lên. Điều này cho phép chúng tôi giám sát các quy trình tải lên riêng lẻ để đảm bảo chúng vẫn tuân thủ.

  - **Time** - Thời gian mà sự kiện được tạo ra trên máy khách. Cho phép chúng tôi đồng bộ hóa và xác thực thứ tự các sự kiện được tạo trên máy khách cũng như thiết lập số liệu hiệu suất cho hướng dẫn người dùng. 

#### <a name="host"></a>Máy chủ

Thông tin về một ứng dụng lưu trữ một ứng dụng nhúng

Danh mục này chứa các trường sau đây:

  - **Id** - Mã định danh duy nhất được gán cho ứng dụng lưu trữ bởi ứng dụng nhúng.

  - **SessionId** - Mã định danh duy nhất trên toàn cầu cho phiên làm việc của máy chủ.

  - **Version** - Mã định danh phiên bản của tệp chính thực thi của máy chủ.

#### <a name="legacy"></a>Kế thừa

Thông tin cần thiết cho tương hợp hệ thống kế thừa.

Danh mục này chứa các trường sau đây:

  - **OsBuild** - Số bản dựng cụ thể của hệ điều hành. Cho phép chúng tôi xác định phiên bản của hệ điều hành mà dữ liệu chẩn đoán đến từ để ưu tiên các sự cố.

  - **OsBuildRevision** - Số lượng bản sửa đổi của bản dựng của hệ diều hành. Cho phép chúng tôi xác định phiên bản của hệ điều hành mà dữ liệu chẩn đoán đến từ để ưu tiên các sự cố.

  - **OsMinorVersion** - Phiên bản nhỏ của hệ điều hành. Cho phép chúng tôi xác định phiên bản của hệ điều hành mà dữ liệu chẩn đoán đến từ để ưu tiên các sự cố.

  - **OsVersionString** - Một chuỗi hợp nhất đại diện cho số bản dựng hệ điều hành. Cho phép chúng tôi xác định phiên bản của hệ điều hành mà dữ liệu chẩn đoán đến từ để ưu tiên các sự cố.

#### <a name="session"></a>Phiên

Thông tin về phiên quy trình.

Danh mục này chứa các trường sau đây:

  - **ABConfigsDelta** - Theo dõi sự khác biệt giữa dữ liệu ABConfigs hiện tại và giá trị trước đó. Cho phép chúng tôi theo dõi những chuyến bay mới trên máy để giúp xác định xem chuyến bay mới có chịu trách nhiệm cho sự cố hay không.

  - **CollectibleClassification** - Các lớp thông tin mà phiên có thể thu thập. Cho phép lọc các phiên dựa trên dữ liệu mà chúng sẽ có.

  - **DisableTelemetry** - Cờ cho biết khóa DisableTelemetry có được đặt hay không. Cho phép chúng tôi biết nếu một phiên không báo cáo dữ liệu chẩn đoán ngoài EssentialServiceMetadata.

  - **SamplingKey** - Khóa được sử dụng để xác định xem phiên có được lấy mẫu hay không. Cho phép chúng tôi hiểu rõ cách các phiên riêng lẻ đang lựa chọn xem chúng có được lấy mẫu hay không.

  - **SamplingMethod** - Phương pháp được sử dụng để xác định chính sách lấy mẫu. Cho phép chúng tôi hiểu dữ liệu nào đến từ một phiên.

  - **Sequence** - Mã định danh số duy nhất cho phiên. Cho phép sắp xếp các phiên để phân tích các sự cố sau đó có thể đã xảy ra.

  - **Start** - Thời gian khởi động của phiên quy trình. Cho phép chúng tôi thiết lập khi phiên bắt đầu.

  - **TimeZoneBiasInMinutes** - Sự khác biệt về số phút giữa giờ UTC và giờ địa phương. Cho phép bình thường hóa thời gian UTC trở lại giờ địa phương.

  - **SamplingClientIdValue** - Giá trị của khóa được sử dụng để xác định lấy mẫu. Cho phép chúng tôi xác định lý do tại sao một phiên được lấy mẫu hay không.

  - **SamplingDeviceIdValue** - Giá trị của khóa được sử dụng để xác định lấy mẫu. Cho phép chúng tôi xác định lý do tại sao một phiên được lấy mẫu hay không.

  - **SamplingSessionKValue** - Siêu dữ liệu lấy mẫu nâng cao. Được sử dụng để giúp đánh giá ý nghĩa thống kê của dữ liệu được nhận.

  - **SamplingSessionNValue** - Siêu dữ liệu lấy mẫu nâng cao. Được sử dụng để giúp đánh giá ý nghĩa thống kê của dữ liệu được nhận.

  - **TelemetryPermissionLevel** - Giá trị cho biết mức độ dữ liệu chẩn đoán mà người dùng đã chọn tham gia. Cho phép chúng tôi hiểu được mức độ dữ liệu chẩn đoán mong đợi từ một phiên.

## <a name="software-setup-and-inventory-data-events"></a>Sự kiện thiết lập và kiểm kê phần mềm

Sau đây là những loại dữ liệu con trong danh mục này:
- [Thiết lập và kiểm kê Office](#office-setup-and-inventory-subtype)
- [Cấu hình phần bổ trợ Office](#office-add-in-configuration-subtype)
- [Bảo mật](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*Thiết lập và loại kiểm kê con Office*

Sản phẩm được cài đặt và phiên bản và trạng thái cài đặt.

#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Áp dụng cho tất cả các ứng dụng chạy win32. Giúp chúng tôi hiểu được trạng thái của quá trình cập nhật của bộ công cụ (Thành công hay thất bại cùng với các chi tiết lỗi)

Các trường sau đây sẽ được thu thập:

- **build** - Phiên bản Office hiện đang được cài đặt

- **channel** Kênh mà Office đã được phân phối.

- **errorCode** - Mã lỗi cho biết lỗi

- **errorMessage** - Thông tin lỗi bổ sung

- **status** - Trạng thái hiện tại của bản cập nhật

- **targetBuild** -Phiên bản mà Office đang cập nhật lên

#### <a name="officecorrelationmetadatautccorrelationmetadata"></a>Office.CorrelationMetadata.UTCCorrelationMetadata

Thu thập siêu dữ liệu Office thông qua UTC để so sánh với dữ liệu tương đương được thu thập qua quy trình phép đo từ xa của Office để kiểm tra tính chính xác và tính đầy đủ của dữ liệu.

Các trường sau đây sẽ được thu thập:

- **abConfigs** - Danh sách ID tính năng để xác định tính năng nào được bật trên máy khách hoặc trống khi dữ liệu này không được thu thập.

- **abFlights** - "NoNL:NoFlights" khi chuyến bay tính năng không được thiết lập. Nếu không thì "holdoutinfo=unknown".

- **AppSessionGuid** - Mã định danh của một phiên ứng dụng cụ thể bắt đầu tại thời điểm tạo quy trình và tồn tại cho đến khi quy trình kết thúc. Nó được định dạng là GUID 128 bit tiêu chuẩn nhưng được cấu tạo gồm 4 phần. Bốn phần theo thứ tự là (1) ID quy trình 32 bit (2) ID phiên 16 bit (3) ID khởi động 16 bit (4) Thời gian tạo quy trình trong UTC 100ns 64 bit

- **appVersionBuild** - Số phiên bản bản dựng ứng dụng.

- **appVersionMajor** - Số phiên bản chính của ứng dụng.

- **appVersionMino** - Số phiên bản phụ của ứng dụng.

- **appVersionRevision** - Số phiên bản bản chỉnh sửa của ứng dụng.

- **audienceGroup** - Tên nhóm người xem bản phát hành

- **audienceId** - Tên người xem bản phát hành

- **channel** Kênh mà Office đã được phân phối.

- **deviceClass** - Yếu tố biểu mẫu thiết bị từ hệ điều hành

- **ecsETag** - Mã định danh thử nghiệm cho quy trình.

- **impressionId** - GUID cho biết bộ tính năng hiện tại.

- **languageTag** - Thẻ ngôn ngữ IETF giao diện người dùng Office hiện tại

- **officeUserID** - GUID được tạo ngẫu nhiên cho cài đặt Office này

- **osArchitecture** - Kiến trúc hệ điều hành

- **osEnvironment** - Một số nguyên cho biết về hệ điều hành (Windows, Android, iOS, Mac, v.v.).

- **osVersionString** Mã định danh hệ điều hành.

- **sessionID** - GUID được tạo ngẫu nhiên để xác định phiên ứng dụng

- **UTCReplace_AppSessionGuid** - Giá trị boolean không đổi. Luôn true.

#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Theo dõi nếu một gói cho Bảng tuỳ biến động đã được tải xuống. Được coi là cấu hình phần mềm vì gói phải được tải xuống thành công để cho phép máy khách hiển thị đúng trải nghiệm. Đặc biệt quan trọng trong đăng ký người tiêu dùng nơi chúng tôi sử dụng các bảng tuỳ biến để liên hệ với người dùng rằng giấy phép đã hết hạn. Được sử dụng để theo dõi siêu dữ liệu của gói nội dung động được sản phẩm tải xuống và lưu vào bộ nhớ đệm ẩn cũng như kết quả của các hoạt động được thực hiện trên gói: lỗi tải xuống, lỗi giải nén, kiểm tra tính nhất quán, lỗi bộ đệm ẩn, sử dụng gói, nguồn tải xuống.

Các trường sau đây sẽ được thu thập:

  - **Data\_CacheFolderNotCreated -** Cờ Boolean cho biết việc tạo thư mục bộ đệm có thành công hay không

  - **Data\_CdnPath – địa chỉ nguồn của gói -**

  - **Data\_EnsureCached -** Cờ Boolean cho biết nếu gói nội dung được lưu trữ

  - **Data\_ExistsAlready -** Cờ Boolean chỉ ra rằng gói đã được tải xuống trước đó và có một nỗ lực khác

  - **Data\_GetFileStreamFailed -** gói nguồn không sẵn dùng trong nguồn

  - **Data\_GetFileStreamFailedToCreateLocalFolder -** Sự kiện đĩa cục bộ gây ra lỗi trong việc tạo thư mục

  - **Data\_GetFileStreamFromPackageFailed -** Cờ cho biết nếu gói đã được tải xuống, nhưng máy khách không thể đọc nó

  - **Data\_GetFileStreamFromPackageSuccess -** nỗ lực thành công để đọc gói

  - **Data\_GetFileStreamSuccess -** Không có sự cố về đĩa cũng như sự cố về cấu hình mà không cho phép luồng tệp được đọc

  - **Data\_GetRelativePathsFailed -** đường dẫn tương đối không trỏ đến vị trí có thể truy nhập

  - **Data\_HashActualValue -** Giá trị hàm băm được trích xuất từ tên tệp khi gói được sử dụng

  - **Data\_HashCalculationFailed -** Lỗi khi tính toán hàm băm

  - **Data\_HashMatchFailed -** Hàm băm không khớp giữa tên gói và giá trị đăng ký được lưu trữ

  - **Data\_HashMatchSuccess -** Việc kiểm tra tính nhất quán của hàm băm được thực hiện thành công

  - **Data\_PackageDownloadRequestFailed -** không thể tải gói

  - **Data\_PackageDownloadRequestNoData -** Gói tải xuống không chứa dữ liệu

  - **Data\_PackageDownloadRequestSuccess -** Bản tải xuống thành công của một gói

  - **Data\_PackageExplodedSuccess -** Trạng thái nỗ lực giải nén

  - **Data\_PackageOpenFailed -** Nỗ lực thất bại trong việc mở tệp gói

  - **Data\_PackageOpenSuccess -** Nỗ lực thành công trong việc mở tệp gói

  - **Data\_SuccessHashValue -** Giá trị hàm băm được trích xuất từ tên tệp khi gói được tải xuống

  - **Data\_SuccessSource -** Bề mặt mà gói đã được tải xuống

#### <a name="officevisiovisiosku"></a>Office.Visio.VisioSKU

Ghi lại SKU Visio dù đó là tiêu chuẩn hay chuyên nghiệp. Cần thiết để phân loại các sự cố về dựa trên SKU.

Các trường sau đây sẽ được thu thập:

  - **Data\_VisioSKU**:**integer** - 0 cho SKU tiêu chuẩn và 1 cho SKU chuyên nghiệp

### <a name="office-add-in-configuration-subtype"></a>*Loại con cấu hình phần bổ trợ Office*

Phần bổ trợ phần mềm và các thiết đặt.

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a>Office.Extensibility.AppCommands.AppCmdProjectionStatus

Thu thập thông tin để theo dõi xem bản cài đặt phần bổ trợ Office nào đã cập nhật thành công dải băng so với cập nhật không thành công.

Được sử dụng để khắc phục các sự cố đăng ký phổ biến trong đó phần bổ trợ không được cài đặt đúng cách và không bao giờ hiển thị dẫn đến việc chúng không thể sử dụng được.

Các trường sau đây sẽ được thu thập:

  - Không có

#### <a name="officeextensibilitycatalogexchangegetentitlements"></a>Office.Extensibility.Catalog.ExchangeGetEntitlements

Dữ liệu liên quan đến thành công khi không truy xuất dữ liệu quyền phần bổ trợ cho người quản trị viên đối tượng thuê Office 365 gán phần bổ trợ. Được sử dụng cho các số liệu về trạng thái, biểu đồ và phân tích các vấn đề của khách hàng.

Các trường sau đây sẽ được thu thập:

  - **CachingResult -** Kết quả của nỗ lực lưu giá trị trả lại cuộc gọi dịch vụ

  - **ClientParameter -** Mã định danh máy khách được gửi trong cuộc gọi dịch vụ

  - **EntitlementsCount -** Số lượng quyền được mong đợi trong phản hồi cuộc gọi

  - **EntitlementsParsed -** Số lượng quyền được phân tích từ phản hồi

  - **IsAllEntitlementsParsed -** Số lượng quyền dự kiến có khớp với số lượng quyền được phân tích hay không

  - **ServiceCallHResult -** Kết quả được trả về bởi API cuộc gọi dịch vụ

  - **TelemetryId -** GUID đại diện cho một người dùng duy nhất

  - **UsedCache -** Phản hồi được lưu trong bộ nhớ đệm ẩn đã được sử dụng thay vì thực hiện cuộc gọi dịch vụ hay chưa

  - **VersionParameter -** Số phiên bản Office được gửi trong cuộc gọi dịch vụ

#### <a name="officeextensibilitycatalogexchangegetlastupdate"></a>Office.Extensibility.Catalog.ExchangeGetLastUpdate

Dữ liệu liên quan đến thành công khi không truy xuất dữ liệu quyền phần bổ trợ cho người quản trị viên đối tượng thuê Office 365 gán phần bổ trợ. Được sử dụng cho các số liệu về trạng thái, biểu đồ và phân tích các vấn đề của khách hàng. ExchangeGetLastUpdate sẽ luôn chạy khi khởi động như một phần của mã máy chủ và xác định xem hoạt động gán phần bổ trợ đã thay đổi cho người dùng hay chưa. Nếu vậy thì osf.DLL sẽ được tải để chúng tôi có thể gọi ExchangeGetEntitlements để nhận các hoạt động gán cụ thể (và ExchangeGetManifests sẽ được gọi để truy xuất bất kỳ bản kê mới nào cần thiết). ExchangeGetEntitlements (và ExchangeGetManifests) cũng có thể được gọi theo yêu cầu sau khi ứng dụng máy chủ đã chạy. Tốt nhất là không tải DLL lớn nếu chúng tôi không cần đến. Nếu không có sự kiện này trong phần Bắt buộc, chúng tôi sẽ không thể biết nếu người dùng không nhận được phần bổ trợ được gán cho họ nếu cuộc gọi dịch vụ đầu tiên đó không thành công. Đó cũng là tín hiệu chính cho bất kỳ vấn đề xác thực nào mà chúng tôi gặp phải khi giao tiếp với dịch vụ của chúng tôi.

Các trường sau đây sẽ được thu thập:

  - **Abort -** Máy chủ đã tắt trong cuộc gọi dịch vụ hay chưa

  - **AllowPrompt -** Lời nhắc xác thực đã được cho phép hay chưa

  - **AuthScheme -** Lược đồ xác thực được yêu cầu bởi Exchange

  - **BackEndHttpStatus -** Mã http được báo cáo khi giao tiếp với thiết bị phụ trợ Exchange -

  - **BackupUrl -** URL Exchange thứ cấp để gọi đến

  - **BEServer -** Tên máy chủ thiết bị phụ trợ Exchange

  - **CalculatedBETarget -** Tên đầy đủ của máy phụ trợ Exchange

  - **Call(n)\_TokenAuthError -** Lỗi xác thực của lần thử dịch vụ thứ n

  - **Call(n)\_TokenIsValid -** Mã thông báo xác thực của lần thử dịch vụ thứ n có hợp lệ hay không

  - **CallMethod -** Chuỗi chỉ ra đường dẫn mà mã đã đi

  - **ConfigSvcReady -** Dịch vụ cấu hình đã được khởi tạo hay chưa

  - **Date -** Giá trị được trả về bởi máy chủ Exchange

  - **DiagInfo -** Thông tin do máy chủ Exchange trả về

  - **End\_TicketAuthError -** Bất kỳ lỗi nào trong khi nhận vé xác thực sau khi cuộc gọi dịch vụ

  - **End\_TokenIsValid -** Vé xác thực có hợp lệ sau khi cuộc gọi dịch vụ hay không

  - **EndingIdentityState -** Đối tượng nhận dạng báo cáo trạng thái sau khi thực hiện các cuộc gọi dịch vụ

  - **EwsHandler -** Giá trị được trả về từ Exchange

  - **FEServer -** Frontend Exchange phục vụ yêu cầu

  - **HResult -** Mã kết quả

  - **HttpStatus -** Mã trạng thái http được trả về từ Exchange

  - **IsSupportedAuthResponse -** Loại xác thực có phải là loại chúng tôi có thể sử dụng hay không

  - **LastUpdateValueRegistry -** Giá trị hàm băm được truy xuất từ sổ đăng ký

  - **LastUpdateValueRetrieved -** Giá trị hàm băm được trả về từ cuộc gọi dịch vụ

  - **MSDiagnostics -** Giá trị được trả về từ Exchange

  - **MsoHttpResult -** Giá trị bộ liệt kê được trả về từ API http

  - **NeedRefresh –-** Đây là trường đúng hay sai cho biết liệu dữ liệu phần bổ trợ đã cũ hay chưa và chúng tôi cần cập nhật nó.

  - **PrimaryUrl -** URL chính để thực hiện cuộc gọi dịch vụ tới

  - **RequestId -** Giá trị được trả về từ Exchange

  - **RequestTryCount -** Số lần chúng tôi đã cố gắng thực hiện cuộc gọi dịch vụ

  - **RequestTryCount -** Số lần chúng tôi cố gắng giao tiếp với Exchange

  - **ResultChain -** Chuỗi mã kết quả từ mỗi lần thử cuộc gọi dịch vụ

  - **StartingIdentityState -** Đối tượng nhận dạng báo cáo trạng thái trước khi thực hiện các cuộc gọi dịch vụ

  - **TelemetryId -** GUID đại diện cho một người dùng duy nhất cho dù chúng tôi cần thực hiện các cuộc gọi dịch vụ khác

#### <a name="officeextensibilitycatalogexchangegetmanifests"></a>Office.Extensibility.Catalog.ExchangeGetManifests

Dữ liệu liên quan đến thành công khi không truy xuất dữ liệu bản kê phần bổ trợ cho người quản trị viên đối tượng thuê Office 365 gán phần bổ trợ. Được sử dụng cho các số liệu về trạng thái, biểu đồ và phân tích các vấn đề của khách hàng.

Các trường sau đây sẽ được thu thập:

  - **CachedManifestsParsed** – Số lượng bản kê được tìm thấy trong bộ đệm ẩn

  - **IsAllReturnedManifestsParsed** – Tất cả các bản kê được trả lại có thể được phân tích hay không

  - **ManifestsRequested** – Số lượng bản kê cần thiết

  - **ManifestsReturned** – Số lượng bản kê được trả về từ máy chủ

  - **ManifestsToRetrieve** – Số lượng bản kê nhận được từ máy chủ

  - **ReturnedManifestsParsed** – Số lượng bản kê được trả về từ máy chủ được phân tích thành công

  - **TelemetryId -** GUID đại diện cho một người dùng duy nhất

#### <a name="officeextensibilityuxfensureloadosfdll"></a>Office.Extensibility.UX.FEnsureLoadOsfDLL 

Theo dõi lỗi tải Osf.DLL. Phát hiện lỗi tải DLL ngăn tính năng chạy.

Các trường sau đây sẽ được thu thập:

  - Không có

#### <a name="officeextensibilityuxfensureloadosfuidll"></a>Office.Extensibility.UX.FEnsureLoadOsfUIDLL 

Theo dõi lỗi tải OsfUI.DLL. Phát hiện lỗi tải DLL ngăn tính năng chạy.

Các trường sau đây sẽ được thu thập:

  - Không có

#### <a name="officeextensibilityuxfensureosfshareddllload"></a>Office.Extensibility.UX.FEnsureOsfSharedDLLLoad 

Theo dõi lỗi tải OsfShared.DLL. Phát hiện lỗi tải DLL ngăn tính năng chạy.

Các trường sau đây sẽ được thu thập:

  - Không có

#### <a name="officeextensibilityvbatelemetrycomobjectinstantiated"></a>Office.Extensibility.VBATelemetryComObjectInstantiated

Thu thập thông tin về việc gọi máy chủ tự động hoặc máy khách trong các giải pháp VBA. Được sử dụng để hiểu về sự tương tác giữa VBA và Com Object.

Các trường sau đây sẽ được thu thập:

  - **ComObjectInstantiatedCount** – Số lần tạo đối tượng COM

  - **HashComObjectInstantiatedClsid** – Hàm băm của mã định danh lớp đối tượng COM

  - **HashProjectName** – Hàm băm của tên dự án VBA

  - **TagId** – Thẻ duy nhất

#### <a name="officeextensibilityvbatelemetrydeclare"></a>Office.Extensibility.VBATelemetryDeclare 

Thu thập thông tin về việc gọi API Win32 hoặc giải pháp VBA. Được sử dụng để hiểu sự tương tác giữa VBA và việc sử dụng và để bổ sung cho các cuộc điều tra bảo mật.

Các trường sau đây sẽ được thu thập:

  - **DeclareCount** – Số của các khai báo

  - **HashDeclare** – Hàm băm của tên DLL

  - **HashEntryPoint** – Hàm băm của tên API

  - **HashProjectName** – Hàm băm của tên dự án VBA

  - **IsPtrSafe** – Câu lệnh khai báo có tương thích với kiến trúc khác hay không

  - **TagId** – Thẻ duy nhất

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a>Office.Outlook.Desktop.Add-ins.Add-inLoaded

Thu thập mức độ thành công và thất bại của việc tải Outlook của một phần bổ trợ. Dữ liệu này được theo dõi tích cực để đảm bảo Outlook hoạt động chính xác với các phần bổ trợ của khách hàng. Dữ liệu này được sử dụng để phát hiện và điều tra sự cố.

Các trường sau đây sẽ được thu thập:

  - **Hoạt động HVA tiêu chuẩn không có tải tùy chỉnh**

#### <a name="officeprogrammabilityadd-insinternalsetconnectenterprise"></a>Office.Programmability.Add-ins.InternalSetConnectEnterprise

Sự kiện được tạo ra khi phần bổ trợ COM được tải trên thiết bị doanh nghiệp. Phân tích trên máy tính:\# của tải được sử dụng làm mẫu số để tính toán trạng thái (sự cố \#/tải \#) để tính toán các chỉ số trạng thái cho các vòng thử nghiệm và sản xuất trong các kịch bản doanh nghiệp. Điều này đòi hỏi dữ liệu phải chính xác, không được lấy mẫu vì số lượng thiết bị nhỏ hơn (100-1K).

Các trường sau đây sẽ được thu thập:

  - **Add-inconnectFlag** – Hành vi tải hiện tại

  - **Add-inDescription** – Mô tả phần bổ trợ

  - **Add-inFileName** – Tên tệp phần bổ trợ không bao gồm đường dẫn tệp

  - **Add-inFriendlyName** – Tên thân thiện của phần bổ trợ

  - **Add-inId** – ID lớp phần bổ trợ

  - **Add-inProgId** – ID tiến trình phần bổ trợ

  - **Add-inProvider** – Nhà cung cấp phần bổ trợ

  - **Add-inTimeDateStamp** – Dấu thời gian phần bổ trợ từ siêu dữ liệu DLL

  - **Add-inVersion** – Phiên bản phần bổ trợ

#### <a name="officevisiovisioaddonload"></a>Office.Visio.Visio.AddonLoad

Ghi lại lỗi khi một giải pháp không tải. Cần thiết để gỡ lỗi lỗi tải phần bổ trợ trong Visio.

Các trường sau đây sẽ được thu thập:

  - **Data\_Load1Error:integer** - Giá trị lỗi trong quá trình tải phần bổ trợ Visio

#### <a name="officevisiovisioaddonusage"></a>Office.Visio.Visio.AddonUsage

Ghi lại lỗi khi không có lỗi trong chức năng giải pháp. Cần thiết để gỡ lỗi lỗi phần bổ trợ trong các phần bổ trợ.

Các trường sau đây sẽ được thu thập:

  - **Data\_DocumentSessionLogID:string** - Mã định danh phiên tài liệu

  - **Data\_IsEnabled**:**bool** - True nếu giải pháp được bật

  - **Data\_TemplateID:string** - GUID của mẫu mà trong đó giải pháp được tải. Được ghi nhật ký dưới dạng 0 cho giải pháp tùy chỉnh

  - **Data\_AddOnID**:**string** - GUID để xác định phần bổ trợ được tải

  - **Data\_Error**:**integer** - ID lỗi

### <a name="security-subtype"></a>*Loại con của bảo mật*

Tài liệu, tính năng và các điều kiện lỗi phần bổ trợ có thể ảnh hưởng đến bảo mật, bao gồm tính sẵn sàng cập nhật sản phẩm.

#### <a name="officesecurityactivationfilterclsidactivated"></a>Office.Security.ActivationFilter.CLSIDActivated

Theo dõi khi Mã định danh lớp cụ thể (Flash, Silverlight, v.v.) được kích hoạt trong Office. Được sử dụng để theo dõi tác động của việc chặn các điều khiển Flash, Silverlight và Shockwave đối với người dùng cuối.

Các trường sau đây sẽ được thu thập:

  - **ActivationType** - Loại kích hoạt đối với điều khiển

  - **Blocked** - là điều khiển bị chặn bởi Office

  - **CLSID** - Mã định danh lớp của điều khiển

  - **Count** - Số lần điều khiển được kích hoạt

#### <a name="officesecurityactivationfilterfailedtoregister"></a>Office.Security.ActivationFilter.FailedToRegister

Theo dõi điều kiện lỗi trong giảm thiểu bảo mật, chặn kích hoạt các điều khiển nguy hiểm trong Office.

Được sử dụng để chẩn đoán các điều kiện lỗi trong giảm thiểu bảo mật có thể ảnh hưởng đến bảo mật của người dùng cuối.

Các trường sau đây sẽ được thu thập:

  - Không có

#### <a name="officesecuritycomsecurityfileextensionlistfromservice"></a>Office.Security.ComSecurity.FileExtensionListFromService

Theo dõi nếu phần mở rộng khối bộ đóng gói được đọc từ dịch vụ cấu hình hoặc chúng tôi đã sử dụng danh sách mặc định của máy khách. Được sử dụng để đảm bảo hiệu quả giảm thiểu bảo mật bảo vệ người dùng cuối của Office.

Các trường sau đây sẽ được thu thập:

  - **RetrievedFromServiceStatus** - Chúng tôi có thể truy xuất danh sách các phần mở rộng tệp để chặn hay không nếu không thì lý do lỗi là gì

#### <a name="officesecuritycomsecurityload"></a>Office.Security.ComSecurity.Load

Theo dõi khi một đối tượng OLE được tải trong một tài liệu. Được sử dụng để đảm bảo hiệu quả giảm thiểu bảo mật bảo vệ người dùng cuối của Office.

Các trường sau đây sẽ được thu thập:

  - **Clsid** - Mã định danh lớp của điều khiển OLE

  - **Count** - Số lần điều khiển OLE được tải

  - **DocUrlHash** - Hàm băm đại diện cho tài liệu duy nhất. (Lưu ý - không có cách nào để tìm hiểu chi tiết thực tế của tài liệu này. Đó chỉ là một bản trình bày duy nhất của tài liệu.)

  - **IsCategorized** – Điều khiển OLE có được phân loại để tải trong Office hay không

  - **IsInsertable** – Điều khiển OLE có thể được chèn hay không

#### <a name="officesecuritycomsecurityobjdetected"></a>Office.Security.ComSecurity.ObjDetected

Theo dõi khi một đối tượng OLE được phát hiện trong một tài liệu. Được sử dụng để đảm bảo hiệu quả giảm thiểu bảo mật bảo vệ người dùng cuối của Office.

Các trường sau đây sẽ được thu thập:

  - **Clsid** - Mã định danh lớp của điều khiển OLE

  - **Count** - Số lần đối tượng OLE được phát hiện

  - **DocUrlHash** - Hàm băm đại diện cho tài liệu duy nhất. (Lưu ý - không có cách nào để tìm hiểu chi tiết thực tế của tài liệu này. Đó chỉ là một bản trình bày duy nhất của tài liệu.)

  - **IsCategorized** – Điều khiển OLE có được phân loại để tải trong Office hay không

  - **IsInsertable** – Điều khiển OLE có thể được chèn hay không

#### <a name="officesecuritycomsecuritypackageractivation"></a>Office.Security.ComSecurity.PackagerActivation

Theo dõi kết quả của giảm thiểu bảo mật, chặn các tiện ích mở rộng nguy hiểm được nhúng trong tài liệu Office. Được sử dụng để đảm bảo hiệu quả giảm thiểu bảo mật bảo vệ người dùng cuối của Office.

Các trường sau đây sẽ được thu thập:

  - **FromInternet** - Có phải là tài liệu từ Internet hay không

  - **PackagerSetting** - Thiết đặt bộ đóng gói hiện tại là gì

  - **TrustedDocument** - Tài liệu có phải là một tài liệu đáng tin cậy hay không

#### <a name="officesecuritycomsecuritypackageractivationerrors"></a>Office.Security.ComSecurity.PackagerActivationErrors

Theo dõi lỗi của giảm thiểu bảo mật, chặn các tiện ích mở rộng nguy hiểm được nhúng trong tài liệu Office. Được sử dụng để đảm bảo hiệu quả giảm thiểu bảo mật bảo vệ người dùng cuối của Office.

Các trường sau đây sẽ được thu thập:

  - **Error** - Mã lỗi

  - **Extension** - Phần mở rộng tập tin là gì

  - **FromInternet** - Có phải là tài liệu từ Internet hay không

  - **LinkedDocument** - Đó có phải là tài liệu được liên kết hay không

  - **PackagerSetting** - Thiết đặt bộ đóng gói hiện tại là gì

  - **TrustedDocument** - Tài liệu có đáng tin cậy hay không


#### <a name="officesecuritymacrointernetvbablockenabled"></a>Office.Security.Macro.InternetVBABlockEnabled

Theo dõi dù Macro khối từ cài đặt Internet có được bật trong máy khách hay không. Đánh giá việc sử dụng giảm thiểu bảo mật để bảo vệ chống lại các macro độc hại.

Các trường sau đây sẽ được thu thập:

  - Không có

#### <a name="officesecuritymacropolicydigsigtrustedpublishers"></a>Office.Security.Macro.PolicyDigSigTrustedPublishers

Theo dõi xem macro có được xác minh là từ một người phát hành đáng tin cậy hay không. Được sử dụng để đảm bảo hiệu quả giảm thiểu bảo mật bảo vệ người dùng cuối của Office.

Các trường sau đây sẽ được thu thập:

  - **Policy** - Đó có phải là bộ chính sách hay không là bộ chính sách hoặc không có sẵn

#### <a name="officesecuritymacroprompted"></a>Office.Security.Macro.Prompted

Theo dõi khi người dùng được nhắc bật Macro VBA. Được sử dụng để đánh giá mức độ phổ biến của Macro VBA và thúc đẩy các giảm thiểu bảo mật trong tương lai nhằm hạn chế thực thi macro để đối phó với các sự cố bảo mật.

Các trường sau đây sẽ được thu thập:

  - **PromptType** - Loại lời nhắc được hiển thị

  - **VBAMacroAntiVirusHash** - Hàm băm diệt vi-rút của macro

  - **VBAMacroAntiVirusHRESULT** - Kết quả của việc đánh giá chống vi-rút

#### <a name="officesecuritymacrovbasecureruntimesessionenablestate"></a>Office.Security.Macro.VBASecureRuntimeSessionEnableState

Theo dõi từng xác minh thời gian chạy AMSI được thực hiện khi macro thực hiện. Theo dõi hiệu quả của xác minh thời gian chạy AMSI của việc thực hiện Macro và xác định các lỗi có thể ảnh hưởng đến bảo mật của người dùng cuối.

Các trường sau đây sẽ được thu thập:

  - **IsRegistry** - Người quản trị có thiết lập một số ghi đè trong sổ đăng ký hay không

  - **State** - Trạng thái cho thời gian chạy an toàn

#### <a name="officesecuritymacroxl4prompted"></a>Office.Security.Macro.XL4Prompted

Theo dõi khi người dùng được nhắc bật Macro XL4. Được sử dụng để đánh giá mức độ phổ biến của Macro XL4 trong Excel để thúc đẩy các giảm thiểu bảo mật trong tương lai chặn XL4 theo mặc định để đối phó với các sự cố bảo mật liên quan đến việc lạm dụng macro XL4.

Các trường sau đây sẽ được thu thập:

  - **PromptType** - Loại lời nhắc được hiển thị


#### <a name="officesecurityocxufiprompt"></a>Office.Security.OCX.UFIPrompt

Theo dõi khi lời nhắc bảo mật được hiển thị cho người dùng khi tải điều khiển ActiveX được đánh dấu là không an toàn cho việc khởi tạo. Được sử dụng để theo dõi mức độ phổ biến của các điều khiển ActiveX UFI trong tài liệu Office để thúc đẩy sự giảm thiểu (ví dụ: điều khiển tiêu diệt) để đối phó với các sự cố bảo mật.

Các trường sau đây sẽ được thu thập:

  - **IsFromInternet** - Tài liệu có được mở từ Internet hay không

  - **IsSecureReaderMode** - Tài liệu có được mở trong Trình đọc an toàn hay không

  - **OcxTrustCenterSettings** - Cài đặt ActiveX hiện tại là gì


#### <a name="officesecuritysecurereaderhostopeninosr"></a>Office.Security.SecureReaderHost.OpenInOSR

Theo dõi hoàn thành thao tác mở trong Dạng xem được bảo vệ. Được sử dụng để chẩn đoán các điều kiện dẫn đến lỗi khi mở tệp trong Dạng xem được bảo vệ ảnh hưởng đến bảo mật và năng suất của khách hàng.

Các trường sau đây sẽ được thu thập:

  - Không có

## <a name="product-and-service-usage-data-events"></a>Sự kiện dữ liệu sử dụng sản phẩm và dịch vụ

Sau đây là những loại dữ liệu con trong danh mục này:

- [Mức độ thành công của tính năng ứng dụng ](#application-feature-success-subtype)
- [Trạng thái ứng dụng và khởi động](#application-status-and-boot-subtype)
- [Cấu hình khả năng truy nhập Office](#office-accessibility-configuration-subtype)


### <a name="application-feature-success-subtype"></a>*Loại con mức độ thành công của tính năng ứng dụng *

Thành công của chức năng ứng dụng. Giới hạn mở và đóng ứng dụng và tài liệu, chỉnh sửa tệp và chia sẻ tệp (cộng tác).

#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Chỉ được thu thập khi người dùng cuối đã kích hoạt Bảng điều khiển đo từ xa cho Office.Nó thu thập thông tin về thời điểm Tác nhân đo từ xa cho Office được thực hiện.Điều này chỉ được thu thập khi Bảng điều khiển đo từ xa cho Office được bật và được sử dụng để xác định trạng thái của Tác nhân đo từ xa cho Office.

Các trường sau đây sẽ được thu thập:

  - **Data.AgentExit** - Dấu thời gian khi Tác nhân đo từ xa thoát thành công

  - **Data.AgentScan** - Dấu thời gian khi Tác nhân đo từ xa hoàn thành việc quét thành công

  - **Data.AgentUpload** - Dấu thời gian khi Tác nhân đo từ xa hoàn thành việc tải lên thành công

#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Chỉ được thu thập khi Bảng điều khiển đo từ xa cho Office đã được bật bởi người dùng cuối (rất có thể là người quản trị). Nó thu thập sự xuất hiện của các sự cố liên quan đến phần bổ trợ Office và tài liệu.Điều này chỉ được thu thập khi người dùng đã kích hoạt Bảng điều khiển đo từ xa cho Office và được sử dụng để xác định xem có sự xuất hiện gia tăng của sự cố liên quan đến phần bổ trợ hoặc tài liệu hay không.

Các trường sau đây sẽ được thu thập:

  - **Data.CollectionTime** - Dấu thời gian khi sự kiện sự cố được ghi lại

#### <a name="officeconnectdeviceactivitystart"></a>Office.ConnectDevice.Activity.Start

Cho phép chúng tôi biết xem việc kết nối với thiết bị hoặc ứng dụng đã thành công hay chưa.  Sử dụng để giám sát và biết về trạng thái tính năng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Datasource_Type** - Sê-ri của thiết bị hoặc thông tin Dịch vụ ứng dụng

- **DataSource_Name** - Tên của nguồn dữ liệu được kết nối

- **Activity_Name** = Tên của hoạt động “ConnectDevice”

- **Activity_CV** = ID để kết hợp các sự kiện trong phiên kết nối

- **Activity_StartStopType** = Bắt đầu

- **Activity_DateTimeTicks** = Dữ liệu về thời gian cho hoạt động
 
#### <a name="officeconnectdeviceactivitystop"></a>Office.ConnectDevice.Activity.Stop

Cho phép chúng tôi biết xem việc kết nối với thiết bị hoặc ứng dụng đã thành công hay chưa. Được sử dụng để giám sát và biết về trạng thái tính năng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Datasource_Type** - Sê-ri của thiết bị hoặc thông tin Dịch vụ ứng dụng

- **DataSource_Name** - Tên của nguồn dữ liệu được kết nối

- **Activity_Name** = Tên của hoạt động “ConnectDevice”

- **Activity_CV** = ID để kết hợp các sự kiện trong phiên kết nối

- **Activity_StartStopType** - Stop

- **Activity_DateTimeTicks** = Dữ liệu về thời gian cho hoạt động

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Dữ liệu liên quan đến việc xử lý quyền riêng lẻ và người quản trị đối tượng thuê Office 365 được gán phần bổ trợ.

Được sử dụng trong biểu đồ (được yêu cầu bởi quản lý nhóm) về thành công của khách hàng và phân tích các vấn đề của khách hàng.

Các trường sau đây sẽ được thu thập:

  - **AppVersion** – Phiên bản của ứng dụng máy chủ phần bổ trợ

  - **SolutionId** GUID đại diện cho phần bổ trợ duy nhất

  - **TelemetryId -** GUID đại diện cho một người dùng duy nhất

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

Cho phép chúng tôi biết nếu một tệp đã được mở thành công từ Lớp FIO. Sử dụng để giám sát và biết về trạng thái tính năng.

Các trường sau đây sẽ được thu thập:

  - **Activity.Group -** Thẻ cho phép một nhóm các sự kiện giám sát được nhóm lại để quản lý thành công tổng thể

  - **Activity.IsHVA -** Cờ cho biết rằng sự kiện là yếu tố rất quan trọng đối với thành công của người dùng

  - **Data.AsyncOpen -** Cờ cho biết rằng tài liệu đã được mở với nội dung đến sau khi phần chính được mở

  - **Data.CacheFileId -** Kết nối với phép đo từ xa Office Document Cache để cho phép phân tích tác động của các sự cố về bộ nhớ ẩn đối với trải nghiệm người dùng

  - **Data.CoauthStatus -** Báo cáo trạng thái hợp tác của tài liệu đang Mở

  - **Data.CountOfMultiRoundTripsDownload -** Số lượng trọn vòng đến máy chủ được sử dụng để khắc phục sự cố về hiệu suất và mạng

  - **Data.CountOfMultiRoundTripsUpload -** Số lượng trọn vòng đến máy chủ được sử dụng để khắc phục sự cố về hiệu suất và mạng

  - **Data.DialogId -** Cài đặt nếu hộp thoại giao diện người dùng được hiển thị trong khi Mở, cho biết thông báo cảnh báo đã được hiển thị cho người dùng

  - **Data.DidFallbackToDAV -** Đặt nếu tài liệu được mở bằng giao thức truyền tệp cũ hơn

  - **Data.Doc.AccessMode -** Tài liệu ở chế độ chỉ đọc

  - **Data.Doc.AssistedReadingReasons -** Thiết đặt nếu tài liệu có bảo vệ dữ liệu điện tử tại chỗ

  - **Data.Doc.ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data.Doc.EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data.Doc.Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data.Doc.Extension -** Đã lỗi thời

  - **Data.Doc.FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data.Doc.Fqdn -** Tên miền của OneDrive hoặc SharePoint Online

  - **Data.Doc.FqdnHash -** Hàm băm một chiều của tên miền có thể nhận dạng khách hàng

  - **Data.Doc.IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data.Doc.IdentityUniqueId -** Đã lỗi thời

  - **Data.Doc.InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data.Doc.IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu

  - **Data.Doc.IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data.Doc.IsCloudCollabEnabled -** Cờ cho biết dịch vụ hỗ trợ Cộng tác đám mây

  - **Data.Doc.IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data.Doc.IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data.Doc.IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data.Doc.IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data.Doc.Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data.Doc.LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data.Doc.NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data.Doc.PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data.Doc.ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data.Doc.ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data.Doc.ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data.Doc.ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data.Doc.ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data.Doc.ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data.Doc.SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data.Doc.SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data.Doc.SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data.Doc.SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data.Doc.StorageProviderId -** Đã lỗi thời

  - **Data.Doc.StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data.Doc.SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data.Doc.UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data.Doc.UsedWrsDataOnOpen -** Chỉ báo chẩn đoán cho tài liệu luỹ kế đang mở

  - **Data.Doc.WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data.DocumentLoadEndpoint -** Bản sao đã lỗi thời/dư thừa của (Data.Doc.Location và Data.Doc.IsSyncbacked)

  - **Data.DocumentSizeInBytes -** Đã lỗi thời/dư thừa được thay thế bằng Data.Doc. SizeInBytes

  - **Data.DocumentSizeOnDisk -** Đã lỗi thời

  - **Data.DoesBaseHaveContentOnOpen -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.DownloadFragmentSize -** Kích thước của dữ liệu được gửi trong yêu cầu phụ để chẩn đoán sự cố mạng

  - **Data.DsmcStartedTooEarly -** Cho biết lỗi bắt đầu phiên chỉnh sửa hợp tác

  - **Data.EditorsCount -** Số lượng cộng tác viên khác đang chỉnh sửa tài liệu

  - **Data.ExcludedDataThresholdInBytes -** Kích cỡ tệp cần thiết cho Async mở được sử dụng

  - **Data.FileIOResult.Code -** Bộ đệm ẩn của mã trả về Mở cuối cùng từ lớp giao thức

  - **Data.FileIOResult.Success -** Bộ đệm ẩn của chỉ báo thành công Mở cuối cùng từ lớp giao thức

  - **Data.FileIOResult.Tag -** Bộ đệm ẩn của thẻ lỗi Mở cuối cùng từ lớp giao thức

  - **Data.FileIOResult.Type -** Bộ đệm ẩn của loại lỗi Mở cuối cùng từ lớp giao thức

  - **Data.FqdnHash -** Đã lỗi thời, được thay thế bằng Data\_Doc\_FqdnHash

  - **Data.FullIError -** Bộ đệm ẩn của tất cả mã lỗi Mở từ lớp giao thức

  - **Data.FullyQualifiedDomainName -** Đã lỗi thời, được thay thế bằng Data\_Doc\_Fqdn

  - **Data.Input.FileOpenState -** Trạng thái được yêu cầu bởi ứng dụng (Đọc/ĐọcGhi, v.v..) **-**

  - **Data.Input.OpenAsync -** Mở không đồng bộ theo yêu cầu của ứng dụng

  - **Data.Input.OpenOfflineCopy -** Mở từ bản sao ngoại tuyến được yêu cầu bởi thao tác thêm

  - **Data.IOFlags -** - Đã lỗi thời

  - **Data.IsBaseBranchEmptyOnOpen -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.IsCachedHistoricalVersion -** Bộ nhớ ẩn chứa phiên bản cũ hơn của tài liệu

  - **Data.IsDocEnterpriseProtected -** Tài liệu đã được bảo vệ bằng mã hóa (Bảo vệ Tài liệu Điện tử/EDP)

  - **Data.IsDocInODC -** Tài liệu đã được mở trước đó và đã có trong bộ đệm ẩn

  - **Data.IsMapUnMapCase -** Một phần trạng thái của tệp được lưu trữ

  - **Data.IsMapUnMapCase.End -** Một phần trạng thái của tệp được lưu trữ

  - **Data.IsOfficeHydrationInProgress -** Tài liệu đang được Windows khôi phục từ bộ nhớ ngoại tuyến

  - **Data.isOfficeHydrationRequired -** Tài liệu hiện đang được lưu trữ ngoại tuyến

  - **Data.isOpenFromCollab -** Bản sao mới nhất của tài liệu đã được truy xuất từ dịch vụ cộng tác dùng chung

  - **Data.isPendingNameExist -** Đang thực hiện đổi tên tài liệu

  - **Data.IsStubFile -** Tài liệu này chưa được lưu vào dịch vụ đám mây

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen -** Trạng thái tài liệu đã thay đổi, những thay đổi có thể đã đến trong khi tài liệu không được mở

  - **Data.isTaskCanceledAfterOpenComplete -** Đã lỗi thời

  - **Data.IsWorkingBranchAvailableOnOpen -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.LicenseStatus** - Trạng thái giấy phép sản phẩm chẩn đoán được sử dụng để xác thực rằng các tính năng sản phẩm phù hợp được bật cho loại giấy phép người dùng 

  - **Data.LicenseType -** Cho biết trạng thái của giấy phép (miễn phí/trả tiền/dùng thử, v.v.)

  - **Data.Location -** Cho biết loại/vị trí của phương tiện lưu trữ (USB; Đám mây, v.v.)

  - **Data.LockRequestDocMode -** Cho biết tài liệu có sẵn dùng cho những người khác hay không

  - **Data.MyDeferredValue -** Đã lỗi thời

  - **Data.Network.BytesReceived -** Đã lỗi thời

  - **Data.Network.BytesSent -** Đã lỗi thời

  - **Data.Network.ConnectionsCreated -** Đã lỗi thời

  - **Data.Network.ConnectionsEnded -** Đã lỗi thời

  - **Data.OcsDisableReasons -** Lý do tại sao dịch vụ cộng tác dùng chung không sẵn dùng cho tài liệu

  - **Data.OcsHostOnOpen -** Cờ cho biết rằng điều khiển sẽ chuyển sang dịch vụ cộng tác dùng chung trong khi Mở

  - **Data.OpeningOfflineCopy -** Cờ cho biết rằng bản sao cục bộ của tài liệu sẽ được mở

  - **Data.Partition -** Đã lỗi thời

  - **Data.RequestTime -** Đã lỗi thời

  - **Data.ResourceIdHash -** Đã lỗi thời

  - **Data.ResumedIncrementalOpen -** Đã lỗi thời

  - **Data.RTCEnabled -** Giao thức phân phối thay đổi nhanh đã bắt đầu

  - **Data.SaveOnOpen -** Những thay đổi chưa được lưu trong tài liệu cục bộ đã được lưu vào dịch vụ trong khi Mở

  - **Data.ServerProtocol -** Đã lỗi thời, được thay thế bằng Data\_Doc\_ServerProtocol

  - **Data.ServerType -** Đã lỗi thời, được thay thế bằng Data\_Doc\_ServerType

  - **Data.ServerVersion -** Đã lỗi thời, được thay thế bằng Data\_Doc\_ServerVersion

  - **Data.ServiceId -** Đã lỗi thời, được thay thế bằng Data\_Doc\_WopiServiceId

  - **Data.SessionId -** Đã lỗi thời

  - **Data.ShouldSwitchToServerOnly -** Bản sao cục bộ của tài liệu không thể được sử dụng và phải sử dụng phiên bản máy chủ

  - **Data.SpecialChars -** Đã lỗi thời

  - **Data.StopwatchDuration -** Đã lỗi thời

  - **Data.SyncBackedFileTelemetrySessionId -** Obsolete

  - **Data.SyncElapsedTime -** Đã lỗi thời

  - **Data.SyncRequestId -** Đã lỗi thời

  - **Data.TestProperty -** Đã lỗi thời

  - **Data.TransitionToHostOnOpen -** Cờ cho biết phiên sẽ kết nối với dịch vụ lưu trữ tài liệu

  - **Data.TransitionToHostOnOpenResult -** Trạng thái chuyển đổi sang dịch vụ máy chủ

  - **Data.UseCachedNetworkConnection -** Cờ cho biết liệu một kết nối đã được sử dụng lại hay một kết nối mới đã được tạo

  - **Data.UseClientIdAsSchemaLockId -** Cờ để kiểm soát cách tài liệu bị khóa trong dịch vụ

  - **Data.WopiServiceId -** Đã lỗi thời, được thay thế bằng Data\_Doc\_WopiServiceId

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a>Office.FileIO.CSI.CCachedFileCsiSaveFileBasic

Cho phép chúng tôi biết nếu một tệp đã được lưu thành công từ Lớp FIO. Sử dụng để giám sát và biết về trạng thái tính năng.

Các trường sau đây sẽ được thu thập:

  - **Activity.Group -** Thẻ cho phép một nhóm các sự kiện giám sát được nhóm lại để quản lý thành công tổng thể

  - **Activity.IsHVA -** Cờ cho biết rằng sự kiện là yếu tố rất quan trọng đối với thành công của người dùng

  - **Data.AsyncOpen -** Cờ cho biết rằng tài liệu đã được mở với nội dung đến sau khi phần chính được mở

  - **Data.BaseDownloadTriggered -** Thay đổi chẩn đoán theo dõi cho biết rằng phiên bản cơ sở của tài liệu đã được yêu cầu

  - **Data.BlockAutoUploadReasons -** Mã lý do cho trạng thái tải lên bị chặn (ví dụ: Lưu tự động bị tắt, tài liệu đang chuyển đổi)

  - **Data.BlockUploadDueToFailedSaveAsOverExisting -** Tải lên bị chặn vì nó sẽ thất bại nếu thử lại

  - **Data.CacheFileId -** Kết nối với phép đo từ xa Office Document Cache để cho phép phân tích tác động của các sự cố về bộ nhớ ẩn đối với trải nghiệm người dùng

  - **Data.ChartType -** Đã lỗi thời

  - **Data.CoAuthStatus -** Báo cáo trạng thái hợp tác của tài liệu đang Lưu

  - **Data.CoauthUpdatesContext -** Ngữ cảnh báo cáo (Phối/Mở luỹ kế)

  - **Data.CountOfMultiRoundTripsDownload -** Số lượng trọn vòng đến máy chủ được sử dụng để khắc phục sự cố về hiệu suất và mạng

  - **Data.CountOfMultiRoundTripsUpload -** Số lượng trọn vòng đến máy chủ được sử dụng để khắc phục sự cố về hiệu suất và mạng

  - **Data.DialogChoice -** Ghi lại lựa chọn được thực hiện trong bất kỳ hộp thoại lỗi nào

  - **Data.DialogId -** Ghi lại hộp thoại của bất kỳ hộp thoại lỗi nào hiển thị trong khi lưu

  - **Data.Dmc.IsOcsSupported -** Đã lỗi thời

  - **Data.Doc.AccessMode -** Tài liệu ở chế độ chỉ đọc

  - **Data.Doc.AssistedReadingReasons -** Thiết đặt nếu tài liệu có bảo vệ dữ liệu điện tử tại chỗ

  - **Data.Doc.ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data.Doc.EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data.Doc.Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data.Doc.Extension -** Đã lỗi thời

  - **Data.Doc.FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data.Doc.Fqdn -** Tên miền của OneDrive hoặc SharePoint Online

  - **Data.Doc.FqdnHash -** Hàm băm một chiều của tên miền có thể nhận dạng khách hàng

  - **Data.Doc.FqdnHasi -** Đã lỗi thời

  - **Data.Doc.IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện lưu

  - **Data.Doc.IdentityUniqueId -** Đã lỗi thời

  - **Data.Doc.IKFlags -** Đã lỗi thời

  - **Data.Doc.InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data.Doc.IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu

  - **Data.Doc.IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data.Doc.IsCloudCollabEnabled -** Cờ cho biết ứng dụng hỗ trợ Cộng tác đám mây

  - **Data.Doc.IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data.Doc.IsOcsSupported -** Cờ cho biết ứng dụng hỗ trợ Cộng tác đám mây

  - **Data.Doc.IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data.Doc.IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data.Doc.Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data.Doc.LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data.Doc.NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data.Doc.PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data.Doc.ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data.Doc.ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data.Doc.ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data.Doc.ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data.Doc.ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data.Doc.ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data.Doc.SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data.Doc.SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data.Doc.SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data.Doc.SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data.Doc.StorageProviderId -** Đã lỗi thời

  - **Data.Doc.StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data.Doc.SussionId -** Đã lỗi thời

  - **Data.Doc.SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data.Doc.UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data.Doc.UsedWrsDataOnOpen -** Chỉ báo chẩn đoán cho tài liệu luỹ kế đang mở

  - **Data.Doc.WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data.DocnReadOnlyReasons -** Đã lỗi thời

  - **Data.DocumentSaveEndpoint -** Đã lỗi thời, được thay thế bằng Data\_Doc\_Vị trí

  - **Data.DocumentSaveType -** Loại lưu (Thông thường, Tạo, Lưu dưới dạng)

  - **Data.DocumentSizeOnDisk -** Đã lỗi thời, được thay thế bằng Data\_Doc\_SizeInBytes

  - **Data.DoesBaseHaveContentOnOpen -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.DstDoc.AccessMode -** Tài liệu mới ở chế độ chỉ đọc/có thể chỉnh sửa

  - **Data.DstDoc.EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu mới

  - **Data.DstDoc.Extension -** Phần mở rộng tài liệu mới (docx/xlsm/pptx, v.v..)

  - **Data.DstDoc.FileFormat -** Giao thức định dạng tệp của tài liệu mới

  - **Data.Doc.Fqdn -** Tên miền của OneDrive hoặc SharePoint Online của tài liệu mới

  - **Data.DstDoc.FqdnHash -** Hàm băm một chiều của tên miền có thể nhận dạng khách hàng của tài liệu mới

  - **Data.DstDoc.IdentityUniqueId -** Đã lỗi thời

  - **Data.DstDoc.IOFlags -** Cờ tuỳ chọn được lưu vào bộ đệm ẩn của tài liệu mới được sử dụng khi mở

  - **Data.DstDoc.IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu mới đã được mở

  - **Data.DstDoc.IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data.DstDoc.Location -** Cho biết dịch vụ nào đã cung cấp tài liệu mới (OneDrive, File Server, SharePoint, v.v.)

  - **Data.DstDoc.NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa trên tài liệu mới

  - **Data.DstDoc.ReadOnlyReasons -** Lý do tại sao tài liệu mới được mở ở dạng chỉ đọc

  - **Data.DstDoc.ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố với tài liệu mới

  - **Data.DstDoc.ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố với tài liệu mới

  - **Data.DstDoc.ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ khi tạo tài liệu mới

  - **Data.DstDoc.ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..) cho tài liệu mới

  - **Data.DstDoc.ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ cho tài liệu mới

  - **Data.DstDoc.SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ cho tài liệu mới

  - **Data.DstDoc.SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online cho tài liệu mới

  - **Data.DstDoc.SizeInBytes -** Chỉ báo kích thước tài liệu cho tài liệu mới

  - **Data.DstDoc.UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc cho tài liệu đích cho tài liệu mới

  - **Data.EditorsCount -** Số lượng cộng tác viên khác đang chỉnh sửa tài liệu

  - **Data.FullIError -** Bộ đệm ẩn của tất cả mã lỗi từ lớp giao thức

  - **Data.HasFilteredCategories -** Đã lỗi thời

  - **Data.HasFilteredCategoryNames -** Đã lỗi thời

  - **Data.HasFilteredSeries -** Đã lỗi thời

  - **Data.HasFilteredSeriesNames -** Đã lỗi thời

  - **Data.HasPendingSaveAs -** Cho biết rằng một yêu cầu Lưu dưới dạng/Lưu bản sao đang được thực hiện

  - **Data.Input.FileOpenState -** Trạng thái được yêu cầu bởi ứng dụng (Đọc/ĐọcGhi, v.v..)

  - **Data.Input.FileSaveState -** Trạng thái yêu cầu bởi ứng dụng (Lưu khi mở, Lưu dưới dạng, v.v..)

  - **Data.Input.NetworkCost -** Cho biết chi phí/loại mạng (gói dữ liệu theo lưu lượng sử dụng, giới hạn trên của kết nối bằng gói dữ liệu theo lưu lượng sử dụng, v.v.)

  - **Data.Input.OpenAsync -** Cờ cho biết ứng dụng yêu cầu một thao tác mở không đồng bộ

  - **Data.Input.OpenOfflineCopy -** Cờ cho biết ứng dụng yêu cầu một thao tác mở ngoại tuyến

  - **Data.IsCachedHistoricalVersion -** Cho biết rằng tệp được lưu vào bộ đệm ẩn này không phải là phiên bản mới nhất

  - **Data.IsHtml -** Cho biết rằng văn bản định dạng HTML đã được dán

  - **Data.IsLegacyCode -** Cho biết văn bản định dạng mã kế thừa đã được dán

  - **Data.IsLocalOnlyFile -** Cho biết rằng tệp chỉ được mở từ bộ nhớ cục bộ

  - **Data.IsLocalOrSyncBackedFile -** Cho biết rằng tệp đã được mở cục bộ và ánh xạ tới dịch vụ

  - **Data.IsMapUnMapCase -** Một phần trạng thái của tệp được lưu trữ

  - **Data.isOpenFromCollab -** Cho biết rằng tệp đã được mở từ dịch vụ cộng tác dùng chung

  - **Data.IsStubFile -** Tài liệu này chưa được chia sẻ lên dịch vụ đám mây

  - **Data.IsSyncBackedFile -** Tài liệu nằm trong thư mục đồng bộ hóa tự động cập nhật

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen -** Trạng thái tài liệu đã thay đổi, những thay đổi có thể đã đến trong khi tài liệu không được mở

  - **Data.IsWorkingBranchAvailableOnOpen -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.Location -** Cho biết loại/vị trí của phương tiện lưu trữ (USB; Đám mây, v.v.)

  - **Data.LockRequestDocMode -** Cho biết tài liệu có sẵn dùng cho những người khác hay không

  - **Data.MruRequestResult -** Đã lỗi thời

  - **Data.NewDataNotAvailableReason -** Đã lỗi thời

  - **Data.OcsDisableReasons -** Không được sử dụng bằng cách lưu

  - **Data.OcsHostOnOpen -** Không được sử dụng bằng cách lưu

  - **Data.Output.FileSaveState -** Trạng thái hoàn thành việc lưu

  - **Data.PivotChart -** Đã lỗi thời

  - **Data.resolveConflictState -** Mã lý do cho yêu cầu giải quyết xung đột phối

  - **Data.RTCEnabled -** Giao thức phân phối thay đổi nhanh đã bắt đầu

  - **Data.SaveAsToCurrent -** Cho biết rằng tài liệu đang hoạt động sẽ ghi đè lên tệp được lưu trữ

  - **Data.ServiceId -** Đã lỗi thời, được thay thế bằng Data\_Doc\_WopiServiceId

  - **Data.SessionId -** Đã lỗi thời

  - **Data.SizeInBytes -** Đã lỗi thời, được thay thế bằng Data\_Doc\_SizeInBytes

  - **Data.StopwatchDuration -** Đã lỗi thời

  - **Data.SyncBackedFileRequiresOnlineTransition -** Cờ cho biết thao tác Lưu tạm thời bị chặn bởi quá trình chuyển đổi trực tuyến

  - **Data.SyncBackedFileSaveOnOpen -** Cờ cho biết các thay đổi được thực hiện bằng đồng bộ hóa tự động yêu cầu lưu lại khi mở

  - **Data.TelemetryId -** Đã lỗi thời

  - **Data.TriggerSaveAfterBaseDownload -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.UploadBlockedDueToCoherencyFailure -** Lưu vào dịch vụ bị chặn giải quyết người dùng đang chờ xử lý của các thay đổi xung đột

  - **Data.UploadBlockedDueToFailedSaveAsOverExisting -** Lưu vào dịch vụ bị chặn do không thể ghi đè tệp hiện có

  - **Data.UploadPreemptedForCoherency -** Lưu vào dịch vụ bị bỏ qua vì nhiều thay đổi đang được thực hiện bởi người dùng

  - **Data.UploadPreemptedForSaveAsOverExistingFailure -** Lưu vào dịch vụ bị hủy do lỗi SaveAsOverExisting trước đó

  - **Data.UploadScheduled -** Tệp đã sẵn sàng để được tải lên không đồng bộ vào dịch vụ

  - **Data.UseClientIdAsSchemaLockId -** Cờ để kiểm soát cách tài liệu bị khóa trong dịch vụ

  - **Data.WorkingCopySaved -** Thay đổi chẩn đoán theo dõi để đảm bảo chúng tôi có phiên bản mới nhất của tệp dùng chung

  - **Data.ZrtSaveAsforSyncBackedBusinessEnabled -** Cờ cho biết tính năng lưu nhanh đã được bật cho SharePoint Online

  - **Data.ZrtSaveAsforSyncBackedConsumerEnabled -** Cờ cho biết tính năng lưu nhanh đã được bật cho OneDrive dành cho Người tiêu dùng

  - **Data.ZrtSaveAsforSyncBackedCTBusinessEnabled -** Cờ cho biết các loại nội dung lưu nhanh đã được bật cho SharePoint Online

  - **Data.ZrtSaveAsforSyncBackedCTConsumerEnabled -** Cờ cho biết loại nội dung lưu nhanh đã được bật cho OneDrive Consumer

  - **Data.ZrtSaveAsforSyncBackedMetaDataBusinessEnabled -** Cờ cho biết lưu tệp nhanh siêu dữ liệu đã được bật cho SharePoint Online

  - **Data.ZrtSaveAsforSyncBackedMetaDataConsumerEnabled -** Cờ cho biết lưu tệp nhanh siêu dữ liệu đã được bật cho OneDrive dành cho Người tiêu dùng-

#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Thu thập khi ứng dụng không khởi động được do lỗi không mong muốn trong khi khởi động. Được sử dụng để theo dõi các trường hợp ngoại lệ và sự cố. Giúp theo dõi & gỡ lỗi trạng thái ứng dụng.

Các trường sau đây sẽ được thu thập:
- **DateTime** - Dấu thời gian của khi sự kiện được ghi nhật ký

- **EventName** - Tên sự kiện được ghi nhật ký


#### <a name="officemanageabilityclient-fetchpolicyprechecks"></a>Office.Manageability.Client Fetch.PolicyPreChecks

Phép đo từ xa quan trọng để theo dõi thành công\\thất bại cho chính sách đám mây tải xác thực kiểm tra trước. ExitReason chứa ánh xạ bộ liệt kê đến điều kiện kiểm tra trước không thành công.

Các trường sau đây sẽ được thu thập:

  - **Data.ExitReason** - Giá trị bộ liệt kê cho biết lý do thoát, nếu kiểm tra trước thất bại

  - **Data.Log** - Thông báo nhật ký tuỳ chỉnh cho biết sự thành công hay thất bại của việc kiểm tra trước

#### <a name="officemanageabilityclientfetchandapplypolicy"></a>Office.Manageability.Client.Fetch.AndApplyPolicy

Phép đo từ xa quan trọng để theo dõi thành công\\thất bại cho chính sách đám mây tải bắt đầu từ ứng dụng. Lý do thoát chứa ánh xạ bộ liệt kê đến lý do lỗi.

Các trường sau đây sẽ được thu thập:

  - **Data.ExitReason** - Giá trị bộ liệt kê cho biết lý do thoát, nếu kiểm tra trước thất bại

  - **Data.Log** - Thông báo nhật ký tuỳ chỉnh cho biết sự thành công hay thất bại của việc kiểm tra trước

#### <a name="officeoutlookdesktopaccountconfigurationcreateaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.CreateAccountResult

Kết quả của việc thêm tài khoản vào Outlook trong cấu hình mới, từ Office Backstage hoặc từ hộp thoại cài đặt tài khoản. Dữ liệu được theo dõi tích cực để đảm bảo chúng tôi không thấy bất kỳ đột biến nào trong các lần thất bại. Chúng tôi cũng phân tích dữ liệu để tìm khu vực cải thiện. Chúng tôi mong muốn cải thiện tỷ lệ thành công này với mỗi bản phát hành.

Các trường sau đây sẽ được thu thập:

  - **AccountCreationResult** – Kết quả (thành công, thất bại, hủy bỏ, v.v.) của việc thêm tài khoản vào Outlook.

  - **AccountCreationTime** – Thời gian cần để tạo tài khoản

  - **AccountInfoSource** - Nguồn thietes đặt tài khoản (ví dụ: AutoDiscover, GuessSmart, AutoDetect, v.v.)

  - **AccountType** – Loại tài khoản được cấu hình.

  - **HashedEmailAddress** – Địa chỉ email dạng băm

  - **ShowPasswordPageFlightEnabled** - Chỉ báo nếu việc chuyến bay ShowPopImapPasswordPage được bật

#### <a name="officeoutlookdesktopaccountconfigurationrepairaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.RepairAccountResult

Kết quả của việc sửa chữa một tài khoản hoặc thay đổi thiết đặt tài khoản nâng cao. Dữ liệu được theo dõi tích cực để đảm bảo chúng tôi không thấy bất kỳ đột biến nào trong các lần thất bại. Chúng tôi cũng phân tích dữ liệu để tìm khu vực cải thiện. Vì đây là một trải nghiệm mới (được tái cấu trúc), nên chúng tôi muốn đảm bảo rằng chúng tôi đã làm đúng.

Các trường sau đây sẽ được thu thập:

  - **AccountInfoSource** - Nguồn thông tin tài khoản cho tài khoản được sử dụng để tìm cách sửa chữa

  - **AccountType** - Loại tài khoản mà thao tác sửa chữa tài khoản đã được thử

  - **HashedEmailAddress** – Địa chỉ email dạng băm

  - **ManualRepairRequested** - Chỉ báo nếu sửa chữa thủ công được yêu cầu

  - **Result** - Kết quả của nỗ lực sửa chữa tài khoản. Ví dụ: "Thành công" hoặc "Không thành công\_SaveChangesToAccount"

#### <a name="officeoutlookdesktopaccountconfigurationupdatepasswordresult"></a>Office.Outlook.Desktop.AccountConfiguration.UpdatePasswordResult

Kết quả cập nhật mật khẩu của tài khoản từ danh sách thả xuống Thiết đặt tài khoản. Dữ liệu được theo dõi tích cực để đảm bảo chúng tôi không thấy bất kỳ đột biến nào trong các lần thất bại. Chúng tôi cũng phân tích dữ liệu để tìm khu vực cải thiện. Vì đây là một trải nghiệm mới (được tái cấu trúc), nên chúng tôi muốn đảm bảo rằng chúng tôi đã làm đúng.

Các trường sau đây sẽ được thu thập:

  - **AccountType** - Loại tài khoản mà thao tác cập nhật mật khẩu đã được thử

  - **HashedEmailAddress** – Địa chỉ email dạng băm

  - **Result** - Kết quả của nỗ lực cập nhật mật khẩu. Ví dụ: "Thành công" hoặc "Không thành công\_AllowLessSecureAppsDisabled"

#### <a name="officeoutlookdesktopprovidersloadproviderlibrary"></a>Office.Outlook.Desktop.Providers.LoadProviderLibrary

Sự kiện này theo dõi sự thành công hay thất bại của MAPI khi cố gắng tải DLL của nhà cung cấp (ví dụ: contab32.dll, emsmdb32.dll, một DLL được sử dụng bởi một phần bổ trợ). Thao tác MAPI chịu trách nhiệm cho tải DLL của nhà cung cấp là nền tảng cho thao tác Bắt buộc của Outlook cũng như khả năng mở rộng (thông qua phần bổ trợ hoặc nhà cung cấp Cửa hàng/Vận chuyển/Sổ địa chỉ tùy chỉnh). Chúng tôi tích cực giám sát kết quả thành không hay thất bại của thao tác này để đảm bảo rằng chức năng MAPI cốt lõi này tiếp tục hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **Hoạt động HVA tiêu chuẩn** không có tải tùy chỉnh

#### <a name="officeoutlookdesktopstorescreatenewstore"></a>Office.Outlook.Desktop.Stores.CreateNewStore

Thu thập kết quả của việc tạo một cửa hàng mới (với loại và phiên bản) cũng như mã kết quả. Chúng tôi tích cực giám sát sự kiện này để theo dõi trạng thái về khả năng đồng bộ hóa và lưu trữ thư cục bộ, lưu trữ thư (trong PST) hoặc sử dụng Nhóm của người dùng.

Các trường sau đây sẽ được thu thập:

  - **Hoạt động HVA tiêu chuẩn** với tải tùy chỉnh

  - **StoreType** – Loại cửa hàng được tạo OST/PST/NST

  - **StoreVersion** – Phiên bản cửa hàng đã tạo Small/Large/Tardis

#### <a name="officepowerpointdocoperationclose"></a>Office.PowerPoint.DocOperation.Close

Được thu thập khi bản trình bày PowerPoint được đóng lại. Nó chứa thông tin cần thiết để có thể điều tra và chẩn đoán chính xác các sự cố xảy ra thông qua quy trình chặt chẽ đòi hỏi phải duy trì và đồng bộ hóa dữ liệu của người dùng. Microsoft sử dụng dữ liệu này để đảm bảo rằng thao tác đóng hoạt động như mong đợi và nội dung người dùng được duy trì thành công.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemetryResult:long -** Mục nhập nhật ký này có tất cả các phép đo từ xa tài liệu cần thiết hay không (Các trường Dữ liệu\_Tài liệu\_\*) Nếu không, lý do là gì?

  - **Data\_AutoSaveDisabledReasons:string -** Tập hợp các giá trị được xác định trước về lý do tại sao lưu tự động bị vô hiệu hóa trên tài liệu này? (Lỗi phối, lỗi lưu, chính sách nhóm, v.v)

  - **Data\_CloseReason:long -** Thao tác đóng được thực hiện như thế nào? Đóng tài liệu? Đóng ứng dụng?

  - **Data\_CppUncaughtExceptionCount:long -** Số trường hợp ngoại lệ chưa được xử lý

  - **Data\_DetachedDuration:long -** Thời gian mà hoạt động bị tách ra/không chạy

  - **Data\_Doc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_Doc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_Doc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_Doc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_Doc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_Doc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_Doc\_IdentityTelemetryId:string – -** GUID duy nhất của người dùng

  - **Data\_Doc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_Doc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_Doc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Dữ liệu\_tài liệu\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_Doc\_IsIncrementalOpen:bool – -** : Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_Doc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Xác minh xem tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked:bool -** Xác minh xem tài liệu có được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive hay không

  - **Data\_Doc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_Doc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_Doc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_Doc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_Doc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_Doc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_Doc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Xác minh xem máy chủ có dựa trên Office14, Office15, Office 16 hay không

  - **Data\_Doc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_Doc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc kết hợp nhật ký phía máy khách và phía máy chủ

  - **Data\_Doc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_Doc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_Doc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_Doc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_Doc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_DocHasStorage:bool -** Tài liệu này có dung lượng lưu trữ cục bộ không?

  - **Data\_fLifeguarded:bool -** Tài liệu đã được bảo vệ chưa (tính năng tự sửa lỗi tài liệu mà không cần nhắc người dùng)?

  - **Data\_IsDocAutoSaveable:bool -** Bản trình bày có thể tự động được lưu không?

  - **Data\_IsDocDirty:bool -** Bản trình bày có những thay đổi chưa được lưu không?

  - **Data\_IsNewDoc:bool -** Là tài liệu mới hay tài liệu hiện có

  - **Data\_IsRecoveredDoc:bool -** Tài liệu có phải là tài liệu được khôi phục không? (Nếu phiên trước đó gặp sự cố, chúng tôi sẽ hiển thị ngăn khôi phục tài liệu vào phiên tiếp theo)

  - **Data\_NewDocDiscarded:bool -** Bản trình bày mới có phải đã bị loại bỏ mà không được lưu không

  - **Data\_OCSClosingDlgCanceled:bool -** Nếu quá trình tải lên đang chờ xử lý trên OCS trong khi người dùng đóng tài liệu, hộp thoại sẽ được bật lên để người dùng chờ. Người dùng chọn tuỳ chọn nào?

  - **Data\_OCSClosingDlgExpired:bool -** Có phải hộp thoại tự hết hạn (sau 1 phút) không?

  - **Data\_OCSClosingStatus:long -** Trạng thái cuối cùng của OCS (Trong CSI, Có thể được đóng, Trong chuyển tiếp OCS, Trong chuyển tiếp CSI, v.v.)

  - **Data\_OCSClosingWaitDurationMS:long -** Thời gian người dùng phải đợi để OCS tải lên

  - **Data\_OCSHandleTransitionResult:long -** Tập hợp các giá trị kết quả của quá trình chuyển tiếp được xác định trước trong khi đóng (Đã thử, tiếp tục đóng, v.v.)

  - **Data\_ServerDocId:string -** GUID để xác định duy nhất một tài liệu

  - **Data\_StopwatchDuration:long -** Tổng thời gian cho Hoạt động

  - **Data\_UserContinuedZRTClose:bool -** Khi đóng hộp thoại hiển thị, người dùng đã chọn “Tiếp tục” đóng chưa?

#### <a name="officepowerpointdocoperationnewdocument"></a>Office.PowerPoint.DocOperation.NewDocument

Được thu thập khi PowerPoint tạo bản trình bày mới. Bao gồm các số liệu về thành công, thất bại và hiệu suất.

Thông tin này được sử dụng để đảm bảo chúng tôi có thể tạo các tệp thành công và không bị suy giảm hiệu suất.

Các trường sau đây sẽ được thu thập:

  - **NewDocumentType** – Tài liệu mới có được tạo từ mẫu hay chỉ được tạo trống?

  - **FLifeguarded** – Tuổi thọ tài liệu có được bảo vệ không (tính năng khôi phục trạng thái tài liệu bị hỏng mà không nhắc người dùng)

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a>Office.PowerPoint.DocOperation.OpenCompleteProtocol

Được thu thập khi PowerPoint mở bản trình bày. Nó chứa thông tin cần thiết để có thể điều tra và chẩn đoán chính xác các vấn đề xảy ra trong giai đoạn cuối của quy trình mở.

Microsoft sử dụng dữ liệu này để đảm bảo tính năng này hoạt động như mong đợi và không có sự giảm hiệu suất khi mở các bản trình bày.

Các trường sau đây sẽ được thu thập:

  - **Data\_AntiVirusScanMethod:long -** Tập hợp các giá trị được xác định trước của loại chống vi-rút được quét (IOAV, AMSI, Không, v.v.)

  - **Data\_AntiVirusScanStatus:long -** Tập hợp các giá trị quét vi-rút được xác định trước xảy ra cho mọi tài liệu được mở (NoThreatDetected, Không thành công, MalwareDetected, v.v.)

  - **Data\_CloseAndReopen:bool -** Tài liệu này có phải đã được đóng và mở lại không?

  - **Data\_DetachedDuration:long -** Thời gian mà hoạt động bị tách ra/không chạy

  - **Data\_Doc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_Doc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_Doc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_Doc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_Doc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_Doc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_Doc\_IdentityTelemetryId:string – -** GUID duy nhất của người dùng

  - **Data\_Doc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_Doc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_Doc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Dữ liệu\_tài liệu\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_Doc\_IsIncrementalOpen:bool – -** : Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_Doc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không?

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_Doc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_Doc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_Doc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_Doc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_Doc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_Doc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_Doc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Xác minh xem máy chủ có dựa trên Office14, Office15, Office 16 hay không

  - **Data\_Doc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_Doc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc kết hợp nhật ký phía máy khách và phía máy chủ

  - **Data\_Doc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_Doc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_Doc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_Doc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_Doc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_ExecutionCount:long -** Số lần chúng tôi thực hiện giao thức IncOpen trước khi thực hiện giao thức (OpenComplete) này

  - **Data\_FailureComponent:long -** Tập hợp các giá trị được xác định trước của cấu phần khiến giao thức này bị lỗi? (Xung đột, CSI, Nội bộ, v.v..)

  - **Data\_FailureReason:long -** Tập hợp các giá trị được xác định trước về nguyên nhân lỗi (FileIsCorrupt, BlockedByAntillin, v.v.)

  - **Data_FullDownloadRoundTripCount:long -** Số lượng vòng tròn đến máy chủ được thực hiện để tải xuống toàn bộ tài liệu.
  
  - **Data_IsProtocolRunInIncOpenMode:bool -** Là giao thức được chạy cho tải xuống luỹ kế, đây là loại tải xuống trong đó các phần của tài liệu đã được tải xuống sau khi hiển thị cho người dùng vào lúc đầu.

  - **Data\_MethodId:long -** Dòng mã nào là mã cuối cùng được thực hiện nội bộ

  - **Data\_StopwatchDuration:long -** Tổng thời gian cho Hoạt động

  - **Data\_TimeToEdit:long -** Thời gian để tài liệu có thể được chỉnh sửa

  - **Data\_TimeToView:long -** Thời gian để trang chiếu đầu tiên của tài liệu đầu tiên được hiển thị

  - **Data\_UnhandledException:bool -** Có bất kỳ ngoại lệ gốc nào chưa xử lý không?

#### <a name="officepowerpointdocoperationsave"></a>Office.PowerPoint.DocOperation.Save

Được thu thập bất cứ khi nào PowerPoint thực hiện lưu bằng cách sử dụng đường dẫn mã hiện đại. Bao gồm loại kết quả thành công hoặc thất bại của số liệu về hiệu suất lưu và siêu dữ liệu của tài liệu có liên quan. Thất bại trong việc lưu có thể gây mất dữ liệu. Microsoft sử dụng dữ liệu này để đảm bảo tính năng này hoạt động như mong đợi và nội dung người dùng được duy trì thành công.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemetryResult:long -** Mục nhập nhật ký này có tất cả các phép đo từ xa tài liệu cần thiết hay không (Các trường Dữ liệu\_Tài liệu\_\*) Nếu không, lý do là gì?

  - **Data\_BeforeSaveEvent:long -** Thời gian dành để nâng cao tài liệu trước sự kiện lưu

  - **Data\_CheckDownRevSaveTimeMS:long -** Thời gian thực hiện kiểm tra hiệu đính

  - **Data\_CheckMacroSaveTimeMS:long -** Thời gian để lưu macro

  - **Data\_ClearAutoSaveTimeMS:long -** Thời gian để xóa cờ Lưu tự động

  - **Data\_ClearDirtyFlagTimeMS:long -** Thời gian để xóa cờ rác tài liệu

  - **Data\_CloneDocumentTimeMS:long -** Thời gian để sao chép tài liệu trước khi bắt đầu lưu

  - **Data\_CommitTransactionTimeMS:long -** Thời gian thực hiện giao tác lưu

  - **Data\_CppUncaughtExceptionCount:long -** Không theo kịp ngoại lệ riêng trong khi hoạt động đang chạy

  - **Data\_DetachedDuration:long -** Thời gian mà hoạt động bị tách ra/không chạy

  - **Data\_Doc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_Doc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_Doc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_Doc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_Doc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_Doc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_Doc\_IdentityTelemetryId:string – -** GUID duy nhất của người dùng

  - **Data\_Doc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_Doc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_Doc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Dữ liệu\_tài liệu\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_Doc\_IsIncrementalOpen:bool – -** : Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_Doc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Xác minh xem tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_Doc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_Doc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_Doc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_Doc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_Doc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_Doc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_Doc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Xác minh xem máy chủ có dựa trên Office14, Office15, Office 16 hay không

  - **Data\_Doc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_Doc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc tương quan nhật ký phía máy khách và phía máy chủ

  - **Data\_Doc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_Doc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_Doc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_Doc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_Doc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_DurationUAEOnSaveStartedMs:long -** Thời gian để Thoát ứng dụng không xác định trong khi lưu

  - **Data\_EnsureSaveTransactionTimeMS:long -** Thời gian thực hiện để đảm bảo giao tác lưu được tạo nếu không tồn tại.

  - **Data\_FailureComponent:long -** Tập hợp các giá trị được xác định trước của cấu phần khiến giao thức này bị lỗi? (Xung đột, CSI, Nội bộ, v.v..)

  - **Data\_FailureReason:long -** Tập hợp các giá trị được xác định trước về nguyên nhân lỗi (FileIsCorrupt, BlockedByAntillin, v.v.)

  - **Data\_fLifeguarded:bool -** Tài liệu đã được bảo vệ chưa (tính năng tự sửa lỗi tài liệu mà không cần nhắc người dùng)?

  - **Data\_HandleEnsureContentType:long -** Thời gian để đảm bảo tất cả các loại nội dung là chính xác

  - **Data\_HandleEnsureContentTypeTimeMS:long -** Thời gian để đảm bảo tất cả các loại nội dung là chính xác

  - **Data\_HasEmbeddedFont:bool -** Tài liệu này có phông chữ được nhúng không?

  - **Data\_InitializeSaveTimeMS:long -** Thời gian để khởi tạo nội dung tài liệu để bắt đầu lưu

  - **Data\_InOCSTransition:bool -** Thao tác lưu có được thực hiện khi chuyển tiếp OCS không

  - **Data\_IsSavingWithEmbeddedFont:bool -** Tài liệu này có phông chữ được nhúng không?

  - **Data\_MethodId:long -** Dòng mã nào là mã cuối cùng được thực hiện nội bộ

  - **Data\_PerformEmbedFontsTimeMS:long -** Thời gian để xếp nối tiếp các phông chữ được nhúng

  - **Data\_PerformModernSaveTimeMS:long -** Thời gian thực hiện để lưu hiện đại (mã mới)

  - **Data\_PerformPostSaveTimeMS:long -** Thời gian thực hiện các chức năng lưu bài đăng (thông báo, hoàn tác mục nhập)

  - **Data\_PrepareForSaveTimeMS:long -** Thời gian để bắt đầu lưu

  - **Data\_RaiseDocumentBeforeSaveEventTimeMS:long -** Thời gian để nâng cao sự kiện BeforeSave

  - **Data\_ReflectDocumentChangeTimeMS:long -** Thời gian để phản ánh các thay đổi đã lưu vào giao diện người dùng (lặp lại hình thu nhỏ, v.v.)

  - **Data\_ReportStartTimeMS:long -** Thời gian để hoàn thành việc khởi tạo từ xa cho thao tác lưu

  - **Data\_ReportSuccessTimeMS:long -** Thời gian để hoàn thành báo cáo lưu thành công

  - **Data\_ResetDirtyFlagOnErrorTimeMS:long -** Thời gian để thiết lập lại cờ rác tài liệu bị lỗi

  - **Data\_SaveReason:long -** Tập hợp các giá trị được xác định trước về lý do tại sao thao tác lưu này được thực hiện? (Lưu tự động, ToOCSTransitionSave, ToCSITransitionSave v.v..)

  - **Data\_SaveType:long -** Tập hợp các giá trị được xác định trước của loại lưu (Lưu dưới dạng, Phát hành, Thủ công, OMSave, v.v.)

  - **Data\_SavingWithFont:bool-** Có phải chúng tôi đang lưu tài liệu với phông chữ được nhúng mới không?

  - **Data\_ScrubClonedDocumentTimeMS:long -** Thời gian để xóa thông tin cá nhân trên bản sao tài liệu nhân bản

  - **Data\_StopwatchDuration:long -** Tổng thời gian cho Hoạt động

  - **Data\_TransactionType:long -** Đó là giao tác Lưu hay MergeAndSave?

#### <a name="officepowerpointdocoperationsaveas"></a>Office.PowerPoint.DocOperation.SaveAs

Được thu thập bất cứ khi nào PowerPoint thực hiện lưu dưới dạng. Bao gồm loại kết quả thành công hoặc thất bại của số liệu về hiệu suất lưu và siêu dữ liệu của tài liệu có liên quan. Thất bại trong việc lưu có thể gây mất dữ liệu.

Microsoft sử dụng dữ liệu này để đảm bảo tính năng này hoạt động như mong đợi và nội dung người dùng được duy trì thành công.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemetryResult:long -** Mục nhập nhật ký này có tất cả các phép đo từ xa tài liệu cần thiết hay không (Các trường Dữ liệu\_Tài liệu\_\*) Nếu không, lý do là gì?

  - **Data\_CppUncaughtExceptionCount:long -** Không theo kịp ngoại lệ riêng trong khi hoạt động đang chạy

  - **Data\_DetachedDuration:long -** Thời gian mà hoạt động bị tách ra/không chạy

  - **Data\_DstDoc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_DstDoc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_DstDoc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_DstDoc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_DstDoc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_DstDoc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_DstDoc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_DstDoc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_DstDoc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_DstDoc\_IdentityTelemetryId:string -** GUID duy nhất của người dùng

  - **Data\_DstDoc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_DstDoc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_DstDoc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Data\_DstDoc\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_DstDoc\_IsIncrementalOpen:bool -** Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_DstDoc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_DstDoc\_IsOpeningOfflineCopy:bool -** Xác minh xem tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không

  - **Data\_DstDoc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_DstDoc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_DstDoc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_DstDoc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_Doc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_DstDoc\_ReadOnlyReasons:long -** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_DstDoc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_DstDoc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_DstDoc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_DstDoc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_DstDoc\_ServerVersion:long -** Xác minh xem máy chủ có dựa trên Office14, Office15, Office 16 hay không

  - **Data\_DstDoc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_DstDoc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc kết hợp nhật ký phía máy khách và phía máy chủ

  - **Data\_DstDoc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_DstDoc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_DstDoc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_DstDoc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_DstDoc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_DstDoc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_DstDoc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_FileType:long -** Tập hợp giá trị được xác định trước của loại tệp nội bộ

  - **Data\_fLifeguarded:bool -** Tài liệu đã được bảo vệ chưa (tính năng tự sửa lỗi tài liệu mà không cần nhắc người dùng)?

  - **Data\_FWebCreated:bool -** Tài liệu này có cờ WebCreator không?

  - **Data\_SaveReason:long -** Tập hợp các giá trị được xác định trước về lý do tại sao thao tác lưu này được thực hiện? (Lưu tự động, ToOCSTransitionSave, ToCSITransitionSave v.v..)

  - **Data\_SaveType:long -** Tập hợp các giá trị được xác định trước của loại lưu (Lưu dưới dạng, Phát hành, Thủ công, OMSave, v.v.)

  - **Data\_SrcDoc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_SrcDoc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_SrcDoc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_SrcDoc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_SrcDoc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_SrcDoc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_SrcDoc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_SrcDoc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_SrcDoc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_SrcDoc\_IdentityTelemetryId:string -** GUID duy nhất của người dùng

  - **Data\_SrcDoc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_SrcDoc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_SrcDoc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Data\_SrcDoc\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_SrcDoc\_IsIncrementalOpen:bool -** Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_SrcDoc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_SrcDoc\_IsOpeningOfflineCopy:bool -** Xác minh xem tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không

  - **Data\_SrcDoc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_SrcDoc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_SrcDoc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_SrcDoc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_SrcDoc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_SrcDoc\_ReadOnlyReasons:long -** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_SrcDoc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_SrcDoc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_SrcDoc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_SrcDoc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_SrcDoc\_ServerVersion:long -** Xác minh nếu máy chủ dựa trên Office14, Office15 hoặc Office 16Data\_SrcDoc\_SessionId:long GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_SrcDoc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc kết hợp nhật ký phía máy khách và phía máy chủ

  - **Data\_SrcDoc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_SrcDoc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_SrcDoc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_SrcDoc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_SrcDoc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_SrcDoc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_SrcDoc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_StopwatchDuration:long -** Tổng thời gian cho Hoạt động

  - **Data\_TypeOfSaveDialog:long -** Tập hợp các giá trị được xác định trước của Hộp thoại (CHẠY\_LƯU DƯỚI DẠNG\_, CHẠY\_LƯU PHƯƠNG TIỆN\_, CHẠY\_LƯU DƯỚI DẠNG\_VIDEO\_, v.v.)

  - **DstDoc -** Vị trí mới của tài liệu

  - **SrcDoc -** Vị trí ban đầu của tài liệu

#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Được thu thập bất cứ khi nào PowerPoint thực hiện lưu bằng cách sử dụng đường dẫn mã kế thừa. Bao gồm loại kết quả thành công hoặc thất bại của số liệu về hiệu suất lưu và siêu dữ liệu của tài liệu có liên quan. Thất bại trong việc lưu có thể gây mất dữ liệu. Microsoft sử dụng dữ liệu này để đảm bảo tính năng này hoạt động như mong đợi và nội dung người dùng được duy trì thành công.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemetryResult:long -** Mục nhập nhật ký này có tất cả các phép đo từ xa tài liệu cần thiết hay không (Các trường Dữ liệu\_Tài liệu\_\*) Nếu không, lý do là gì?

  - **Data\_CppUncaughtExceptionCount:long -** Không theo kịp ngoại lệ riêng trong khi hoạt động đang chạy

  - **Data\_DetachedDuration:long -** Thời gian mà hoạt động bị tách ra/không chạy

  - **Data\_Doc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_Doc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_Doc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_Doc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_Doc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_Doc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_Doc\_IdentityTelemetryId:string – -** GUID duy nhất của người dùng

  - **Data\_Doc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_Doc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_Doc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Dữ liệu\_tài liệu\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_Doc\_IsIncrementalOpen:bool – -** : Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_Doc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Xác minh xem tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_Doc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_Doc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_Doc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_Doc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_Doc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_Doc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_Doc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Xác minh xem máy chủ có dựa trên Office14, Office15, Office 16 hay không

  - **Data\_Doc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_Doc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc kết hợp nhật ký phía máy khách và phía máy chủ

  - **Data\_Doc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_Doc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_Doc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_Doc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_Doc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_DstDoc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_DstDoc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_DstDoc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_DstDoc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_DstDoc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_DstDoc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_DstDoc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_DstDoc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_DstDoc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_DstDoc\_IdentityTelemetryId:string -** GUID duy nhất của người dùng

  - **Data\_DstDoc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_DstDoc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_DstDoc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Data\_DstDoc\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_DstDoc\_IsIncrementalOpen:bool -** Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_DstDoc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_DstDoc\_IsOpeningOfflineCopy:bool -** Xác minh xem tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không

  - **Data\_DstDoc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_DstDoc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_DstDoc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_DstDoc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_DstDoc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_DstDoc\_ReadOnlyReasons:long -** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_DstDoc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_DstDoc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_DstDoc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_DstDoc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_DstDoc\_ServerVersion:long -** Xác minh xem máy chủ có dựa trên Office14, Office15, Office 16 hay không

  - **Data\_DstDoc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_DstDoc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc kết hợp nhật ký phía máy khách và phía máy chủ

  - **Data\_DstDoc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_DstDoc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_DstDoc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_DstDoc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_DstDoc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_DstDoc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_DstDoc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_FileType:long -** Tập hợp giá trị được xác định trước của loại tệp nội bộ

  - **Data\_fLifeguarded:bool -** Tài liệu đã được bảo vệ chưa (tính năng tự sửa lỗi tài liệu mà không cần nhắc người dùng)?

  - **Data\_SaveReason:long -** Tập hợp các giá trị được xác định trước về lý do tại sao thao tác lưu này được thực hiện? (Lưu tự động, ToOCSTransitionSave, ToCSITransitionSave v.v..)

  - **Data\_SaveType:long -** Tập hợp các giá trị được xác định trước của loại lưu (Lưu dưới dạng, Phát hành, Thủ công, OMSave, v.v.)

  - **Data\_SrcDoc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc | đọc ghi)

  - **Data\_SrcDoc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_SrcDoc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_SrcDoc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_SrcDoc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_SrcDoc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_SrcDoc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_SrcDoc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_SrcDoc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_SrcDoc\_IdentityTelemetryId:string -** GUID duy nhất của người dùng

  - **Data\_SrcDoc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_SrcDoc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_SrcDoc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Data\_SrcDoc\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_SrcDoc\_IsIncrementalOpen:bool -** Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_SrcDoc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_SrcDoc\_IsOpeningOfflineCopy:bool -** Xác minh xem tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không

  - **Data\_SrcDoc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_SrcDoc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_SrcDoc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_SrcDoc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_SrcDoc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_SrcDoc\_ReadOnlyReasons:long -** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_SrcDoc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_SrcDoc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_SrcDoc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_SrcDoc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_SrcDoc\_ServerVersion:long -** Xác minh xem máy chủ có dựa trên Office14, Office15, Office 16 hay không

  - **Data\_SrcDoc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_SrcDoc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc kết hợp nhật ký phía máy khách và phía máy chủ

  - **Data\_SrcDoc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_SrcDoc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_SrcDoc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_SrcDoc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_SrcDoc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_SrcDoc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_SrcDoc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_StopwatchDuration:long -** Tổng thời gian cho Hoạt động

  - **Data\_TypeOfSaveDialog:long -** Tập hợp các giá trị được xác định trước của Hộp thoại (CHẠY\_LƯU DƯỚI DẠNG\_, CHẠY\_LƯU PHƯƠNG TIỆN\_, CHẠY\_LƯU DƯỚI DẠNG\_VIDEO\_, v.v.)

  - **Doc -** Tài liệu hiện tại để Lưu

  - **DstDoc -** Vị trí mới của tài liệu (trong trường hợp Lưu dưới dạng)

  - **SrcDoc -** Vị trí ban đầu của tài liệu (trong trường hợp Lưu dưới dạng)

#### <a name="officepowerpointpptsharedslideshowfailure"></a>Office.PowerPoint.PPT.Shared.SlideShow.Failure

Thu thập lần thất bại trong quá trình trình chiếu. Trình chiếu là một tính năng chính cho PowerPoint. Microsoft đang thu thập khi xảy ra lỗi trong quá trình trình chiếu để giúp cải thiện trải nghiệm người dùng trên trình chiếu. Microsoft sử dụng dữ liệu này để nhận thông tin chẩn đoán về nơi xảy ra lỗi trong khi người dùng đang sử dụng trình chiếu

Các trường sau đây sẽ được thu thập:

  - **CountSlideShowErrors** - Tổng số lỗi trình chiếu

  - **CountPPTErrors** - Tổng số lỗi PPT

  - **CountOArtErrors** - Tổng số lỗi OArt

  - **CountOtherErrors** - Tổng số lỗi khác

  - **FirstSlideShowError** - Lỗi đầu tiên xảy ra trong trình chiếu

  - **FirstOArtError** - Lỗi đầu tiên xảy ra trong OArt

  - **FirstPPTError** - Lỗi đầu tiên xảy ra trong PPT

  - **FirstOtherError** - Lỗi đầu tiên xảy ra trong khu vực khác

#### <a name="officeprojectprojectfilesave"></a>Office.Project.ProjectFileSave

Project lưu một tệp. Sự kiện này cho biết một thao tác lưu của Project. Nó cho phép Microsoft đo lường sự thành công của Project khi lưu một tệp quan trọng để tránh mất dữ liệu tài liệu.

Các trường sau đây sẽ được thu thập:

  - **Data\_TriggerTime** - Thời gian của thao tác lưu

  - **Data\_FileType** - Loại tệp mà Project đang được lưu dưới dạng
 
#### <a name="officesessionactivitystart"></a>Office.Session.Activity.Start

Cho phép chúng tôi biết khi nào một phiên phát trực tuyến dữ liệu bắt đầu.  Sử dụng để giám sát và biết về trạng thái tính năng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Activity_Name** = Tên của hoạt động “Session”

- **Activity_CV** = ID để kết hợp các sự kiện trong phiên kết nối

- **Activity_StartStopType** = Bắt đầu

- **Activity_DateTimeTicks** = Dữ liệu về thời gian cho hoạt động

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

Cho phép chúng tôi biết khi nào một phiên phát trực tuyến dữ liệu dừng. Được sử dụng để theo dõi và biết về trạng thái tính năng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Activity_Name** = Tên của hoạt động “Session”

- **Activity_CV** = ID để kết hợp các sự kiện trong phiên kết nối

- **Activity_StartStopType** - Stop

- **Activity_DateTimeTicks** = Dữ liệu về thời gian cho hoạt động

#### <a name="officestreamdeviceactivitystart"></a>Office.StreamDevice.Activity.Start

Cho phép chúng tôi biết nếu phát trực tuyến nguồn dữ liệu thành công.   Sử dụng để giám sát và biết về trạng thái tính năng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Datasource_Type** - Sê-ri của thiết bị hoặc thông tin Dịch vụ ứng dụng

- **DataSource_Name** - Tên của nguồn dữ liệu được kết nối

- **Activity_Name** - Tên của hoạt động "StreamDeviceData" hoặc "StreamFileData"

- **Activity_CV** = ID để kết hợp các sự kiện trong phiên kết nối

- **Activity_StartStopType** = Bắt đầu

- **Activity_DateTimeTicks** = Dữ liệu về thời gian cho hoạt động

#### <a name="officestreamdeviceactivitystop"></a>Office.StreamDevice.Activity.Stop

Cho phép chúng tôi biết nếu ngừng phát trực tuyến nguồn dữ liệu thành công.   Sử dụng để giám sát và biết về trạng thái tính năng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Datasource_Type** - Sê-ri của thiết bị hoặc thông tin Dịch vụ ứng dụng

- **DataSource_Name** - Tên của nguồn dữ liệu được kết nối

- **Activity_Name** - Tên của hoạt động "StreamDeviceData" hoặc "StreamFileData"

- **Activity_CV** = ID để kết hợp các sự kiện trong phiên kết nối

- **Activity_StartStopType** - Stop

- **Activity_DateTimeTicks** = Dữ liệu về thời gian cho hoạt động

#### <a name="officetargetedmessagingabexperimentmessagetrigger"></a>Office.TargetedMessaging.ABExperimentMessageTrigger

Theo dõi số người dùng nhận tin nhắn BizBar và bảng tùy biến động từ TargetedMessagingService (TMS). Dữ liệu này rất quan trọng để hiểu được những thư mà người dùng đang nhận được và trên bề mặt nào để chúng tôi có thể đảm bảo rằng họ không bỏ lỡ bất kỳ thư nào có thể quan trọng đối với việc họ tiếp tục sử dụng sản phẩm. Dữ liệu này cũng cần thiết để đo lường chính xác mức độ thành công của các thử nghiệm và chiến dịch của chúng tôi chạy thông qua TMS.

Các trường sau đây sẽ được thu thập:

  - **Data\_Surface** – Tên của bề mặt mà dịch vụ này gửi thông báo dành cho

  - **Data\_Flight** – Mã định danh ECS/CT Flight đã được sử dụng để gửi thông báo này

  - **Data\_CampaignId** – Mã định danh của chiến dịch mà thông báo này là một phần

  - **Data\_MessageId** – Mã định danh của thiết bị đã gửi thông báo

  - **Data\_TransactionId** – Mã định danh của giao dịch này với dịch vụ

  - **Data\_TriggerPoint** – Bước mà sự kiện này được ghi lại (thông báo nhận được so với thông báo được hiển thị)

#### <a name="officetextfontpickerfontselectedwin32"></a>Office.Text.FontPickerFontSelected.Win32

Sự kiện này cho biết liệu phông chữ đã tải xuống có được hiển thị chính xác hay không. Được sử dụng để chỉ sự thành công hay thất bại của việc tải xuống phông chữ.

Các trường sau đây sẽ được thu thập:

  - **Font name (Data\_Font)** - Tên của phông chữ được chọn trong bộ chọn phông chữ

  - **User click (Data\_FClick)** - Nếu người dùng sử dụng chuột để chọn mục

#### <a name="officetextresourceclientrequestresourceinternal"></a>Office.Text.ResourceClient.RequestResourceInternal

Sự kiện này cho biết liệu phông chữ đã được tải xuống chính xác hay không. Được sử dụng để chỉ sự thành công hay thất bại của việc kết xuất phông chữ được tải xuống.

Các trường sau đây sẽ được thu thập:

  - **Data\_FontToken** - Tên tệp tài nguyên sẽ được lưu dưới dạng

  - **Data\_HTTPResult** - Kết quả của yêu cầu HTTP

  - **Data\_HTTPStatusCode** - Mã HTTP được trả về từ yêu cầu HTTP

  - **Data\_isInternetOn** - Nếu chúng tôi có kết nối khi tìm cách truy xuất tài nguyên

  - **Data\_RequestUrl** - URL của tài nguyên CDN mà chúng tôi đang cố gắng truy xuất

#### <a name="officetranslatordocumenttranslated"></a>Office.Translator.DocumentTranslated

Thu thập sự thành công hay thất bại của bản dịch tài liệu đầy đủ mà người dùng kích hoạt trong Translator SDX. Điều này là rất quan trọng để đánh giá trạng thái của tính năng và phản ứng với bất kỳ sự cố ngừng hoạt động nào có thể xảy ra. Giám sát trạng thái của kịch bản "Dịch tài liệu" trong Word.

Các trường sau đây sẽ được thu thập:

  - **Data.actionSource -** Cách lựa chọn dịch được kích hoạt -

  - **Data.bodyBackgroundColor -** Màu nền bộ chứa chủ đề Office-

  - **Data.bodyForegroundColor -** Màu mặt trước bộ chứa chủ đề Office-

  - **Data.browserLang -** Ngôn ngữ hiển thị hiện tại của trình duyệt-

  - **Data.browserOnline -** Đã lỗi thời -

  - **Data.browserPlatform -** Nền tảng trình duyệt-

  - **Data.browserUserAgent -** Tác nhân người dùng của trình duyệt -

  - **Data.colorDepth -** Độ sâu màu hệ thống-

  - **Data.contentLanguage -** Ngôn ngữ được phát hiện của nội dung cần dịch-

  - **Data.controlBackgroundColor -** Màu nền bộ chứa chủ đề Office-

  - **Data.controlForegroundColor -** Màu mặt trước bộ chứa chủ đề Office-

  - **Data.correlationId -** Mã định danh duy nhất của yêu cầu được gửi đến dịch vụ-

  - **Data.crossSessionId -** Mã định danh duy nhất của người dùng-

  - **Data.crossSessionStartTime -** Dấu thời gian UTC khi bắt đầu phiên dịch-

  - **Data.currentTime -** Dấu thời gian UTC khi thông báo phép đo từ xa này được gửi-

  - **Data.displayLanguage -** Ngôn ngữ hiển thị của Office -

  - **Data.documentSourceLang -** Ngôn ngữ của nội dung tài liệu-

  - **Data.documentTargetLang -** Ngôn ngữ mà tài liệu sẽ được dịch sang-

  - **Data.Environment -** Môi trường dịch vụ mà yêu cầu được gửi tới-

  - **Data.errorMessage -** Thông báo lỗi được báo cáo bởi dịch vụ-

  - **Data.eventActionType -** Loại sự kiện phép đo từ xa -

  - **Data.eventTagId -** Mã định danh duy nhất của dòng mã tạo ra thông báo phép đo từ xa này-

  - **Data.Flights -** Chuyến bay được bật -

  - **Data.fileSize -** Kích cỡ tệp Word để dịch-

  - **Data.fileSource -** Nơi tệp Word được lưu trữ (ngoại tuyến, trực tuyến)-

  - **Data.fileType -** Phần mở rộng tệp Word-

  - **Data.innerHeight "-** Chiều cao bộ chứa ngăn bên-

  - **Data.innerWidth "-** Chiều rộng bộ chứa ngăn bên -

  - **Data.lookupSourceLang-** Không được sử dụng để dịch tài liệu-

  - **Data.lookupTargetLang-** Không được sử dụng để dịch tài liệu-

  - **Data.officeHost-** Ứng dụng Office lưu trữ ngăn bên-

  - **Data.officeLocale-** Ngôn ngữ người dùng Office-

  - **Data.officeMachineId-** Mã định danh duy nhất của thiết bị-

  - **Data.officePlatform -** Nền tảng của thiết bị-

  - **Data.officeSessionId -** Mã định danh phiên Office -

  - **Data.officeUserId -** Mã định danh duy nhất của người dùng Office-

  - **Data.officeVersion -** Phiên bản Office-

  - **Data.pageXOffset -** Vị trí cuộn ngang của ngăn bên từ phía bên trái của ngăn-

  - **Data.pageYOffset -** Vị trí cuộn dọc của ngăn bên từ phía trên cùng của ngăn-

  - **Data.pixelDepth -** Độ phân giải màu màn hình-

  - **Data.responseCode -** Mã phản hồi yêu cầu từ dịch vụ-

  - **Data.responseTime -** Thời gian đã qua của yêu cầu -

  - **Data.resultType -** Kết quả của yêu cầu -

  - **Data.screenHeight -** Chiều cao màn hình tính bằng pixel-

  - **Data.screenLeft -** Tọa độ ngang của cửa sổ so với màn hình-

  - **Data.screenTop -** Tọa độ dọc của cửa sổ so với màn hình-

  - **Data.screenWidth -** Chiều rộng màn hình tính bằng pixel-

  - **Data.selectedTab -** Tab nào được chọn Lựa chọn hoặc Tài liệu-

  - **Data.serverUrl -** URL dịch vụ dịch-

  - **Data.sessionId -** Mã định danh phiên ngăn bên-

  - **Data.sessionStartTime -** Dấu thời gian UTC khi bắt đầu phiên dịch-

  - **Data.sourceTextHash -** Hàm băm của văn bản để dịch-

  - **Data.sourceTextLength -** Chiều dài của văn bản để dịch-

  - **Data.sourceTextWords -** Số từ trong văn bản để dịch-

  - **Data.warningMessage -** Thông báo cảnh báo được dịch vụ báo cáo-

#### <a name="officetranslatortexttranslated"></a>Office.Translator.TextTranslated

Thu thập sự thành công hay thất bại của bản dịch lựa chọn mà thao tác người dùng kích hoạt trong Translator SDX. Điều này là rất quan trọng để đánh giá trạng thái của tính năng và phản ứng với bất kỳ sự cố ngừng hoạt động nào có thể xảy ra. Được sử dụng để theo dõi trạng thái cho kịch bản "Lựa chọn dịch" trong Excel, PowerPoint, Word.

Các trường sau đây sẽ được thu thập:

  - **Data.actionSource -** Cách lựa chọn dịch được kích hoạt

  - **Data.bodyBackgroundColor -** Màu nền bộ chứa chủ đề Office

  - **Data.bodyForegroundColor -** Màu mặt trước bộ chứa chủ đề Office

  - **Data.browserLang -** Ngôn ngữ hiển thị hiện tại của trình duyệt

  - **Data.browserOnline -** Đã lỗi thời

  - **Data.browserPlatform -** Nền tảng trình duyệt

  - **Data.browserUserAgent -** Tác nhân người dùng của trình duyệt

  - **Data.colorDepth -** Độ sâu màu hệ thống

  - **Data.contentLanguage -** Ngôn ngữ được phát hiện của nội dung cần dịch

  - **Data.controlBackgroundColor -** Màu nền bộ chứa chủ đề Office

  - **Data.controlForegroundColor -** Màu mặt trước bộ chứa chủ đề Office

  - **Data.correlationId -** Mã định danh duy nhất của yêu cầu được gửi đến dịch vụ

  - **Data.crossSessionId -** Mã định danh duy nhất của người dùng

  - **Data.crossSessionStartTime -** Dấu thời gian UTC khi bắt đầu phiên dịch

  - **Data.currentTime -** Dấu thời gian UTC khi thông báo phép đo từ xa này được gửi

  - **Data.displayLanguage -** Ngôn ngữ hiển thị của Office

  - **Data.documentSourceLang -** Không được sử dụng để chọn

  - **Data.documentTargetLang -** Cũng không được sử dụng để lựa chọn dịch

  - **Data.Environment -** Môi trường dịch vụ mà yêu cầu được gửi tới

  - **Data.errorMessage -** Thông báo lỗi được báo cáo bởi dịch vụ

  - **Data.eventActionType -** Loại sự kiện phép đo từ xa -

  - **Data.eventTagId -** Mã định danh duy nhất của dòng mã tạo ra thông báo phép đo từ xa này

  - **Data.Flights -** Chuyến bay được bật

  - **Data.innerHeight "-** Chiều cao bộ chứa ngăn bên

  - **Data.innerWidth "-** Chiều rộng bộ chứa ngăn bên

  - **Data.lookupSourceLang-** Ngôn ngữ của văn bản hiện đang được chọn

  - **Data.lookupTargetLang-** Ngôn ngữ văn bản hiện được chọn sẽ được dịch sang

  - **Data.officeHost-** Ứng dụng Office lưu trữ ngăn bên

  - **Data.officeLocale-** Ngôn ngữ người dùng Office

  - **Data.officeMachineId-** Mã định danh duy nhất của thiết bị

  - **Data.officePlatform -** Nền tảng của thiết bị

  - **Data.officeSessionId -** Mã định danh phiên Office

  - **Data.officeUserId -** Mã định danh duy nhất của người dùng Office

  - **Data.officeVersion -** Phiên bản Office

  - **Data.pageXOffset -** Vị trí cuộn ngang của ngăn bên từ phía bên trái của ngăn

  - **Data.pageYOffset -** Vị trí cuộn dọc của ngăn bên từ phía trên cùng của ngăn

  - **Data.pixelDepth -** màu độ phân giải màn hình

  - **Data.responseCode -** Mã phản hồi yêu cầu từ dịch vụ

  - **Data.responseTime -** Thời gian đã qua của yêu cầu

  - **Data.resultType -** Kết quả của yêu cầu

  - **Data.screenHeight -** Chiều cao màn hình tính bằng pixel

  - **Data.screenLeft -** Tọa độ ngang của cửa sổ so với màn hình

  - **Data.screenTop -** Tọa độ dọc của cửa sổ so với màn hình

  - **Data.screenWidth -** Chiều rộng màn hình tính bằng pixel

  - **Data.selectedTab -** Tab nào được chọn Lựa chọn hoặc Tài liệu

  - **Data.serverUrl -** URL dịch vụ dịch

  - **Data.sessionId -** Mã định danh phiên ngăn bên

  - **Data.sessionStartTime -** Dấu thời gian UTC khi bắt đầu phiên dịch

  - **Data.sourceTextHash -** Hàm băm của văn bản để dịch

  - **Data.sourceTextLength -** Chiều dài của văn bản để dịch

  - **Data.sourceTextWords -** Số từ trong văn bản để dịch

  - **Data.warningMessage -** Thông báo cảnh báo được dịch vụ báo cáo

#### <a name="officewordexperimentationdocumentstatsoncloseandsuspend"></a>Office.Word.Experimentation.DocumentStatsOnCloseAndSuspend

Sự kiện này ghi lại số liệu thống kê tài liệu cho từng tài liệu khi Office Word bị đóng hoặc bị tạm ngừng.

Sự kiện này được sử dụng để kết hợp các chỉnh sửa tài liệu, kích thước, v.v. với các lỗi lưu tài liệu, chia sẻ tài liệu và tài liệu cộng tác trực tuyến.

Các trường sau đây sẽ được thu thập:

  - **Data\_BkmkRefCount -** Số lượng tham chiếu thẻ đánh dấu trong tài liệu

  - **Data\_CharacterCount -** Số lượng ký tự trong tài liệu

  - **Data\_CharactersWithSpaceCount -** Số lượng ký tự và khoảng trắng trong tài liệu

  - **Data\_ChartCount -** Số lượng ký tự trong tài liệu

  - **Data\_CitationCount -** Số lượng trích dẫn trong tài liệu

  - **Data\_DocumentLocation -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_ETW\_TrackbackTag -** Xác định địa điểm trong mã nơi sự kiện này được kích hoạt (Đóng hoặc Tạm ngừng)

  - **Data\_EndnoteDocCount -** Số lượng chú thích cuối trong tài liệu

  - **Data\_FootnoteDocCount -** Số chú thích cuối trang trong tài liệu

  - **Data\_HasBibliography -** Cho biết liệu tài liệu có chứa danh mục tham khảo hay không

  - **Data\_HasHeader -** Cho biết liệu tài liệu có chứa đầu trang hay không

  - **Data\_IsImeUsed -** Cho biết liệu Trình soạn thảo phương pháp nhập có được sử dụng trong tài liệu hay không

  - **Data\_IsPageCountInProgress -** Cho biết số lượng trang hiện đang được thực hiện cho tài liệu.

  - **Data\_IsTouchUsed -** Cho biết liệu phương pháp nhập chạm có được sử dụng trong tài liệu hay không

  - **Data\_IsTrackChangesOn -** Cho biết liệu theo dõi thay đổi có được bật cho tài liệu hay không

  - **Data\_LineCount -** Số dòng trong tài liệu

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word.

  - **Data\_PageCount -** Số trang trong tài liệu

  - **Data\_PageNumberFieldCount -** Số trường số trang trong tài liệu

  - **Data\_ParagraphCount -** Số đoạn trong tài liệu

  - **Data\_PicCount -** Số lượng ảnh trong tài liệu

  - **Data\_RsidCount -** Số hiệu đính lưu mã định danh trong tài liệu

  - **Data\_TocCount -** Số lượng mục lục trong tài liệu

  - **Data\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_UserActionID -** Trường dữ liệu này không được sử dụng (giá trị luôn là 0).

  - **Data\_UserActionName -** luôn là “DocumentStatsOnCloseAndSuspend”

  - **Data\_UserInteractionTimeMsec -** Số mili giây mà người dùng đã tích cực tương tác với tài liệu

  - **Data\_WordCount -** Số từ trong tài liệu

#### <a name="officewordfilenewcreatenewfile"></a>Office.Word.FileNew.CreateNewFile

Sự kiện này cho biết rằng một tài liệu mới được tạo trong Office Word và theo dõi thành công hay thất bại của hoạt động này. Sự kiện này được sử dụng để theo dõi việc tạo tài liệu mới đang hoạt động như mong đợi. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_DirtyState** - Tài liệu có được tạo ở trạng thái tác hay không (với những thay đổi cần được lưu)

  - **Data\_ErrorID** - Mã định danh lỗi trong trường hợp thao tác không thành công

  - **Data\_MainPdod** Mã định danh tài liệu trong phiên quy trình này

  - **Data\_UsesCustomTemplate** -Cho biết tài liệu đã được tạo từ một mẫu tùy chỉnh hay chưa

#### <a name="officewordfilesaveactcmdgosubsaveas"></a>Office.Word.FileSave.ActCmdGosubSaveAs

Sự kiện này cho thấy rằng người dùng đang lưu các thay đổi của họ vào một tài liệu mới. Sự kiện theo dõi xem thao tác lưu vào tài liệu mới có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemRes -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_DetachedDuration -** Thời gian hoạt động được tách ra từ chuỗi

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_Doc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_EditorDisablingRename -** Mã định danh của trình chỉnh sửa đầu tiên khiến việc đổi tên bị vô hiệu hóa

  - **Data\_EditorsCount -** Số lượng trình chỉnh sửa trong tài liệu

  - **Data\_LastLoggedTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định khi chúng tôi cố gắng không mở hai lần (được sử dụng để chẩn đoán chất lượng dữ liệu)

  - **Data\_MoveDisabledReason -** Lỗi vô hiệu hóa thao tác di chuyển cho tài liệu

  - **Data\_MoveFlightEnabled -** Liệu chuyến bay cho tính năng di chuyển có được bật hay không

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu

  - **Data\_RenameFlightEnabled -** Liệu chuyến bay cho tính năng đổi tên có được bật hay không

#### <a name="officewordfilesaveactfconfirmsavedoccoreautorecoverysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreAutoRecoverySave

Sự kiện này cho biết Office Word lưu tài liệu tự động khôi phục chưa được lưu trước đó. Nó cho phép Microsoft phát hiện lỗi trong tự động phục hồi, điều này rất quan trọng đối với sự an toàn của dữ liệu tài liệu.

Sự kiện theo dõi xem thao tác tự động khôi phục lưu khi có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_DetachedDuration -** Thời gian hoạt động được tách ra từ chuỗi

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_Doc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_Doc\_WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data\_FailureClass -** Số nguyên thể hiện lớp lỗi cho các lỗi chuyển tiếp Dịch vụ Cộng tác Office (OCS)

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word.

  - **Data\_MoveFlightEnabled -** Liệu chuyến bay cho tính năng di chuyển có được bật hay không

  - **Data\_OCSSyncbackSaveStarted -** Cờ cho biết thao tác lưu này có liên quan đến việc lưu lại đồng bộ hóa

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu này

  - **Data\_RenameFlightEnabled -** Liệu chuyến bay cho tính năng đổi tên có được bật hay không

  - **Data\_SaveInitiateKind -** Số nguyên cho biết cách bắt đầu lưu

  - **Data\_SrcDocIsUnnamedOrNew -** Cho biết liệu tài liệu chúng tôi đang lưu có mới không

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Sự kiện này cho biết Office Word sẽ nhắc người dùng lưu các thay đổi khi cố gắng đóng tài liệu. Nó cho phép Microsoft theo dõi xem thao tác lưu khi thoát có hoạt động như mong đợi để tránh mất dữ liệu tài liệu hay không. Sự kiện theo dõi xem thao tác lưu khi thoát có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemRes -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_DetachedDuration -** Thời gian hoạt động được tách ra từ chuỗi

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_Doc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_Doc\_WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data\_DstDoc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_DstDoc\_EdpState – Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu đích-**

  - **Data\_DstDoc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v.) cho tài liệu đích

  - **Data\_DstDoc\_FileFormat -** Phiên bản giao thức định dạng tệp cho tài liệu đích

  - **Data\_DstDoc\_Location -** Cho biết dịch vụ nào sẽ cung cấp lưu trữ cho tài liệu đích (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_DstDoc\_LocationDetails -** Cho biết Thư mục đã biết cục bộ nào đã lưu trữ tài liệu đích

  - **Data\_DstDoc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_DstDoc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc cho tài liệu đích

  - **Data\_FailureClass -** Số nguyên thể hiện lớp lỗi với lỗi chuyển đổi OCS

  - **Data\_LocationPickerSaveStatus -** Giá trị số nguyên cho biết thao tác kích hoạt lưu từ hộp thoại lưu khi thoát

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word.

  - **Data\_MoveFlightEnabled -** Liệu chuyến bay cho tính năng di chuyển có được bật hay không

  - **Data\_OCSSyncbackSaveStarted -** Cờ cho biết thao tác lưu này có liên quan đến việc lưu lại đồng bộ hóa

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu này

  - **Data\_RenameFlightEnabled -** Liệu chuyến bay cho tính năng đổi tên có được bật hay không

  - **Data\_SaveInitiateKind -** Số nguyên cho biết cách bắt đầu lưu

  - **Data\_SrcDocIsUnnamedOrNew -** Cho biết liệu tài liệu chúng tôi đang lưu có mới không

#### <a name="officewordfilesavesaveassavefile"></a>Office.Word.FileSave.SaveAsSaveFile

Sự kiện này cho biết Office Word lưu tài liệu vào một tài liệu mới. Nó cho phép Microsoft phát hiện lỗi trong lưu - vì điều này rất quan trọng để tránh mất dữ liệu tài liệu. Sự kiện theo dõi xem quá trình lưu có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemRes -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_AddDocTelemResDst -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị từ xa liên quan đến tài liệu khác trong sự kiện cho tài liệu đích hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_AddDocTelemResSrc -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện cho tài liệu nguồn hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_DetachedDuration -** Thời gian hoạt động được tách ra từ chuỗi

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_Doc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_DstDoc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_DstDo\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu đích được mở trong chế độ đọc được hỗ trợ

  - **Data\_DstDoc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_DstDoc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu đích

  - **Data\_DstDoc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_DstDoc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_DstDoc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint cho tài liệu đích

  - **Data\_DstDoc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng cho tài liệu đích

  - **Data\_DstDoc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_DstDoc\_InitializationScenario -** Ghi lại cách tài liệu đích được mở

  - **Data\_DstDoc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở cho tài liệu đích

  - **Data\_DstDoc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng đích

  - **Data\_DstDoc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_DstDoc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_DstDoc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data\_DstDoc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu trên máy tính

  - **Data\_DstDoc\_Location -** Cho biết dịch vụ nào đã cung cấp lưu trữ cho tài liệu đích (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_DstDoc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_DstDoc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_DstDoc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt cho tài liệu đích

  - **Data\_DstDoc\_ReadOnlyReasons -** Lý do tại sao tài liệuđích được mở ở dạng chỉ đọc

  - **Data\_DstDoc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_DstDoc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_DstDoc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_DstDoc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_DstDoc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_DstDoc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_DstDoc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_DstDoc\_SizeInBytes -** Chỉ số kích thước tài liệu

  - **Data\_DstDoc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_DstDoc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_DstDoc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_DstDoc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc cho tài liệu đích

  - **Data\_DstDoc\_WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data\_FailureClass -** Số nguyên thể hiện lớp lỗi với lỗi chuyển đổi OCS

  - **Data\_LocationPickerPropagateToSaveTime,spLapsedMsec -** Đo thời gian, tính bằng mili giây, cần thiết để quá trình lưu kích hoạt sau khi nhận được kết quả từ bộ chọn vị trí

  - **Data\_LocationPickerSaveStatus -** Trạng thái được trả về bởi bộ chọn vị trí

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word

  - **Data\_MoveDisabledReason -** Lỗi vô hiệu hóa thao tác di chuyển cho tài liệu

  - **Data\_MoveFlightEnabled -** Liệu thao tác chống lại tính năng di chuyển có được bật hay không

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu này

  - **Data\_RenameFlightEnabled -** Liệu chuyến bay cho tính năng đổi tên có được bật hay không

  - **Data\_SaveInitiateKind -** Số nguyên cho biết cách bắt đầu lưu

  - **Data\_SrcDoc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_SrcDoc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_SrcDoc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_SrcDoc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu nguồn

  - **Data\_SrcDoc\_Ext -** Phần mở rộng tài liệu cho tài liệu nguồn (docx/xlsb/pptx, v.v.)

  - **Data\_SrcDoc\_FileFormat -** Phiên bản giao thức định dạng tệp cho tài liệu nguồn

  - **Data\_SrcDoc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint cho tài liệu nguồn

  - **Data\_SrcDoc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng cho tài liệu nguồn

  - **Data\_SrcDoc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_SrcDoc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_SrcDoc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_SrcDoc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_SrcDo\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_SrcDoc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_SrcDoc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data\_SrcDoc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu trên máy tính

  - **Data\_SrcDoc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu nguồn (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_SrcDoc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_SrcDoc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_SrcDoc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_SrcDoc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_SrcDoc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_SrcDoc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_SrcDoc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_SrcDoc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_SrcDoc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_SrcDoc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_SrcDoc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_SrcDoc\_SizeInBytes -** Chỉ số kích thước tài liệu

  - **Data\_SrcDoc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_SrcDoc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_SrcDoc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_SrcDoc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_SrcDoc\_WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data\_SrcDocIsUnnamedOrNew -** Cho biết liệu tài liệu chúng tôi đang lưu có mới không

#### <a name="officewordworddocumentdirtyflagchanged"></a>Office.Word.Word.DocumentDirtyFlagChanged

Sự kiện này cho biết Office Word chỉnh sửa tài liệu thay đổi trạng thái bên trong của tài liệu thành "rác". Nó cho phép Microsoft để đánh giá trạng thái tính năng của tài liệu chỉnh sửa. Sự kiện này là thông báo hoạt động của chỉnh sửa người dùng. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng.

Các trường sau đây sẽ được thu thập:

  - **Data\_CollectionTime-** Dấu thời gian của sự kiện

  - **Data\_DocumentLocation-** Loại vị trí tài liệu

  - **Data\_DocumentLocationDetails-** Loại con của vị trí tài liệu

  - **Data\_FAlwaysSaveEnabled-** Cho biết liệu tính năng luôn lưu có được bật hay không

  - **Data\_FirstEditTime-** Dấu thời gian của lần chỉnh sửa đầu tiên

  - **Data\_NumberCoAuthors-** Số lượng đồng tác giả chỉnh sửa tài liệu trong phiên

  - **Data\_NumberOfTimesDocumentDirtied-** Số lần chỉnh sửa được thực hiện cho tài liệu

  - **Data\_Pdod -** Mã định danh tài liệu trong quy trình Office Word

  - **Data\_UrlHash-** Hàm băm của đường dẫn tài liệu

  - **Data\_ViewKind-** Kiểu dạng xem Word

#### <a name="officevisiosharedfeatureexperimentation"></a>Office.Visio.Shared.FeatureExperimentation

Theo dõi tính năng chống lại người dùng. Sự kiện này giúp chúng tôi xác định thành công hay thất bại của việc chống lại tính năng.

Các trường sau đây sẽ được thu thập:

  - **Data\_Enable:bool**- True cho biết tính năng được bật cho người dùng hiện tại

  - **Data\_Feature:string** - Tên của tính năng

  - **Data\_Flighted:bool** - True cho biết tính năng được bật

  - **Data\_Licensed:bool** - True cho biết tính năng đang được kiểm tra cấp phép

  - **Data\_Subscriber:bool** - True cho biết người dùng có giấy phép đăng ký

#### <a name="officevisiosharedrefreshsmartdiagram"></a>Office.Visio.Shared.RefreshSmartDiagram

Ghi lại lỗi trong việc làm mới sơ đồ khi tệp được tạo thông qua DV. Điều này sẽ giúp chúng tôi gỡ lỗi các lỗi và sự cố trong làm mới dữ liệu trong sơ đồ DV.

Các trường sau đây sẽ được thu thập:

  - **Data\_ConnectorsBasedOnSequence:bool** - True nếu sơ đồ được làm mới ban đầu được tạo bằng cách sử dụng trình kết nối dựa trên tuỳ chọn trình tự"

  - **Data\_DialogError**:**string** - Li trong khi làm mới sơ đồ thông minh

  - **Data\_FileError:string** - chuỗi lỗi khi tệp Excel được kết nối không hợp lệ

  - **Data\_OverwriteSelected**:**bool** - True nếu người dùng chọn tùy chọn ghi đè lên sơ đồ trong khi làm mới

  - **Data\_WarningShown**:**bool** - True nếu có bất kỳ cảnh báo nào được hiển thị cho người dùng trong quá trình làm mới dữ liệu

#### <a name="officevisiosharedwritebacktoexcel"></a>Office.Visio.Shared.WritebackToExcel

Ghi lại lỗi ghi lại Excel khi tệp được tạo thông qua DV. Điều này sẽ giúp chúng tôi gỡ lỗi các lỗi và sự cố trong ghi lại Excel trong sơ đồ DV.

Các trường sau đây sẽ được thu thập:

  - **Data\_ConnectorsBasedOnSequence:bool** - True nghĩa là các trình kết nối được tạo dựa trên các thiết đặt trình tự

  - **Data\_DataSourceType:string** - Tệp này cho biết liệu sơ đồ được tạo từ "Bảng" hay "CustomRange"

  - **Data\_DialogError:string** - Loại lỗi tùy chỉnh trong khi tạo sơ đồ thông minh thông qua Excel

  - **Data\_NoOfShapesAdded:int** - Số lượng hình được thêm vào trong khi ghi lại chức năng Excel

  - **Data\_NoOfShapesDeleted:int** - Số lượng hình đã bị xóa trong khi ghi lại chức năng Excel

  - **Data\_OverwriteSelected:bool** - Tue cho biết người dùng đã chọn tùy chọn ghi đè dữ liệu

  - **Data\_SourceDataModified:bool** - True cho biết dữ liệu nguồn được sửa đổi

  - **Data\_WarningShown:bool** - True nghĩa là cảnh báo cập nhật dữ liệu được hiển thị cho người dùng

  - **Data\_WarningShownBecauseOfPresenceOfFormula:bool** - True cho biết cảnh báo hiển thị cho người dùng vì sự hiện diện của công thức trong Excel

  - **Data\_WarningShownToAddNextStepID:bool** - True cho biết cảnh báo hiển thị cho người dùng vì bước tiếp theo Định danh bị thiếu trong Excel

  - **Data\_WarningShownToConvertToTable:bool** - True cho biết cảnh báo được hiển thị cho người dùng để chuyển đổi dữ liệu Excel sang định dạng bảng

### <a name="application-status-and-boot-subtype"></a>*Trạng thái ứng dụng và kiểu con khởi động*

Xác định xem các sự kiện tính năng cụ thể đã xảy ra hay chưa, chẳng hạn như bắt đầu hoặc dừng và tính năng có đang hoạt động hay không.

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Ghi lại thông tin về việc tắt không mong muốn của Office. Điều này cho phép chúng tôi xác định sự cố hoặc tạm dừng sản phẩm để có thể xử lý chúng.

Các trường sau đây sẽ được thu thập:

  - **Data\_AirspaceInitTime:integer-** Thời gian để khởi tạo cấu phần irspace Office

  - **Data\_AllShapes:integer -** Số lượng hình trong tài liệu

  - **Data\_APIInitTime:integer -** Thời gian để khởi tạo mô-đun Visio API

  - **Data\_AppSizeHeight –** **-** Chiều dài cửa sổ bổ trợ

  - **Data\_AppSizeWidth –** **-** Chiều rộng cửa sổ bổ trợ

  - **Data\_AppURL -** URL của phần bổ trợ; Ghi nhật ký URL đầy đủ cho phần bổ trợ lưu trữ và tên miền URL cho phần bổ trợ không lưu trữ

  - **Data\_AuthorsCount:integer -** Số lượng tác giả đã chỉnh sửa tài liệu trong phiên này

  - **Data\_BackgroundPages:integer -** Số lượng trang nền trong sơ đồ

  - **Data\_BootTime:integer -** Lượng thời gian cần thiết để khởi động Visio

  - **Data\_Browser -** Chuỗi trình duyệt có thông tin về trình duyệt như loại, phiên bản

  - **Data\_ChildWindowMixedModeTime:integer -** Thời gian để bật chế độ hỗn hợp trong Visio (Cửa sổ con có thể có DpiAwarity khác nhau từ cửa sổ cha mẹ)

  - **Data\_CommentsCount:integer -** Số lượng chú thích trong tài liệu

  - **Data\_ConnectionCount:integer -** Số lượng kết nối dữ liệu trong sơ đồ

  - **Data\_ContentMgrInitTim:integer -** Thời gian để khởi tạo trình quản lý nội dung

  - **Data\_CreateMainFrameTime:integer -** Tạo thời gian máy tính chính

  - **Data\_CreatePaletteTime:integer -** Thời gian để tạo bảng màu toàn cầu

  - **Data\_DispFormatCount:integer -** Số lượng đồ họa dữ liệu trong sơ đồ

  - **Data\_Doc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_Fqdn:string -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_Doc\_FqdnHash:string -** Hàm băm của tài liệu được lưu trữ

  - **Data\_Doc\_IsIncrementalOpen:bool-** : Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không?

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked:bool-** True khi đây là tài liệu máy chủ tồn tại cục bộ và được đồng bộ hóa với máy chủ (ví dụ: thông qua ứng dụng máy khách OneDrive hoặc ODB)

  - **Data\_Doc\_Location:long-** : Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_Doc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive

  - **Data\_Doc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_Doc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_Doc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_Doc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ) 

  - **Data\_Doc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_DpiAwarenessTime:integer -** Thời gian thực hiện để kích hoạt nhận thức về Dpi trên mỗi màn hình

  - **Data\_DurationToCompleteInMilliseconds:double-** Khoảng thời gian để hoàn thành quá trình lưu dưới dạng tính bằng mili giây

  - **Data\_ErrorCode:int -** : 0 là thành công, số nguyên là thất bại trong quá trình lưu

  - **Data\_FailureReason:integer -** lý do lỗi lưu không đồng bộ

  - **Data\_FileExtension -** Phần mở rộng tệp của sơ đồ đã mở

  - **Data\_FileHasDGMaster:bool -** True khi tệp có Đồ họa dữ liệu

  - **Data\_FileHasImportedData:bool -** True khi tệp nhập dữ liệu

  - **Data\_FileHasShapesLinked:bool -** True khi tệp có hình được liên kết với dữ liệu

  - **Data\_FileIOBytesRead:int -** Tổng số byte đọc trong khi lưu

  - **Data\_FileIOBytesReadSquared:int -** Giá trị bình phương của dữ liệu\_FileIOBytesRead

  - **Data\_FileIOBytesWritten:int -** Tổng số byte được ghi trong khi lưu

  - **Data\_FileIOBytesWrittenSquared:int-** Giá trị bình phương của dữ liệu\_FileIOBytesWritten

  - **Data\_FilePathHash:binary** - Hàm băm nhị phân của đường dẫn tệp

  - **Data\_FilePathHash: binary** - GUID cho đường dẫn tệp

  - **Data\_FileSize -** Kích cỡ tài liệu tính bằng byte

  - **Data\_ForegroundPages:integer -** Số lượng trang mặt trước trong sơ đồ

  - **Data\_ForegroundShapes:integer -** Số nguyên hình trong các trang mặt trước

  - **Data\_GdiInitTime:integer -** Thời gian để khởi tạo mô-đun GDI API

  - **Data\_HasCoauthUserEdit:bool -** True nếu tài liệu được chỉnh sửa trong phiên đồng tác giả

  - **Data\_HasCustomPages:bool -** True nếu tài liệu chứa các trang tùy chỉnh

  - **Data\_HasCustPatterns:bool -** True nếu tệp có mẫu tùy chỉnh

  - **Data\_HasDynConn:bool -** True nếu tài liệu chứa kết nối động

  - **Data\_HasScaledPages:bool -** True nếu tài liệu chứa các trang co giãn

  - **Data\_HasUserWaitTime:bool -** True khi hộp thoại tập tin được hiển thị trong khi lưu

  - **Data\_InitAddinsTime:integer -** Thời gian để khởi tạo và tải Thêm COM

  - **Data\_InitBrandTime:integer -** Lượng thời gian cần thiết để khởi tạo màn hình nhấp nháy và thương hiệu các cấu phần Office

  - **Data\_InitGimmeTime:integer -** Thời gian để khởi tạo cấu phần Office

  - **Data\_InitLicensingTime:integer -** Thời gian để khởi tạo cấp phép cấu phần Office

  - **Data\_InitMsoUtilsTime:integer -** Thời gian khởi tạo cấu phần Office MSOUTILS

  - **Data\_InitPerfTime:integer -** Thời gian thực hiện khởi tạo cấu phần Office

  - **Data\_InitTCOTime:integer -** Lượng thời gian cần thiết để khởi tạo trình quản lý cấu phần Office

  - **Data\_InitTrustCenterTime:integer -** Thời gian để khởi tạo trung tâm tin cậy cấu phần Office

  - **Data\_InitVSSubSystemsTime:integer -** Lượng thời gian cần thiết để khởi tạo trình quản lý cấu phần Visio

  - **Data\_InternalFile:bool -** True nếu tệp là một tệp nội bộ. Ví dụ: mẫu tô

  - **Data\_IsAsyncSave:bool -** True nếu lưu không đồng bộ

  - **Data\_IsAutoRecoveredFile:bool -** True nếu tệp được tự động khôi phục

  - **Data\_IsEmbedded:bool -** True nếu tệp Visio được nhúng trong một ứng dụng khác

  - **Data\_IsInfinitePageDisabledForAllPages:bool -** True nếu Trang vô hạn bị vô hiệu hóa cho tất cả các trang của tài liệu

  - **Data\_IsIRMProtected:bool -** True nếu tệp được bảo vệ Quyền Thông tin

  - **Data\_IsLocal:bool -** True nếu tệp là tệp cục bộ

  - **Data\_IsRecoverySave:bool -** True nếu an toàn được kích hoạt do quá trình khôi phục

  - **Data\_IsShapeSearchPaneHiddenState:bool -** True nếu ngăn tìm kiếm hình bị ẩn cho tài liệu

  - **Data\_IsSmartDiagramPresentInActivePageOfFile:bool -** bool, true nếu sơ đồ trực quan dữ liệu thông minh có trong trang hoạt động của tệp

  - **Data\_IsSmartDiagramPresentInFile:bool -** bool, true nếu sơ đồ trực quan dữ liệu thông minh có trong tệp.

  - **Data\_IsUNC:bool -** True nếu đường dẫn tài liệu tuân thủ Công ước đặt tên chung

  - **Data\_LandscapePgCount:integer -** Số lượng trang có hướng ngang trong sơ đồ

  - **Data\_Layers:integer -** Số lớp trong sơ đồ

  - **Data\_LoadProfileTime:integer -** Lượng thời gian cần thiết để tải hồ sơ Office

  - **Data\_LoadRichEditTim:integer-** Thời gian tải cấu phần chỉnh sửa đa dạng

  - **Data\_LoadVisIntlTime:integer -** Thời gian để tải DLL Quốc tế của Visio

  - **Data\_Location:integer -** Vị trí của tệp mà nó được mở 0 - Cục bộ 1 - Mạng, 2 - SharePoint, 3 - Web

  - **Data\_MasterCount:integer -** Số lượng bản cái trong sơ đồ

  - **Data\_MaxCoauthUsers:integer -** Số lượng người dùng tối đa đồng tác giả tại bất kỳ thời điểm nào trong phiên Filesystem, Registry, First Party, SDX

  - **Data\_MaxTilesAutoSizeOn:integer -** Số lượng ô tối đa của trang được bật kích thước tự động

  - **Data\_MsoBeginBootTime:integer -** Thời gian khởi động MSO

  - **Data\_MsoDllLoadTime:integer -** Thời gian tải MSO DLL

  - **Data\_MsoEndBootTime:integer -** Thời gian kết thúc khởi động MSO

  - **Data\_MsoInitCoreTime:integer -** Thời gian khởi tạo cấu phần MSO Office

  - **Data\_MsoInitUITime:integer -** Thời gian để khởi tạo giao diện người dùng cấu phần MSO Office

  - **Data\_MsoMigrateTime:integer -** Thời gian để di chuyển cài đặt người dùng khi khởi động lần đầu tiên nếu người dùng nâng cấp từ phiên bản trước

  - **Data\_NetworkIOBytesRead:int -** Tổng số byte đọc trong khi lưu

  - **Data\_NetworkIOBytesReadSquared:int -** Giá trị bình phương của dữ liệu\_NetworkIOBytesRead

  - **Data\_FileIOBytesWritten:int -** Tổng số byte được ghi trong khi lưu

  - **Data\_FileIOBytesWrittenSquared:int-** Giá trị bình phương của NetworkIOBytesWritten

  - **Data\_OartStartupTime:integer -** Thời gian để khởi tạo cấu phần OART Office

  - **Data\_OleInitTime:integer -** Thời gian thực hiện khởi tạo cấu phần OLE Office

  - **Data\_OpenDurationTimeInMs:integer -** Khoảng thời gian để mở tệp tính bằng mili giây

  - **Data\_OriginatedFromTemplateID:integer -** Mã định danh cho mẫu mà từ đó sơ đồ đã được tạo. NULL cho các mẫu của bên thứ ba

  - **Data\_Pages:integer -** Số lượng trang trong tài liệu

  - **Data\_PositionToolbarsTime:integer -** Thời gian để đưa các thanh công cụ vào vị trí

  - **Data\_ReadOnly:bool -** True nếu tệp ở chế độ chỉ đọc

  - **Data\_RecordSetCount:integer -** Số lượng bản ghi được thiết lập trong sơ đồ

  - **Data\_RecoveryTime:integer -** Thời gian để mở tệp khôi phục

  - **Data\_ReviewerPages:integer -** Số lượng trang người đánh giá trong sơ đồ

  - **Data\_RibbonTime:integer -** Thời gian để hiển thị thanh trạng thái

  - **Data\_RoamingSettingsStartupTime:integer -** Thời gian tạo và tải tất cả các thiết đặt Visio hiện được chuyển vùng

  - **Data\_SchemeMgrStartupTime:integer -** Thời gian để khởi tạo trình quản lý lược đồ

  - **Data\_SDX\_AssetId -** CHỈ tồn tại cho các phần bổ trợ lưu trữ. OMEX cung cấp phần bổ trợ trong một AssetId khi nhập vào Store

  - **Data\_SDX\_BrowserToken -** Mã định danh nằm trong bộ đệm ẩn của trình duyệt

  - **Data\_SDX\_HostJsVersion -** Đây là phiên bản dành riêng cho nền tảng của Office.js (ví dụ: Outlook web16.01.js) Phần này chứa bề mặt API cho phần bổ trợ.

  - **Data\_SDX\_Id -** GUID của phần bổ trợ duy nhất xác định nó 

  - **Data\_SDX\_InstanceId -** Thể hiện cặp tài liệu Phần bổ trợ

  - **Data\_SDX\_MarketplaceType -** Cho biết nơi Phần bổ trợ được cài đặt

  - **Data\_SDX\_OfficeJsVersion -** Đây là phiên bản Office.js sẽ chuyển hướng đến phiên bản cụ thể của nền tảng.

  - **Data\_SDX\_Version -** Phiên bản của phần bổ trợ

  - **Data\_ShellCmdLineTime:integer -** Thời gian dành để phân tích và thực hiện bất kỳ lệnh shell nào trên dòng lệnh

  - **Data\_Size:long** - Kích cỡ tệp tính bằng byte

  - **Data\_StartEndTransactionTime:integer -** Thời gian để khởi tạo các cấu phần Visio

  - **Data\_STNInitTime:integer -** Thời gian khởi tạo cấu hình cửa sổ mẫu tô

  - **Data\_Tag:string -** Mã định danh duy nhất để xác định sự kiện Lưu dưới dạng

  - **Data\_ThemeCount:integer -** Số lượng chủ đề trong sơ đồ

  - **Data\_TimeStamp -** Dấu thời gian khi tài liệu được đóng lại

  - **Data\_UIInitTime:integer -** Thời gian khởi tạo giao diện người dùng

  - **Data\_WasSuccessful:bool -** True nếu quá trình lưu dưới dạng được thực hiện thành công

  - **Data\_WinLaunchTime:integer -** Thời gian để khởi chạy ngăn khởi động Visio, v.v.)

  - **Office.Visio.FileCharacteristicsVisio -** Ghi lại các thuộc tính tệp tại thời điểm tệp khởi động dành cho Visio C2R và Dev16. Sự kiện này giúp chúng tôi phân loại và gỡ lỗi các lỗi về thuộc tính tài liệu, từ đó cho phép chúng tôi truy ra được nguyên nhân nhanh hơn và khắc phục sự cố để đạt được sự hài lòng khách hàng.

  - **Office.Visio.Shared.BootStats -** Sự kiện này sẽ thu thập thời gian khởi động cho ứng dụng Visio Win32. Nó thu thập các trường khác nhau để khởi động các thành phần khác nhau như thời gian tải Ribbon, thời gian khởi tạo ứng dụng. Sự kiện này được sử dụng để đo hiệu suất khởi động cho Visio.

  - **Office.Visio.Shared.FileOpen -** Sự kiện này thu thập số liệu thống kê Mở tệp cho Visio. Sự kiện này được sử dụng để theo dõi tỷ lệ mở thành công/thất bại của mở tệp và ánh xạ nó với một vài thuộc tính như kích thước tệp. Thuộc tính tệp cho phép chúng tôi gỡ lỗi và truy ra được nguyên nhân nhanh hơn.

  - **Office.Visio.Shared.Filesave -** Sự kiện này thu thập số liệu thống kê Lưu tệp cho Visio. Sự kiện này được sử dụng để theo dõi tỷ lệ mở thành công/thất bại của lưu tệp và ánh xạ nó với một vài thuộc tính như kích thước tệp và vị trí mà nó đang được lưu, ví dụ: đám mây/cục bộ. Thuộc tính tệp cho phép chúng tôi gỡ lỗi và truy ra được nguyên nhân nhanh hơn.

  - **Office.Visio.Shared.FilesaveAs -** Sự kiện này thu thập số liệu thống kê Lưu tệp cho Visio. Sự kiện này được sử dụng để theo dõi tỷ lệ mở thành công/thất bại của lưu tệp và ánh xạ nó với một vài thuộc tính như kích thước tệp và vị trí mà nó đang được lưu, ví dụ: đám mây/cục bộ. Thuộc tính tệp cho phép chúng tôi gỡ lỗi và truy ra được nguyên nhân nhanh hơn.

  - **Office.Visio.Shared.PostSave -** Sự kiện này ghi lại các nguyên nhân gây ra lỗi trong lưu tệp.

  - **Office.Visio.Shared.FilesaveAs -** Sự kiện này thu thập số liệu thống kê Lưu tệp dưới dạng cho Visio Dev16. Sự kiện này được sử dụng để theo dõi tỷ lệ mở thành công/thất bại của lưu tệp dưới dạng và ánh xạ nó với một vài thuộc tính như kích thước tệp và vị trí mà nó đang được lưu, ví dụ: đám mây/cục bộ. Thuộc tính tệp cho phép chúng tôi gỡ lỗi và truy ra được nguyên nhân nhanh hơn.

  - **Office.Visio.VisioFileSaveAsync -** Sự kiện này thu thập số liệu thống kê lưu tệp không đồng bộ cho Visio Dev16. Sự kiện này được sử dụng để theo dõi tỷ lệ mở thành công/thất bại của lưu tệp không đồng bộ và ánh xạ nó với một vài thuộc tính như kích thước tệp và vị trí mà nó đang được lưu, ví dụ: đám mây/cục bộ. Thuộc tính tệp cho phép chúng tôi gỡ lỗi và truy ra được nguyên nhân nhanh hơn.

  - **Office.Visio.VisioFileSaveAsync -** Sự kiện này thu thập số liệu thống kê Lưu tệp đồng bộ cho Visio Dev16. Sự kiện này được sử dụng để theo dõi tỷ lệ mở thành công/thất bại của lưu tệp đồng bộ và ánh xạ nó với một vài thuộc tính như kích thước tệp và vị trí mà nó đang được lưu, ví dụ: đám mây/cục bộ. Thuộc tính tệp cho phép chúng tôi gỡ lỗi và truy ra được nguyên nhân nhanh hơn. Sự kiện này giúp chúng tôi theo dõi lưu lý do lỗi của một tệp.

#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Thu thập PUID người dùng và mã định danh đối thuê một lần mỗi phiên. Sự tương quan giữa PUID và đối tượng thuê là yếu tố cần thiết để hiểu và chẩn đoán các sự cố về Outlook trên cơ sở mỗi đối tượng thuê.

Các trường sau đây sẽ được thu thập:

  - **CollectionTime** Dấu thời gian của sự kiện

  - **ConnId** - Mã định danh kết nối: Mã định danh của kết nối phân tích PUID và mã định danh đối tượng thuê OMS

  - **OMSTenantId** – Mã định danh duy nhất do Microsoft tạo của đối tượng thuê

  - **PUID** - PUID của Exchange PUID để nhận dạng riêng người dùng

#### <a name="officepowerpointpptdesktopbootime"></a>Office.PowerPoint.PPT.Desktop.Bootime

Thu thập cách PowerPoint được khởi động. Nó bao gồm việc khởi động PowerPoint trong dạng xem được bảo vệ, trong chế độ đọc được hỗ trợ, từ Macro, in, tài liệu mới và trống, khôi phục tài liệu, từ tự động hóa và nếu nó là click- to-run. Nó cũng thu thập thời gian để PowerPoint khởi động. Dữ liệu này rất quan trọng để đảm bảo PowerPoint hoạt động tốt khi được khởi động từ các chế độ khác nhau. Microsoft sử dụng dữ liệu này để phát hiện thời gian khởi động dài khi mở PowerPoint từ các chế độ khác nhau.

Các trường sau đây sẽ được thu thập:

  - **AssistedReading -** ở chế độ đọc hỗ trợ

  - **Automation -** từ tự động hóa

  - **Benchmark -** chạy tiêu chuẩn hiệu suất

  - **Blank -** Tài liệu trống.

  - **BootTime -** Thời gian khởi động phiên

  - **Embedding -** Tài liệu nhúng

  - **IsC2R -** ở chế độ click-to-run

  - **IsNew -** Tài liệu mới

  - **IsOpen -** đang mở

  - **Macro1 -** chạy Macro

  - **Macro2 -** chạy Macro

  - **NonStandardSpaceInCmdLine** – Có khoảng trống không tiêu chuẩn trong dòng lệnh

  - **Print -** in tài liệu

  - **PrintDialog -** in tài liệu với hộp thoại

  - **PrintPrinter -** in tài liệu bằng máy in

  - **ProtectedView -** trong dạng xem được bảo vệ

  - **RegServer -** Đăng ký PowerPoint dưới dạng một máy chủ COM

  - **Restore -** Khôi phục tài liệu

  - **Show -** Hiển thị tài liệu

  - **Time -** Thời gian của phiên

  - **ProtectedView -** trong dạng xem được bảo vệ

#### <a name="officepowerpointppthasuserediteddocument"></a>Office.PowerPoint.PPT.HasUserEditedDocument

Thu thập khi người dùng bắt đầu chỉnh sửa tài liệu. Microsoft sử dụng dữ liệu này để tính toán người dùng hoạt động đã chỉnh sửa tài liệu PowerPoint

Các trường sau đây sẽ được thu thập:

  - **CorrelationId** – Mã định danh tương quan tài liệu

#### <a name="officeprojectbootandopenproject"></a>Office.Project.BootAndOpenProject

Project khởi động bằng cách mở một tệp. Sự kiện này cho biết rằng người dùng đã mở Office Project với một tệp được liên kết. Nó chứa dữ liệu thành công quan trọng của việc đảm bảo Project có thể bắt đầu và tải một tệp.

Các trường sau đây sẽ được thu thập:

  - **Data\_AlertTime -** Lượng thời gian hộp thoại khởi động được kích hoạt.

  - **Data\_BootTime -** Lượng thời gian cần thiết để khởi động Project

  - **Data\_CacheFileSize -** Nếu tệp được lưu trữ, kích cỡ tệp

  - **Data\_EntDocType -** Loại tệp đã được mở

  - **Data\_IsInCache -** Liệu tệp đã mở có được vào bộ đệm ẩn hay không

  - **Data\_LoadSRAs -** Người dùng có muốn tải SRA hay không

  - **Data\_Outcome -** Tổng thời gian khởi động và mở tệp.

  - **Data\_OpenFromDocLib -** Nếu tệp Project được mở là từ thư viện tài liệu

  - **Data\_ProjectServerVersion -** Phiên bản và bản dựng mà Project hiện đang bật

#### <a name="officeprojectbootproject"></a>Office.Project.BootProject

Project khởi động mà không cần mở một tệp. Sự kiện này cho biết rằng người dùng đã mở Office Project mà không cần một tệp được liên kết. Nó chứa dữ liệu thành công quan trọng của việc đảm bảo Project có thể bắt đầu.

Các trường sau đây sẽ được thu thập:

  - **Data\_BootTime -** Lượng thời gian cần thiết để khởi động Project

  - **Data\_FileLoaded -** False nếu mở từ ngoài khoảng trống hoặc Project trống mới

  - **Data\_IsEntOfflineWithProfile -** Nếu người dùng ở trong SKU chuyên nghiệp và không được kết nối với máy chủ

  - **Data\_IsEntOnline -** Nếu phiên Project được kết nối với máy chủ Project có tính năng doanh nghiệp

  - **Data\_IsLocalProfile -** Nếu phiên Project được kết nối với máy chủ Project có tính năng doanh nghiệp

  - **Data\_ProjectServerVersion -** Phiên bản và bản dựng mà Project hiện đang bật

#### <a name="officepowerpointdocoperationopen"></a>Office.PowerPoint.DocOperation.Open 

Thu thập bất cứ khi nào PowerPoint mở ra một tệp. Chứa thông tin thành công, chi tiết lỗi, số liệu về hiệu suất và chi tiết cơ bản về tệp bao gồm loại định dạng tệp và siêu dữ liệu tài liệu. Thông tin này là cần thiết để đảm bảo PowerPoint có thể mở tệp thành công mà không làm giảm hiệu suất. Nó cho phép chúng tôi chẩn đoán bất kỳ vấn đề nào mà chúng tôi khám phá.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemetryResult -** Mục nhập nhật ký này có tất cả các phép đo từ xa tài liệu cần thiết hay không (Các trường Dữ liệu\_Doc\_\*)

  - **Data\_AddDocumentToMruList -** Đo khoảng thời gian thực hiện AddDocumentToMruList

  - **Data\_AlreadyOpened -** Tài liệu này có được mở trước đó không (trong bối cảnh của cùng một phiên quy trình)

  - **Data\_AntiVirusScanMethod -** Tập hợp các giá trị được xác định trước của loại chống vi-rút được quét (IOAV, AMSI, Không, v.v.)

  - **Data\_AntiVirusScanStatus -** Tập hợp các giá trị quét vi-rút được xác định trước xảy ra cho mọi tài liệu được mở (NoThreatDetected, Không thành công, MalwareDetected, v.v.)

  - **Data\_AsyncOpenKind -** Tập hợp các giá trị được xác định trước của các tùy chọn không đồng bộ (Cộng tác, ServerOnly, SyncBacked, NotAsync)

  - **Data\_CancelBackgroundDownloadHr -** Việc tải xuống tài liệu có bị gián đoạn không? Nếu có, kết quả của sự gián đoạn là gì?

  - **Data\_CheckForAssistedReadingReasons -** Khoảng thời gian thực hiện phương pháp CheckForAssistedReadingReasons tính bằng mili giây

  - **Data\_CheckForDisabledDocument -** Khoảng thời gian thực hiện phương pháp CheckForDisablesDocument tính bằng mili giây

  - **Data\_CheckForExistingDocument -** Khoảng thời gian thực hiện phương pháp CheckForExistingDocument tính bằng mili giây

  - **Data\_CheckIncOpenResult -** Khoảng thời gian thực hiện phương pháp CheckIncOpenResult tính bằng mili giây

  - **Data\_CheckLambdaResult -** Khoảng thời gian thực hiện phương pháp CheckLambdaResult tính bằng mili giây

  - **Data\_CheckPackageForRequiredParts -** Khoảng thời gian thực hiện phương pháp CheckPackageForRequiredParts tính bằng mili giây

  - **Data\_CheckPackageForSpecialCases -** Khoảng thời gian thực hiện phương pháp CheckPackageForSpecialCases tính bằng mili giây

  - **Data\_CheckRequiredPartsLoaded -** Khoảng thời gian thực hiện phương pháp CheckRequiredPartsLoaded tính bằng mili giây

  - **Data\_CheckWebSharingViolationForIncOpen -** Khoảng thời gian thực hiện phương pháp CheckWebSharingViolationForIncOpen tính bằng mili giây

  - **Data\_ContentTransaction -** Tập hợp các giá trị được xác định trước khi giao dịch có thể được tạo (AllowedOnLoadDocument, AllowedOnOpenComplete, v.v.)

  - **Data\_CppUncaughtExceptionCount:long -** Không theo kịp ngoại lệ riêng trong khi hoạt động đang chạy

  - **Data\_CreateDocumentTimeMS -** Khoảng thời gian thực hiện phương pháp CreateDocumentTimeMS tính bằng mili giây

  - **Data\_CreateDocumentToken -** Khoảng thời gian thực hiện phương pháp CreateDocumentToken tính bằng mili giây

  - **Data\_CreateDocumentToW -** Khoảng thời gian thực hiện phương pháp CreateDocumentToW tính bằng mili giây

  - **Data\_CreateDocumentToW -** Khoảng thời gian thực hiện phương pháp CreateDocWindow tính bằng mili giây

  - **Data\_CreateLocalTempFile -** Khoảng thời gian thực hiện phương pháp CreateLocalTempFile tính theo mili giây

  - **Data\_DetachedDuration:long -** Thời gian mà hoạt động bị tách ra/không chạy

  - **Data\_DetermineFileType -** Khoảng thời gian thực hiện phương pháp DetermineFileType tính theo mili giây

  - **Data\_Doc\_AccessMode:long -** Cách tài liệu này đã được mở (Chỉ đọc/đọc ghi)

  - **Data\_Doc\_AssistedReadingReasons:long -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType:long -** Cách tài liệu được lưu trữ trong SharePoint

  - **Data\_Doc\_EdpState:long -** Trạng thái Bảo vệ Dữ liệu Doanh nghiệp của tài liệu

  - **Data\_Doc\_Ext:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_Extension:string -** Phần mở rộng tài liệu

  - **Data\_Doc\_FileFormat:long -** Tập hợp các giá trị định dạng của tệp được xác định trước (chi tiết hơn so với phần mở rộng)

  - **Data\_Doc\_Fqdn:string – -** Nơi tài liệu được lưu trữ (SharePoint.com, live.net), chỉ khả dụng cho các tên miền của Office 365

  - **Data\_Doc\_FqdnHash:string – -** Hàm băm của tài liệu được lưu trữ

  - **Data\_Doc\_IdentityTelemetryId:string – -** GUID duy nhất của người dùng

  - **Data\_Doc\_IdentityUniqueId:string -** Mã định danh duy nhất của danh tính được sử dụng cho thao tác Tài liệu dùng chung

  - **Data\_Doc\_IOFlags:long -** Bitmask cho các cờ liên quan đến IO khác nhau cho một tài liệu nhất định

  - **Data\_Doc\_IrmRights:long -** Tập hợp các giá trị được xác định trước về loại Quản lý Quyền Thông tin được áp dụng trên tài liệu này (Chuyển tiếp, trả lời, SecureReader, Chỉnh sửa, v.v.)

  - **Dữ liệu\_tài liệu\_IsCloudCollabEnabled:bool -** True nếu tiêu đề HTTP "IsCloudCollabEnables" đã được nhận từ yêu cầu TÙY CHỌN.

  - **Data\_Doc\_IsIncrementalOpen:bool – -** : Tài liệu đã được mở tăng dần (tính năng mới mở tài liệu mà không cần tải xuống toàn bộ tài liệu)

  - **Data\_Doc\_IsOcsSupported:bool -** Tài liệu có hỗ trợ đồng tác giả bằng dịch vụ OCS mới hay không

  - **Data\_Doc\_IsOpeningOfflineCopy:bool -** Tài liệu có đang được mở từ bộ nhớ đệm ẩn cục bộ hay không?

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked:bool -** Tài liệu được mở từ thư mục đang sử dụng ứng dụng đồng bộ OneDrive

  - **Data\_Doc\_Location:long -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Cục bộ, SharePoint, WOPI, Mạng, v.v.)

  - **Data\_Doc\_LocationDetails:long -** Bộ giá trị được xác định trước của vị trí chi tiết hơn (thư mục Temp, thư mục tải xuống, Tài liệu One Drive, Hình ảnh One Drive, v.v)

  - **Data\_Doc\_NumberCoAuthors:long -** Số lượng đồng tác giả tại thời điểm mở tài liệu

  - **Data\_Doc\_PasswordFlags:long -** Tập hợp các giá trị được xác định trước về cách tài liệu được mã hóa bằng mật khẩu (Không có, mật khẩu để đọc, mật khẩu để chỉnh sửa)

  - **Data\_Doc\_ReadOnlyReasons:long –-** Tập hợp giá trị được xác định trước về lý do tại sao tài liệu này được đánh dấu là chỉ đọc (Được khóa trên máy chủ, tài liệu cuối cùng, mật khẩu được bảo vệ để chỉnh sửa, v.v.)

  - **Data\_Doc\_ResourceIdHash:string -** Hàm băm của mã định danh nguồn cho các tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_ServerDocId:string -** Mã định biến không thể thay đổi cho các tài liệu được lưu trữ trên đám mây 

  - **Data\_Doc\_ServerProtocol:long -** Tập hợp các giá trị được xác định trước của giao thức được sử dụng để giap tiếp với máy chủ (http, Cobalt, WOPI, v.v.)

  - **Data\_Doc\_ServerType:long -** Tập hợp các giá trị được xác định trước của loại máy chủ (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long -** Máy chủ có dựa trên Office14, Office15, Office 16 không?

  - **Data\_Doc\_SessionId:long -** GUID được tạo xác định phiên bản của tài liệu trong cùng một phiên quy trình

  - **Data\_Doc\_SharePointServiceContext:string -** Một chuỗi mờ, điển hình là GridManagerID.FarmID. Hữu ích cho việc tương quan nhật ký phía máy khách và phía máy chủ

  - **Data\_Doc\_SizeInBytes:long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_Doc\_SpecialChars:long -** Bitmask dài biểu thị các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StorageProviderId:string -** Chuỗi xác định nhà cung cấp lưu trữ của tài liệu, như "DropBox”

  - **Data\_Doc\_StreamAvailability:long-** Tập hợp các giá trị trạng thái của luồng tài liệu được xác định trước (có sẵn, bị vô hiệu hóa vĩnh viễn, không khả dụng)

  - **Data\_Doc\_UrlHash:string -** Hàm băm của URL đầy đủ của tài liệu được lưu trữ trên đám mây

  - **Data\_Doc\_UsedWrsDataOnOpen:bool -** True nếu tệp được mở tăng dần bằng cách sử dụng dữ liệu WRS được lưu trước trong bộ nhớ đệm ẩn trên máy chủ

  - **Data\_Doc\_WopiServiceId:string -** Mã định danh dịch vụ WOPI, ví dụ: "Dropbox"

  - **Data\_DownloadExcludedData -** Khoảng thời gian thực hiện phương pháp DownloadExcludedData tính theo mili giây

  - **Data\_DownloadExcludedDataTelemetry -** Tập hợp giá trị được xác định trước của trạng thái chờ đồng bộ hóa để tải xuống (SynousLogicHit, UserCancelling RunModalTaskUnazedHResult, v.v.)

  - **Data\_DownloadFileInBGThread -** Khoảng thời gian thực hiện phương pháp DownloadFileInBGThread tính theo mili giây

  - **Data\_DownloadFragmentSize -** Kích cỡ của đoạn (đoạn có thể tải xuống của tệp), thường là 3,5 MB

  - **Data\_ExcludedEmbeddedItems -** Số phần zip được loại trừ cho lần kết xuất đầu tiên

  - **Data\_ExcludedEmbeddedItemsSize -** Tổng kích thước của các phần zip được loại trừ cho lần kết xuất đầu tiên

  - **Data\_ExcludedRequiredItems -** Số phần zip được loại trừ cho lần kết xuất đầu tiên

  - **Data\_ExcludedRequiredItemsSize -** Tổng kích thước của các phần zip được loại trừ cho lần kết xuất đầu tiên

  - **Data\_ExecutionCount -** Số lần giao thức IncOpen được thực thi

  - **Data\_FailureComponent:long -** Tập hợp các giá trị được xác định trước của cấu phần khiến giao thức này bị lỗi? (Xung đột, CSI, Nội bộ, v.v..)

  - **Data\_FailureReason:long -** Tập hợp các giá trị được xác định trước về nguyên nhân lỗi (FileIsCorrupt, BlockedByAntillin, v.v.)

  - **Data\_FCreateNew -** Đây có phải là tài liệu trống mới không

  - **Data\_FCreateNewFromTemplate -** Đây có phải là tài liệu mới từ các mẫu không

  - **Data_FErrorAfterDocWinCreation:boolean-** Có bất kỳ lỗi hoặc ngoại lệ nào xảy ra sau khi cửa sổ tài liệu được tạo ra không.

  - **Data\_FileUrlLocation -** Tập hợp các giá trị được xác định trước về nơi lưu trữ tài liệu (Network Share, Local Drive, ServerOther, v.v.)

  - **Data\_FirstSlideCompressedSize -** kích cỡ được nén của phần zip trang chiếu đầu tiên (thường là Slide1.xml)

  - **Data\_FIsDownloadFileInBgThreadEnabled -** Tải xuống trong chuỗi hội thoại nền có được bật không?

  - **Data\_fLifeguarded:bool -** Tài liệu đã được bảo vệ chưa (tính năng tự sửa lỗi tài liệu mà không cần nhắc người dùng)?

  - **Data\_ForceReopenOnIncOpenMergeFailure -** Cờ đại diện nếu chúng tôi buộc phải mở lại do lỗi phối trong Inc Open

  - **Data\_ForegroundThreadPass0TimeMS -** (Chỉ dành cho máy Mac) Tổng thời gian dành cho chuỗi hội thoại mặt trước trong lượt đi đầu tiên

  - **Data\_ForegroundThreadPass1TimeMS -** (Chỉ dành cho máy Mac) Tổng thời gian dành cho chuỗi hội thoại mặt trước trong lượt đi thứ hai

  - **Data\_FWebCreatorDoc -** Tài liệu được tạo từ mẫu hoặc Trình bắt đầu nhanh

  - **Data\_HasDocToken -** Tài liệu này có mã thông báo tài liệu CSI (mã nội bộ) không

  - **Data\_HasDocument -** Tài liệu này có tài liệu CSI (mã nội bộ) không

  - **Data\_InclusiveMeasurements -** Các khoảng thời gian đo phương thức có bao gồm khoảng thời gian gọi phương thức con hay không

  - **Data\_IncompleteDocReasons -** Tập hợp các giá trị được xác định trước về lý do mở không đầy đủ (Unknown, DiscardFailure, v.v.)

  - **Data\_IncOpenDisabledReasons -** Tập hợp các giá trị được xác định trước vê lý do tại sao mở tăng dần bị vô hiệu hóa

  - **Data\_IncOpenFailureHr -** Kết quả của lý do tại sao mở lũy kế không thành công

  - **Data\_IncOpenFailureTag -** Thẻ (con trỏ tới vị trí mã) của nơi mở lũy kế không thành công

  - **Data\_IncOpenFallbackReason -** Lý do tại sao IncOpen không chạy

  - **Data\_IncOpenRequiredTypes -** Tập hợp các giá trị được xác định trước của các loại nội dung cần thiết cho kết xuất đầu tiên (requiredXmlZipItem, requiredNotesMaster, v.v.)

  - **Data\_IncOpenStatus -** Tập hợp các giá trị được xác định trước của trạng thái mở lũy kế (Attempted, FoundExcludedItems, DocIncOpenInfoCreated, v.v.)

  - **Data\_InitFileContents -** Khoảng thời gian thực hiện phương pháp InitFileContents tính theo mili giây

  - **Data\_InitialExcludedItems -** Số phần zip được loại trừ cho lần kết xuất đầu tiên

  - **Data\_InitialExcludedItemsSize -** Tổng kích thước của các phần zip được loại trừ ban đầu

  - **Data\_InitializationTimeMS -** (Chỉ dành cho máy Mac) Thời gian khởi tạo

  - **Data\_InitialRoundtripCount -** Số phản hồi của máy chủ cần thiết để tạo lưu trữ zip ban đầu

  - **Data\_InitLoadProcess -** Khoảng thời gian thực hiện phương pháp InitLoadProcess tính theo mili giây

  - **Data\_InitPackage -** Khoảng thời gian thực hiện phương pháp InitPackage tính theo mili giây

  - **Data\_InitSecureReaderReasons -** Khoảng thời gian thực hiện phương pháp InitSecureReaderReasons tính theo mili giây

  - **Data\_IsIncOpenInProgressWhileOpen -** Trong trường hợp nhiều mở cùng một tài liệu, giao thức Inc Open có chạy cùng với giao thức mở không?

  - **Data\_IsMultiOpen -** Chúng tôi có hỗ trợ nhiều lần mở không?

  - **Data\_IsOCS -** Tài liệu ở chế độ OCS có ở trạng thái được biết đến cuối cùng của nó không

  - **Data\_IsODPFile -** Tài liệu ở “Định dạng tài liệu mở” có được OpenOffice.org sử dụng hay không

  - **Data\_IsPPTMetroFile -** Định dạng tệp tài liệu có phải là metro (pptx) không

  - **Data\_LoadDocument -** Khoảng thời gian thực hiện phương pháp LoadDocument tính theo mili giây

  - **Data\_MeasurementBreakdown -** Phân tích đo lường được mã hóa (rút ngắn hiệu suất phương pháp chi tiết)

  - **Data\_Measurements -** Số đo được mã hóa

  - **Data\_MethodId -** Phương thức cuối cùng được thực thi

  - **Data\_NotRequiredExcludedItems -** Tổng số mục gói PowerPoint không được yêu cầu cho lần kết xuất đầu tiên và bị loại trừ

  - **Data\_NotRequiredExcludedItemsSize -** Tổng số mục gói PowerPoint không được yêu cầu cho lần kết xuất đầu tiên và bị loại trừ

  - **Data\_NotRequiredExcludedParts -** Tổng số phần zip không được yêu cầu cho lần kết xuất đầu tiên và bị loại trừ

  - **Data\_NotRequiredExcludedPartsSize -** Tổng số phần zip không được yêu cầu cho lần kết xuất đầu tiên và bị loại trừ

  - **Data\_OpenCompleteFailureHR -** Kết quả về lý do tại sao giao thức OpenComplete không thành công

  - **Data\_OpenCompleteFailureTag -** Thẻ (con trỏ tới vị trí mã) trong đó giao thức OpenComplete không thành công

  - **Data\_OpenLifeguardOption -** Tập hợp các giá trị được lựa chọn được xác định trước cho thao tác của bảo vệ (None, TryAgain, OpenInWebApp, v.v.)

  - **Data\_OpenReason -** Tập hợp giá trị được xác định trước về cách mở tài liệu này (FilePicker, OpenFromMru, FileDrop, v.v.)

  - **Data\_OSRPolicy -** Chính sách SecureReader

  - **Data\_OSRReason -** Lý do tại sao tài liệu này được mở trong Trình đọc an toàn

  - **Data\_OtherContentTypesWithRequiredParts -** Các loại nội dung không chuẩn được loại trừ nhưng được yêu cầu cho lần kết xuất đầu tiên

  - **Data\_PrepCacheAsync -** Cờ cho OcsiOpenPerfPrepCacheAsync

  - **Data\_PreviousDiscardFailed -** Cho biết lần thử mở/đóng trước đó trên tài liệu không giải phóng đúng tất cả bộ nhớ

  - **Data\_PreviousFailureHr -** Trong trường hợp mở lại cùng một tài liệu, kết quả thất bại cuối cùng là gì

  - **Data\_PreviousFailureTag -** Trong trường hợp mở lại cùng một tài liệu, thẻ lỗi cuối cùng là gì (con trỏ đến vị trí mã)

  - **Data\_RemoteDocToken -** Mở từ xa có được bật không (tính năng nguyên mẫu cho phép mở tệp từ dịch vụ thay vì từ máy chủ)?

  - **Data\_Repair -** Chúng tôi có đang ở chế độ sửa chữa tài liệu hay không (đối với các tài liệu bị lỗi có thể sửa được)

  - **Data\_RequestPauseStats -** Số lần mã được yêu cầu để tạm dừng ghi hiệu suất

  - **Data\_RequiredPartsComressedSize -** Tổng kích cỡ của các phần PowerPoint cần thiết cho lần kết xuất đầu tiên

  - **Data\_RequiredPartsDownload -** Tổng kích cỡ của các phần PowerPoint được yêu cầu được tải xuống

  - **Data\_RequiredPartsRoundtripCount -** Tổng số vòng tròn (lệnh gọi đến máy chủ) cần thiết để có được tất cả các phần PowerPoint cần thiết cho lần kết xuất đầu tiên

  - **Data\_RequiredZipItemsDownload -** Tổng kích cỡ của các mục zip cần thiết cho lần kết xuất đầu tiên

  - **Data\_RequiredZipItemsRoundtripCount -** Tổng số vòng tròn (lệnh gọi đến máy chủ) cần thiết để có được tất cả các mục zip cần thiết cho lần kết xuất đầu tiên

  - **Data\_RoundtripsAfterMissingRequiredParts -** Tổng số vòng tròn (lệnh gọi đến máy chủ) cần thiết sau khi chúng tôi thấy thiếu các phần PowerPoint cần thiết

  - **Data\_RoundtripsAfterMissingRequiredZipItems -** Tổng số vòng tròn (lệnh gọi đến máy chủ) cần thiết sau khi chúng tôi thấy thiếu các mục zip yêu cầu

  - **Data\_RoundtripsAfterRequiredPackage -** Tổng số vòng tròn (lệnh gọi đến máy chủ) cần thiết sau khi chúng tôi tạo gói

  - **Data\_RoundtripsAfterRequiredParts -** Tổng số vòng tròn (lệnh gọi đến máy chủ) cần thiết sau khi chúng tôi tải xuống tất cả các phần bắt buộc

  - **Data\_SetDocCoAuthAutoSaveable -** Khoảng thời gian thực hiện phương pháp SetDocCoAuthAutoSaveable tính theo mili giây

  - **Data\_SniffedFileType -** Một phỏng đoán có giáo dục về loại tệp đề xuất của tài liệu bị lỗi

  - **Data\_StartTime -** Bộ đếm hiệu suất khi bắt đầu mở

  - **Data\_StopwatchDuration:long -** Tổng thời gian cho Hoạt động

  - **Data\_SyncSlides -** Khoảng thời gian thực hiện phương pháp SyncSlides tính theo mili giây

  - **Data\_TimerStartReason -** Tập hợp các giá trị được xác định trước về cách bắt đầu bộ đếm thời gian (CatchMissedSyncStateNotification, WaitingForFirstD Download, v.v.)

  - **Data\_TimeSplitMeasurements -** Phân tích đo lường được mã hóa (rút ngắn hiệu suất phương pháp chi tiết)

  - **Data\_TimeToInitialPackage -** Thời gian để tạo gói ban đầu

  - **Data\_TimeToRequiredPackage -** Thời gian để tạo gói bắt buộc

  - **Data\_TimeToRequiredParts -** Thời gian để tạo gói với tất cả các phần cần thiết trong đó

  - **Data\_TotalRequiredParts -** Tổng số phần PowerPoint cần thiết cho lần kết xuất đầu tiên

  - **Data\_UnknownRequiredParts -** Tổng số phần không tiêu chuẩn cần thiết cho lần kết xuất đầu tiên

  - **Data\_UnpackLinkWatsonId -** Mã định danh Watson lỗi khi tài liệu được mở thông qua URL chia sẻ OneDrive

  - **Data\_UnpackResultHint -** Tập hợp giá trị được xác định trước của việc giải nén kết quả URL chia sẻ (NavigateToWebWithoutError, UrlUnsupported ,vorOpen, v.v.)

  - **Data\_UnpackUrl -** Khoảng thời gian thực hiện phương pháp UnpackUrl tính theo mili giây

  - **Data\_UpdateAppstateTimeMS -** Khoảng thời gian thực hiện phương pháp UpdateAppstate tính theo mili giây

  - **Data\_UpdateCoauthoringState -** Khoảng thời gian thực hiện phương pháp UpdateCoauthoringState tính theo mili giây

  - **Data\_UpdateReadOnlyState -** Khoảng thời gian thực hiện phương pháp UpdateReadOnlyState tính theo mili giây

  - **Data\_WACCorrelationId -** Trong trường hợp mở tệp trong trình duyệt, nhận tương quan của nhật ký WebApp

  - **Data\_WasCachedOnInitialize -** Tài liệu này có được lưu trong quá trình khởi tạo hay không

  - **Data\_WBDirtyBeforeDiscard -** Nhánh hoạt động có trở thành rác trước khi mở lại tài liệu hay không

  - **Data\_ZRTOpenDisabledReasons -** Lý do chúng tôi không thể mở tài liệu từ bộ đệm ẩn (Chuyến đi khứ hồi)

#### <a name="officeprojectopenproject"></a>Office.Project.OpenProject

Project sẽ mở ra một tệp. Sự kiện này cho biết người dùng trực tiếp mở tệp Project bởi người dùng. Nó chứa dữ liệu thành công quan trọng của việc mở tệp trong Project.

Các trường sau đây sẽ được thu thập:

  - **Data\_AgileMode -** xác định xem dự án được mở là một dự án thác nước hoặc dự án linh hoạt

  - **Data\_AlertTime -** Lượng thời gian hộp thoại khởi động được kích hoạt

  - **Data\_CacheFileSize -** Nếu tệp được lưu trữ, kích cỡ tệp

  - **Data\_EntDocType -** Loại tệp đã được mở

  - **Data\_IsInCache -** Liệu tệp đã mở có được vào bộ đệm ẩn hay không

  - **Data\_LoadSRAs -** Người dùng có muốn tải SRA hay không

  - **Data\_OpenFromDocLib -** Nếu tệp Project được mở là từ thư viện tài liệu

  - **Data\_Outcome -** Tổng thời gian khởi động và mở tệp

  - **Data\_Outcome -** Tổng thời gian khởi động và mở tệp.

  - **Data\_ProjectServerVersion -** Phiên bản và bản dựng mà Project hiện đang bật

#### <a name="officesessionidproviderofficeprocesssessionstart"></a>Office.SessionIdProvider.OfficeProcessSessionStart

Áp dụng cho tất cả các ứng dụng Office dựa trên Windows: win32 và UWP

Các trường sau đây sẽ được thu thập:

- **OfficeProcessSessionStart** gửi thông tin cơ bản khi bắt đầu một phiên Office mới. Điều này được sử dụng để đếm số phiên duy nhất được thấy trên một thiết bị nhất định. Điều này được sử dụng như một sự kiện thông báo hoạt động để đảm bảo rằng ứng dụng có chạy trên thiết bị hay không. Ngoài ra, nó đóng vai trò là tín hiệu quan trọng cho độ tin cậy của ứng dụng tổng thể

- **AppSessionGuid** - Mã định danh của một phiên ứng dụng cụ thể bắt đầu tại thời điểm tạo quy trình và tồn tại cho đến khi quy trình kết thúc. Nó được định dạng là GUID 128 bit tiêu chuẩn nhưng được cấu tạo gồm 4 phần. Bốn phần theo thứ tự là (1) ID quy trình 32 bit (2) ID phiên 16 bit (3) ID khởi động 16 bit (4) Thời gian tạo quy trình trong UTC 100ns 64 bit

- **processSessionId** - GUID được tạo ngẫu nhiên để xác định phiên ứng dụng

- **UTCReplace_AppSessionGuid** - Giá trị boolean không đổi. Luôn true.

#### <a name="officetelemetryengineisprelaunch"></a>Office.TelemetryEngine.IsPreLaunch

Có thể áp dụng cho các ứng dụng Office UWP.  Sự kiện này được kích hoạt khi một ứng dụng Ofice được bắt đầu để nâng cấp/cài đặt bài lần đầu tiên từ cửa hàng. Đây là một phần của dữ liệu chẩn đoán cơ bản, được sử dụng để theo dõi xem phiên có khởi chạy phiên hay không.

Các trường sau đây sẽ được thu thập:

- **appVersionBuild** - Số phiên bản bản dựng ứng dụng.

- **appVersionMajor** - Số phiên bản chính của ứng dụng.

- **appVersionMino** - Số phiên bản phụ của ứng dụng.

- **appVersionRev** - Số phiên bản bản chỉnh sửa của ứng dụng.

- **SessionID** - GUID được tạo ngẫu nhiên để xác định phiên ứng dụng

#### <a name="officetelemetryenginesessionhandoff"></a>Office.TelemetryEngine.SessionHandOff

Áp dụng cho các ứng dụng Office chạy trên Win32.  Sự kiện này giúp chúng tôi hiểu liệu có một phiên mới được tạo để xử lý sự kiện mở tệp do người dùng khởi tạo hay không. Đó là một thông tin chẩn đoán quan trọng được sử dụng để lấy tín hiệu độ tin cậy và đảm bảo rằng ứng dụng hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

- **appVersionBuild** - Số phiên bản bản dựng ứng dụng.

- **appVersionMajor** - Số phiên bản chính của ứng dụng.

- **appVersionMino** - Số phiên bản phụ của ứng dụng.

- **appVersionRev** - Số phiên bản bản chỉnh sửa của ứng dụng.

- **childSessionID** - GUID được tạo ngẫu nhiên để xác định phiên ứng dụng

- **parentSessionId** - GUID được tạo ngẫu nhiên để xác định phiên ứng dụng

#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Sự kiện này cho biết Office Word mở một tài liệu từ danh sách Được sử dụng gần đây nhất (MRU). Nó cũng chứa dữ liệu hiệu suất mở tệp quan trọng và là sự kiện bắt đầu ứng dụng từ góc độ người dùng. Sự kiện theo dõi xem tệp mở từ MRU có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemRes -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_BytesAsynchronous -** Số byte (được nén) mà chúng tôi tin rằng chúng tôi có thể mở tệp mà không cần lấy chúng trước khi người dùng muốn bắt đầu chỉnh sửa hoặc có thể lưu

  - **Data\_BytesAsynchronousWithWork -** Số byte (được nén) mà chúng tôi có thể mở tệp mà không cần nhưng sẽ yêu cầu đầu tư mã đáng kể để thực hiện

  - **Data\_BytesSynchronous -** Số byte (đã nén) mà chúng ta phải có trước khi có thể bắt đầu mở tệp

  - **Data\_BytesUnknown -** Số lượng byte trong các phần tài liệu mà chúng tôi không mong muốn tìm thấy

  - **Data\_DetachedDuration -** Thời gian hoạt động được tách ra từ chuỗi

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_Doc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_Doc\_WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data\_EditorDisablingRename -** Mã định danh của trình chỉnh sửa đầu tiên khiến việc đổi tên bị vô hiệu hóa

  - **Data\_EditorsCount -** Số lượng trình chỉnh sửa trong tài liệu

  - **Data\_FSucceededAfterRecoverableFailure -** Cho biết rằng mở thành công sau khi sửa lỗi trong khi mở tài liệu

  - **Data\_ForceReadWriteReason -** Giá trị số nguyên biểu thị lý do tại sao tệp bị buộc vào chế độ đọc/ghi

  - **Data\_LastLoggedTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định khi chúng tôi cố gắng không mở hai lần (được sử dụng để chẩn đoán chất lượng dữ liệu)

  - **Data\_LinkStyles -** Cho biết liệu chúng tôi có đang liên kết đến các kiểu mẫu hay không

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word

  - **Data\_Measurements -** Chuỗi được mã hóa chứa phân tích thời gian của các phần mở khác nhau. Được sử dụng để đo lường hiệu suất.

  - **Data\_MoveDisabledReason -** Lỗi vô hiệu hóa thao tác di chuyển cho tài liệu

  - **Data\_MoveFlightEnabled -** Liệu thao tác chống lại tính năng di chuyển có được bật hay không

  - **Dữ liệu\_PartsUnknown -** Số phần tài liệu mà chúng tôi không thể lấy dữ liệu

  - **Data\_RecoverableFailureInitiationLocationTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định vị trí trong mã nơi mà chúng tôi cố gắng sửa tệp trước khi mở

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu này

  - **Data\_RenameFlightEnabled -** Liệu thao tác chống lại tính năng đổi tên có được bật hay không

  - **Data\_SecondaryTag -** Thẻ duy nhất cho site gọi mã được sử dụng để thêm dữ liệu lỗi bổ sung để mở

  - **Data\_TemplateFormat -** Định dạng tệp của mẫu mà tài liệu dựa trên.

  - **Data\_UsesNormal -** Cho biết liệu tài liệu mở có dựa trên mẫu thông thường hay không

#### <a name="officewordfileopenopenffileopenxstzcore"></a>Office.Word.FileOpen.OpenFFileOpenXstzCore

Sự kiện này cho biết Office Word sẽ mở tài liệu được người dùng nhấp đúp. Nó cũng chứa dữ liệu hiệu suất mở tệp quan trọng và là sự kiện bắt đầu ứng dụng từ góc độ người dùng. Sự kiện theo dõi xem tệp mở từ việc nhấp đúp vào tệp có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemRes -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu

  - **Data\_BytesAsynchronous -** Số byte (được nén) mà chúng tôi tin rằng chúng tôi có thể mở tệp mà không cần lấy chúng trước khi người dùng muốn bắt đầu chỉnh sửa hoặc có thể lưu

  - **Data\_BytesAsynchronousWithWork -** Số byte (được nén) mà chúng tôi có thể mở tệp mà không cần nhưng sẽ yêu cầu đầu tư mã đáng kể để thực hiện

  - **Data\_BytesSynchronous -** Số byte (đã nén) mà chúng ta phải có trước khi có thể bắt đầu mở tệp

  - **Data\_BytesUnknown -** Số lượng byte trong các phần tài liệu mà chúng tôi không mong muốn tìm thấy

  - **Data\_DetachedDuration -** Thời gian hoạt động được tách ra từ chuỗi

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SharePointServiceContext-**

  - **Data\_Doc\_SizeInBytes -** Chỉ số kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_Doc\_WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data\_EditorDisablingRename -** Mã định danh của trình chỉnh sửa đầu tiên khiến việc đổi tên bị vô hiệu hóa

  - **Data\_EditorsCount -** Số lượng trình chỉnh sửa trong tài liệu

  - **Data\_FSucceededAfterRecoverableFailure -** Cho biết rằng mở thành công sau khi sửa lỗi trong khi mở tài liệu

  - **Data\_ForceReadWriteReason -** Giá trị số nguyên biểu thị lý do tại sao tệp bị buộc vào chế độ đọc/ghi

  - **Data\_LastLoggedTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định khi chúng tôi cố gắng không mở hai lần (được sử dụng để chẩn đoán chất lượng dữ liệu)

  - **Data\_LinkStyles -** Cho biết liệu chúng tôi có đang liên kết đến các kiểu mẫu hay không

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word

  - **Data\_Measurements -** Chuỗi được mã hóa chứa phân tích thời gian của các phần mở khác nhau. Được sử dụng để đo lường hiệu suất.

  - **Data\_MoveDisabledReason -** Lỗi vô hiệu hóa thao tác di chuyển cho tài liệu

  - **Data\_MoveFlightEnabled -** Liệu thao tác chống lại tính năng di chuyển có được bật hay không

  - **Dữ liệu\_PartsUnknown -** Số phần tài liệu mà chúng tôi không thể lấy dữ liệu

  - **Data\_RecoverableFailureInitiationLocationTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định vị trí trong mã nơi mà chúng tôi cố gắng sửa tệp trước khi mở.

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu này

  - **Data\_RenameFlightEnabled -** Liệu thao tác chống lại tính năng đổi tên có được bật hay không

  - **Data\_SecondaryTag -** Thẻ duy nhất cho site gọi mã được sử dụng để thêm dữ liệu lỗi bổ sung để mở.

  - **Data\_TemplateFormat -** Định dạng tệp của mẫu mà tài liệu dựa trên.

  - **Data\_UsesNormal -** Cho biết liệu tài liệu mở có dựa trên mẫu thông thường hay không


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Sự kiện này cho biết Office Word mở một tài liệu thông qua kích hoạt COM hoặc dòng lệnh. Nó cũng chứa dữ liệu hiệu suất mở tệp quan trọng và là sự kiện bắt đầu ứng dụng từ góc độ người dùng. Sự kiện theo dõi xem MRU từ tệp mở từ dòng lệnh có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemRes -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_BytesAsynchronous -** Số byte (được nén) mà chúng tôi tin rằng chúng tôi có thể mở tệp mà không cần lấy chúng trước khi người dùng muốn bắt đầu chỉnh sửa hoặc có thể lưu.

  - **Data\_BytesAsynchronousWithWork -** Số byte (được nén) mà chúng tôi có thể mở tệp mà không cần nhưng sẽ yêu cầu đầu tư mã đáng kể để thực hiện

  - **Data\_BytesSynchronous -** Số byte (đã nén) mà chúng ta phải có trước khi có thể bắt đầu mở tệp

  - **Data\_BytesUnknown -** Số lượng byte trong các phần tài liệu mà chúng tôi không mong muốn tìm thấy.

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_Doc\_WopiServiceId -** Chứa mã định danh duy nhất của nhà cung cấp dịch vụ WOPI

  - **Data\_EditorDisablingRename -** Mã định danh của trình chỉnh sửa đầu tiên khiến việc đổi tên bị vô hiệu hóa

  - **Data\_EditorsCount -** Số lượng trình chỉnh sửa trong tài liệu

  - **Data\_FSucceededAfterRecoverableFailure -** Cho biết rằng mở thành công sau khi sửa lỗi trong khi mở tài liệu

  - **Data\_ForceReadWriteReason -** Giá trị số nguyên biểu thị lý do tại sao tệp bị buộc vào chế độ đọc/ghi

  - **Data\_LastLoggedTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định khi chúng tôi cố gắng không mở hai lần (được sử dụng để chẩn đoán chất lượng dữ liệu)

  - **Data\_LinkStyles -** Cho biết liệu chúng tôi có đang liên kết đến các kiểu mẫu hay không

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word

  - **Data\_Measurements -** Chuỗi được mã hóa chứa phân tích thời gian của các phần mở khác nhau. Sử dụng để chẩn đoán hiệu suất mở.

  - **Data\_MoveDisabledReason -** Lỗi vô hiệu hóa thao tác di chuyển cho tài liệu

  - **Data\_MoveFlightEnabled -** Liệu thao tác chống lại tính năng di chuyển có được bật hay không

  - **Dữ liệu\_PartsUnknown -** Số phần tài liệu mà chúng tôi không thể lấy dữ liệu

  - **Data\_RecoverableFailureInitiationLocationTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định vị trí trong mã nơi mà chúng tôi cố gắng sửa tệp trước khi mở

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu này

  - **Data\_RenameFlightEnabled -** Liệu thao tác chống lại tính năng đổi tên có được bật hay không

  - **Data\_SecondaryTag -** Thẻ duy nhất cho site gọi mã được sử dụng để thêm dữ liệu lỗi bổ sung để mở.

  - **Data\_TemplateFormat -** Định dạng tệp của mẫu mà tài liệu dựa trên.

  - **Data\_UsesNormal -** Cho biết liệu tài liệu mở có dựa trên mẫu thông thường hay không.


#### <a name="officewordfileopenopenloadfile"></a>Office.Word.FileOpen.OpenLoadFile

Sự kiện này cho biết Office Word mở một tài liệu thông qua hộp thoại Mở. Nó cũng chứa dữ liệu hiệu suất mở tệp quan trọng và là sự kiện bắt đầu ứng dụng từ góc độ người dùng. Sự kiện theo dõi xem tệp mở từ hộp thoại mở tệp có hoạt động như mong đợi hay không. Nó cũng được sử dụng để tính toán người dùng/thiết bị hoạt động hàng tháng và số liệu về độ tin cậy của đám mây.

Các trường sau đây sẽ được thu thập:

  - **Data\_AddDocTelemRes -** Báo cáo xem chúng tôi có thể điền chính xác các giá trị liên quan đến tài liệu khác trong sự kiện hay không. Được sử dụng để chẩn đoán chất lượng dữ liệu.

  - **Data\_BytesAsynchronous -** Số byte (được nén) mà chúng tôi tin rằng chúng tôi có thể mở tệp mà không cần lấy chúng trước khi người dùng muốn bắt đầu chỉnh sửa hoặc có thể lưu

  - **Data\_BytesAsynchronousWithWork -** Số byte (được nén) mà chúng tôi có thể mở tệp mà không cần nhưng sẽ yêu cầu đầu tư mã đáng kể để thực hiện

  - **Data\_BytesSynchronous -** Số byte (đã nén) mà chúng ta phải có trước khi có thể bắt đầu mở tệp

  - **Data\_BytesUnknown -** Số lượng byte trong các phần tài liệu mà chúng tôi không mong muốn tìm thấy

  - **Data\_DetachedDuration -** Thời gian hoạt động được tách ra từ chuỗi

  - **Data\_Doc\_AccessMode -** Tài liệu đích chỉ đọc/có thể chỉnh sửa

  - **Data\_Doc\_AssistedReadingReasons -** Tập hợp các giá trị được xác định trước lý do tại sao tài liệu được mở trong chế độ đọc được hỗ trợ

  - **Data\_Doc\_ChunkingType -** Các đơn vị được sử dụng để mở tài liệu luỹ kế

  - **Data\_Doc\_EdpState -** Cài đặt Bảo vệ Dữ liệu Điện tử cho tài liệu

  - **Data\_Doc\_Ext -** Phần mở rộng tài liệu (docx/xlsb/pptx, v.v)

  - **Data\_Doc\_FileFormat -** Phiên bản giao thức định dạng tệp

  - **Data\_Doc\_Fqdn -** Tên miền trực tuyến OneDrive hoặc SharePoint

  - **Data\_Doc\_FqdnHash -** Hàm băm một chiều của tên miền nhận dạng khách hàng

  - **Data\_Doc\_IdentityTelemetryId -** Hàm băm một chiều của danh tính người dùng được sử dụng để thực hiện mở

  - **Data\_Doc\_InitializationScenario -** Ghi lại cách tài liệu được mở

  - **Data\_Doc\_IOFlags -** Báo cáo về các cờ đã lưu trong bộ nhớ đệm ẩn được sử dụng để đặt tùy chọn yêu cầu mở

  - **Data\_Doc\_IrmRights -** Các thao tác được cho phép bởi chính sách Bảo vệ Dữ liệu Điện tử đã được áp dụng cho tài liệu/người dùng

  - **Data\_Doc\_IsIncrementalOpen -** Cờ cho biết rằng tài liệu đã được mở một cách tăng dần

  - **Data\_Doc\_IsOcsSupported -** Cờ cho biết rằng tài liệu được hỗ trợ trong dịch vụ cộng tác

  - **Data\_Doc\_IsOpeningOfflineCopy -** Cờ cho biết rằng bản sao ngoại tuyến của tài liệu đã được mở

  - **Data_Doc_IsRtcAlwaysOn -** True nếu kênh thời gian thực (RTC) luôn bật cho tệp này.

  - **Data\_Doc\_IsSyncBacked -** Cờ cho biết rằng bản sao được đồng bộ hóa tự động của tài liệu tồn tại trên máy tính

  - **Data\_Doc\_Location -** Cho biết dịch vụ nào đã cung cấp tài liệu (OneDrive, File Server, SharePoint, v.v.)

  - **Data\_Doc\_LocationDetails -** Cho biết Thư mục đã biết nào cung cấp tài liệu được lưu trữ cục bộ

  - **Data\_Doc\_NumberCoAuthors -** Số lượng người dùng đồng nghiệp trong một phiên cộng tác chỉnh sửa

  - **Data\_Doc\_PasswordFlags -** Cho biết cờ đọc hoặc đọc/ghi mật khẩu được đặt

  - **Data\_Doc\_ReadOnlyReasons -** Lý do tại sao tài liệu được mở ở dạng chỉ đọc

  - **Data\_Doc\_ResourceIdHash -** Mã định danh tài liệu ẩn danh được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerDocId -** Mã định danh tài liệu ẩn danh không thể thay đổi được sử dụng để chẩn đoán sự cố

  - **Data\_Doc\_ServerProtocol -** Phiên bản giao thức được sử dụng để giao tiếp với dịch vụ

  - **Data\_Doc\_ServerType -** Loại máy chủ cung cấp dịch vụ (SharePoint, OneDrive, WOPI, v.v..)

  - **Data\_Doc\_ServerVersion -** Phiên bản máy chủ cung cấp dịch vụ

  - **Data\_Doc\_SessionId -** Xác định phiên chỉnh sửa tài liệu cụ thể trong phiên đầy đủ

  - **Data\_Doc\_SharePointServiceContext -** Thông tin chẩn đoán từ các yêu cầu của SharePoint Online

  - **Data\_Doc\_SizeInBytes -** Chỉ báo kích thước tài liệu

  - **Data\_Doc\_SpecialChars -** Chỉ báo các ký tự đặc biệt trong URL hoặc đường dẫn của tài liệu

  - **Data\_Doc\_StreamAvailability -** Chỉ báo nếu luồng tài liệu khả dụng/bị vô hiệu hóa

  - **Data\_Doc\_SyncBackedType -** Chỉ báo về loại tài liệu (cục bộ hoặc dịch vụ)

  - **Data\_Doc\_UrlHash -** Hàm băm một chiều để tạo mã định danh tài liệu gốc

  - **Data\_EditorDisablingRename -** Mã định danh của trình chỉnh sửa đầu tiên khiến việc đổi tên bị vô hiệu hóa

  - **Data\_EditorsCount -** Số lượng trình chỉnh sửa trong tài liệu

  - **Data\_ForceReadWriteReason -** Giá trị số nguyên biểu thị lý do tại sao tệp bị buộc vào chế độ đọc/ghi

  - **Data\_FSucceededAfterRecoverableFailure -** Cho biết rằng mở thành công sau khi sửa lỗi trong khi mở tài liệu

  - **Data\_LastLoggedTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định khi chúng tôi cố gắng không mở hai lần (được sử dụng để chẩn đoán chất lượng dữ liệu)

  - **Data\_LinkStyles -** Cho biết liệu chúng tôi có đang liên kết đến các kiểu mẫu hay không

  - **Data\_MainPdod -** Mã định danh tài liệu trong quy trình Office Word

  - **Data\_Measurements -** Chuỗi được mã hóa chứa phân tích thời gian của các phần mở khác nhau. Được sử dụng để đo lường hiệu suất.

  - **Data\_MoveDisabledReason -** Lỗi vô hiệu hóa thao tác di chuyển cho tài liệu

  - **Data\_MoveFlightEnabled -** Liệu thao tác chống lại tính năng di chuyển có được bật hay không

  - **Dữ liệu\_PartsUnknown -** Số phần tài liệu mà chúng tôi không thể lấy dữ liệu

  - **Data\_RecoverableFailureInitiationLocationTag -** Thẻ duy nhất cho site gọi mã được sử dụng để xác định vị trí trong mã nơi mà chúng tôi cố gắng sửa tệp trước khi mở

  - **Data\_RenameDisabledReason -** Lỗi gây ra việc đổi tên bị vô hiệu hóa cho tài liệu này

  - **Data\_RenameFlightEnabled -** Liệu thao tác chống lại tính năng đổi tên có được bật hay không

  - **Data\_SecondaryTag -** Thẻ duy nhất cho site gọi mã được sử dụng để thêm dữ liệu lỗi bổ sung để mở

  - **Data\_TemplateFormat -** Định dạng tệp của mẫu mà tài liệu dựa trên

  - **Data\_UsesNormal -** Cho biết liệu tài liệu mở có dựa trên mẫu thông thường hay không


### <a name="office-accessibility-configuration-subtype"></a>*Loại con cấu hình khả năng truy nhập Office*

Các tính năng trợ năng của Office

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a>Office.Accessibility.AccessibilityToolSessionPresenceWin32

Cho phép chúng tôi phát hiện ra rằng người dùng có một công cụ công nghệ Trợ giúp và tên của nó. Điều này cho phép chúng tôi hiểu rõ nếu người dùng Office gặp sự cố với công cụ Công nghệ trợ giúp cụ thể.

Các trường sau đây sẽ được thu thập:

  - **Data\_Data\_Jaws -** Cho biết liệu Jaws có đang chạy trong phiên không**Data\_Data\_Magic -** Cho biết liệu Magic có chạy trong phiên không

  - **Data\_Data\_Magnify -** Cho biết liệu tính năng Phóng to có chạy trong phiên không

  - **Data\_Data\_Narrator -** Cho biết nếu Trình tường thuật có chạy trong phiên không

  - **Data\_Data\_NVDA -** Cho biết nếu NVDA có chạy trong phiên không

  - **Data\_Data\_SA -** Cho biết nếu SA có chạy trong phiên không

  - **Data\_Data\_Supernova -** Cho biết nếu Supernova có chạy trong phiên không

  - **Data\_Data\_SuperNovaessSuite -** Cho biết nếu SuperNovaAccessSuite có chạy trong phiên không

  - **Data\_Data\_WinEyes -** Cho biết nếu WinEyes có chạy trong phiên không

  - **Data\_Data\_ZoomText -** Cho biết nếu ZoomText có chạy trong phiên không

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Sự kiện này cho biết Office Word đọc to văn bản trong tài liệu. Sự kiện là thông báo hoạt động cho tính năng trợ năng cho phép Microsoft đánh giá trạng thái tính năng đọc to văn bản.

Các trường sau đây sẽ được thu thập:

  - **Data\_CharacterCount -** Số ký tự của tài liệu

  - **Data\_CharactersWithSpaceCount -** Số lượng ký tự và dấu cách của tài liệu

  - **Data\_IsPageCountInProgress -** là số trang đang được thực hiện

  - **Data\_LineCount -** Số dòng của tài liệu

  - **Data\_PageCount -** Số trang của tài liệu

  - **Data\_ParagraphCount -** Số đoạn của tài liệu

  - **Data\_Play -** Đây có phải là lần đầu tiên Word đọc to hay không

  - **Data\_ViewKind -** Loại dạng xem tài liệu

  - **Data\_WordCount -** Số từ trong tài liệu

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud

Sự kiện này cho biết Office Word dừng đọc to văn bản trong tài liệu. Sự kiện cho phép Microsoft đánh giá trạng thái tính năng đọc to văn bản bằng cách đánh giá khoảng thời gian hoạt động.

Các trường sau đây sẽ được thu thập:

  - Không có

## <a name="product-and-service-performance-data-events"></a>Sự kiện dữ liệu về hiệu suất sản phẩm và dịch vụ

Sau đây là những loại dữ liệu con trong danh mục này:
- [Ứng dụng bất ngờ (gặp sự cố)](#unexpected-application-exit-crash-subtype)
- [Hiệu suất tính năng ứng dụng ](#application-feature-performance-subtype)
- [Lỗi hoạt động ứng dụng](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a>*Loại con Ứng dụng thoát bất ngờ (gặp sự cố)*

Ứng dụng bất ngờ thoát và trạng thái của ứng dụng khi điều đó xảy ra.

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Thu thập thông tin cho bất kỳ trường hợp ngoại lệ nào chưa được xử lý bằng Ứng dụng Data Streamer. Dữ liệu này được dùng để theo dõi tình trạng của ứng dụng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Ngoại lệ** - Ngăn xếp lệnh gọi cho Ngoại lệ

- **Tên sự kiện** - Tên sự kiện là Danh mục sự kiện và Nhãn sự kiện.

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Sự kiện được tạo ra khi phần bổ trợ COM gặp sự cố

Phân tích trên máy tính: Công cụ này được sử dụng làm tử số trong tính toán trạng thái dành riêng cho doanh nghiệp cho các phần bổ trợ được sử dụng để phỏng đoán trong quá trình thử nghiệm nếu phần bổ trợ "sẵn sàng nâng cấp" trong vòng sản xuất.  
Thông tin chuyên sâu toàn cầu: Công cụ này được sử dụng để tính toán mức độ "sẵn sàng" toàn cầu, không dành riêng cho doanh nghiệp cho phần bổ trợ sau đó được xuất bản trên readyforwindows.com và các công cụ khác như Bộ công cụ về Tính sẵn sàng

Các trường sau đây sẽ được thu thập:

**ScopeId** – Phạm vi chuỗi hội thoại hiện tại

**Method** – Phương pháp Office nơi mà ngoại lệ đã xảy ra

**Interface** – Giao diện Office nơi xảy ra ngoại lệ

**AddinId** – ID lớp phần bổ trợ

**AddinProgId** – ID tiến trình phần bổ trợ

**AddinFriendlyName** – Tên thân thiện của phần bổ trợ

**AddinTimeDateStamp** – Dấu thời gian phần bổ trợ từ siêu dữ liệu DLL

**AddinVersion** – Phiên bản phần bổ trợ

**AddinFileName** – Tên tệp bổ trợ không bao gồm đường dẫn tệp

**VSTOAddIn** – Phần bổ trợ có phải là VSTO hay không

**AddinConnectFlag** – Hành vi tải hiện tại

**LoadAttempts** – Số lần thử tải phần bổ trợ

#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Sự kiện được tạo khi tệp được kích hoạt macro chạy vào lỗi dịch mã hoặc thời gian chạy

Phân tích trên máy tính: Công cụ này được sử dụng làm tử số trong tính toán trạng thái dành riêng cho doanh nghiệp cho các loại macro (ví dụ: macro Word, macro Excel, v.v.) được sử dụng để phỏng đoán trong quá trình thử nghiệm nếu phần bổ trợ "sẵn sàng nâng cấp" trong vòng sản xuất.

Các trường sau đây sẽ được thu thập:

**TagId** – Dd của thẻ phép đo từ xa

**BreakReason** – Nguyên nhân gây ra sự cố (thời gian chạy, dịch mã, lỗi khác)

**SolutionType** – Loại giải pháp (tài liệu, mẫu, phần bổ trợ ứng dụng, phần bổ trợ COM)

**Data.ErrorCode** – Mã lỗi được báo cáo bởi công cụ VBA

#### <a name="officeoutlookdesktophangbucketmetrics"></a>Office.Outlook.Desktop.HangBucketMetrics

Thu thập thời gian treo đối với việc Outlook bị treo - mã định danh duy nhất cho mỗi lần treo, thời gian trôi qua và thông tin ngăn xếp lệnh gọi. Dữ liệu được sử dụng để phát hiện và xác định sự cố ứng dụng để khắc phục trong các bản cập nhật trong tương lai.

Các trường sau đây sẽ được thu thập:

  - **BucketId** - Hàm băm của ngăn xếp lệnh gọi

  - **ElapsedTotal** - Tổng thời gian dành cho lệnh gọi

  - **ElapsedHanging** - Thời gian treo trong lệnh gọi

#### <a name="officeoutlookdesktophangreportingscopeperfmetrics"></a>Office.Outlook.Desktop.HangReportingScopePerfMetrics

Thu thập thời gian dành cho các kịch bản cốt lõi triển vọng - switchfolder, switchmodule, sendmailoutbox, openitem classic, sendmailtransport. Dữ liệu được theo dõi tích cực cho các vấn đề về hiệu suất bất thường. Nó được sử dụng để phát hiện và chẩn đoán các vấn đề về hiệu suất cũng như cải thiện hiệu suất với mỗi bản cập nhật.

Các trường sau đây sẽ được thu thập:

  - **ElapsedTotal** - Tổng thời gian dành cho lệnh gọi này

  - **ScopeId** - Tên của hàm chứa khai báo hoặc tên tùy chỉnh được cung cấp thông qua định nghĩa phạm vi

#### <a name="officeoutlookdesktopwatsonbuckets"></a>Office.Outlook.Desktop.WatsonBuckets

Quy tắc này thu thập thông tin sự cố từ nhật ký sự kiện khi Outlook gặp sự cố trong phiên trước đó.

Các dữ liệu được theo dõi tích cực cho sự cố treo bất thường. Dữ liệu được sử dụng để phát hiện và xác định sự cố treo để khắc phục trong các bản cập nhật trong tương lai.

Các trường sau đây sẽ được thu thập:

  - **BucketId** - Hàm băm của ngăn xếp lệnh gọi

  - **ElapsedTotal** - Tổng thời gian dành cho lệnh gọi

  - **ElapsedHanging** - Thời gian treo trong lệnh gọi

#### <a name="officepowerpointsession"></a>**Office.PowerPoint.Session**

Thu thập việc sử dụng tính năng trên mỗi phiên PowerPoint.Dữ liệu này được sử dụng để tính tỷ lệ thoát PowerPoint không đáng tin cậy trong khi sử dụng một tính năng. Tỷ lệ thoát PowerPoint không đáng tin cậy là tín hiệu chính để đảm bảo PowerPoint đang hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **Flag** – Cờ của phiên

  - **Usage** – Việc sử dụng tính năng

#### <a name="officepowerpointuaedialog"></a>Office.PowerPoint.UAE.Dialog

Được thu thập mỗi khi PowerPoint thoát ra một cách không đáng tin cậy trong khi hộp thoại mở ở trên cùng của cửa sổ chính PowerPoint. Thông tin này rất quan trọng để theo kịp việc PowerPoint thoát ra một cách không đáng tin cậy do hộp thoại hoạt động chặn cửa sổ chính của PowerPoint. Microsoft đang sử dụng dữ liệu này để chẩn đoán sự cố nhằm đảm bảo PowerPoint hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **DlgCnt** – Tổng số của hộp thoại mở khi phiên gặp sự cố

  - **DlgId** – Mã định danh hộp thoại mở

  - **IdType** – Loại mã định danh hộp thoại mở

  - **InitTime** - Thời gian khởi tạo phiên bị lỗi

  - **SessionId** - Mã định danh phiên.

  - **TopId** – Mã định danh hộp thoại trên cùng

  - **Version** – Phiên bản phiên gặp sự cố

#### <a name="officepowerpointuaedocument"></a>Office.PowerPoint.UAE.Document

Thu thập tính năng đang được sử dụng trên tài liệu khi PowerPoint thoát ra một không đáng tin cậy. Các tính năng này bao gồm trình chiếu, mở tài liệu, lưu, chỉnh sửa, đồng tác giả, tắt. Thông tin này rất quan trọng để theo kịp việc PowerPoint thoát ra một cách không đáng tin cậy trong khi sử dụng một tính năng. Microsoft đang sử dụng dữ liệu này để chẩn đoán sự cố nhằm đảm bảo PowerPoint hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **CoauthFlag** – Cờ sử dụng đồng tác giả

  - **CommandFlag** – Cờ sửa đổi tài liệu

  - **FileIOFlag** – Cờ sử dụng IO tệp

  - **InitTime** - Thời gian khởi tạo phiên bị lỗi

  - **Location** – Vị trí tài liệu

  - **ServerDocId** – Mã định danh tài liệu máy chủ

  - **SessionId** - Mã định danh phiên gặp sự cố.

  - **UrlHash** – Hàm băm URL tài liệu

  - **Usage** – Việc sử dụng tính năng

  - **Version** – Phiên bản phiên gặp sự cố

#### <a name="officepowerpointuaeopen"></a>Office.PowerPoint.UAE.Open

Thu thập mỗi khi PowerPoint thoát một cách không đáng tin cậy trong khi mở tài liệu. Thông tin này rất quan trọng để theo kịp việc PowerPoint thoát ra một cách không đáng tin cậy trong mở một tài liệu. Microsoft đang sử dụng dữ liệu này để chẩn đoán sự cố nhằm đảm bảo PowerPoint hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **FileUrlLocation** – Vị trí URL tài liệu

  - **Flag** – Cờ cho thao tác mở

  - **InitTime** - Thời gian khởi tạo phiên bị lỗi

  - **Location** – Vị trí tài liệu

  - **OpenReason** – Lý do cho thao tác mở

  - **ServerDocId** – Mã định danh tài liệu máy chủ

  - **SessionId** - Mã định danh phiên gặp sự cố.

  - **UrlHash** – Hàm băm URL tài liệu

  - **Version** – Phiên bản phiên gặp sự cố

#### <a name="officepowerpointuaesession"></a>Office.PowerPoint.UAE.Session

Thu thập tính năng đã được sử dụng khi phiên PowerPoint thoát ra một không đáng tin cậy.Thông tin này rất quan trọng để theo kịp việc PowerPoint thoát ra một cách không đáng tin cậy. Microsoft đang sử dụng dữ liệu này để chẩn đoán sự cố nhằm đảm bảo PowerPoint hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **Flag** – Cờ của phiên

  - **InitTime** - Thời gian khởi tạo phiên bị lỗi

  - **PreviousSessionId** - Mã định danh phiên gặp sự cố.

  - **Usage** – Việc sử dụng tính năng

  - **Version** – Phiên bản phiên gặp sự cố

#### <a name="officepowerpointuaeshutdown"></a>Office.PowerPoint.UAE.Shutdown

Thu thập PowerPoint thoát một cách không đáng tin cậy trong khi tắt. Thông tin này rất quan trọng để theo kịp việc PowerPoint thoát ra một cách không đáng tin cậy trong khi tắt. Microsoft đang sử dụng dữ liệu này để chẩn đoán sự cố nhằm đảm bảo PowerPoint hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **InitTime** - Thời gian khởi tạo phiên bị lỗi

  - **SessionId** - Mã định danh phiên gặp sự cố.

  - **Stage** – Giai đoạn tắt

  - **Version** – Phiên bản phiên gặp sự cố

#### <a name="officepowerpointuaeslideshow"></a>Office.PowerPoint.UAE.SlideShow

Thu thập PowerPoint thoát một cách không đáng tin cậy trong khi tắt. Thông tin này rất quan trọng để theo kịp việc PowerPoint thoát ra một cách không đáng tin cậy trong khi tắt. Microsoft đang sử dụng dữ liệu này để chẩn đoán sự cố nhằm đảm bảo PowerPoint hoạt động như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **InitTime** - Thời gian khởi tạo phiên bị lỗi

  - **Mode** – Chế độ trình chiếu

  - **SessionId** - Mã định danh phiên gặp sự cố.

  - **State** – Trạng thái trình chiếu

  - **Version** – Phiên bản phiên gặp sự cố

#### <a name="officeprogrammabilitytelemetryaddincrash"></a>Office.Programmability.Telemetry.AddInCrash

Sự kiện được tạo ra khi phần bổ trợ COM được tải. Thông tin này rất quan trọng để xác định xem liệu phần bổ trợ có gây ra sự cố cho ứng dụng Office hay không. Nó được sử dụng để đánh giá khả năng tương thích bổ trợ toàn cầu với các ứng dụng Office.

Các trường sau đây sẽ được thu thập:

  - **CLSID** – Mã định danh lớp phần bổ trợ

  - **ConnectFlag** – Hành vi tải phần bổ trợ hiện tại

  - **AddinFileName** – Tên tệp phần bổ trợ không bao gồm đường dẫn tệp

  - **AddinFriendlyName** – Tên thân thiện của phần bổ trợ

  - **Interface** – Giao diện Office nơi xảy ra ngoại lệ

  - **LoadAttempts** – Số lần thử tải phần bổ trợ

  - **Method** – Phương pháp Office nơi xảy ra ngoại lệ

  - **OfficeApplication** – Ứng dụng Office nơi xảy ra ngoại lệ

  - **OfficeVersion** – Các phiên bản của Office

  - **ProgID** Mã định danh tiến trình phần bổ trợ

#### <a name="officethisaddinstartupfailed"></a>Office.ThisAddIn.StartupFailed

Thu thập thông tin cho ngoại lệ xảy ra trong quá trình khởi động Ứng dụng Data Streamer. Dữ liệu này được dùng để theo dõi tình trạng của ứng dụng. Sự kiện này được tạo bởi Microsoft Data Streamer cho phần bổ trợ Excel.

Các trường sau đây sẽ được thu thập:

- **Ngoại lệ** - Ngăn xếp lệnh gọi cho Ngoại lệ

- **Tên sự kiện** - Tên sự kiện là Danh mục sự kiện và Nhãn sự kiện.


### <a name="application-feature-performance-subtype"></a>*Loại con hiệu suất tính năng ứng dụng *

Thời gian phản hồi hoặc hiệu suất kém cho các tình huống như ứng dụng khởi động hoặc mở tệp.

#### <a name="officemanageabilityserviceapplypolicy"></a>Office.Manageability.Service.ApplyPolicy

Phép đo từ xa quan trọng để theo dõi thất bại\\thành công của việc áp dụng thiết đặt chính sách điện toán đám mây vào sổ đăng ký. LastError cho biết lý do tại sao và vị trí ứng dụng của các chính sách trong sổ đăng ký không thành công.

Các trường sau đây sẽ được thu thập:

  - **Data.ApplyLogMsg** - Thông báo ngoại lệ nếu có trong khi chính sách đang được áp dụng

  - **Data.Cid** - Mã định danh tương quan được tạo động được gửi đến dịch vụ khi lệnh gọi dịch vụ được thực hiện để tải chính sách đám mây. Được sử dụng để kết hợp lệnh gọi gây ra sự cố trong khi áp dụng các chính sách trên đám mây.

  - **Data.Last Error** - Một trong năm giá trị chuỗi (bộ liệt kê) để ghi lại giai đoạn của ứng dụng chính sách được thực thi khi xảy ra ngoại lệ

#### <a name="officeoutlookdesktopbootperfmetrics"></a>Office.Outlook.Desktop.BootPerfMetrics

Thu thập thời gian được thực hiện để khởi động Outlook. Thời gian khởi động của Outlook được theo dõi tích cực để phát hiện và chẩn đoán hồi quy. Nó cũng được sử dụng để chẩn đoán sự nâng cấp của khách hàng cũng như cải thiện hiệu suất khởi động theo thời gian.

Các trường sau đây sẽ được thu thập:

  - **AddinElapsedTotal** - Tổng thời gian tải các phần bổ trợ

  - **CredPromptCount** – Số lượng lời nhắc thông tin đăng nhập được hiển thị

  - **ElapsedTotal** - Tổng thời gian dành cho khởi động

  - **IsLoggingEnabled** - Ghi nhật ký có được bật hay không

  - **ShowChooseProfileDlg** – Hộp thoại Chọn Hồ sơ có được hiển thị hay không

  - **ShowFirstRunDlg** - Outlook có được khởi chạy lần đầu tiên hay không

  - **ShowIMAPSrchfldWarningDlg** - Cảnh báo trong trường hợp chúng tôi có tài khoản IMAP có ANSI PST

  - **ShowNeedSupportDlg** - Lỗi khởi động kích hoạt hộp thoại hỗ trợ

  - **ShowSafeModeDlg** - Phiên có được mở ở chế độ an toàn hay không

  - **ShowScanPstDlg** - Kiểm tra sửa chữa lưu trữ hiển thị thông báo lỗi

#### <a name="officeperformanceboot"></a>Office.Performance.Boot

Được thu thập khi khởi động một ứng dụng Office. Bao gồm việc khởi động được bắt đầu bằng cách mở tệp hoặc khởi chạy thông qua menu Bắt đầu, cho dù đây có phải là lần khởi động đầu tiên của ứng dụng, số lượng bộ nhớ ứng dụng đang sử dụng là bao nhiêu và liệu có bất kỳ giao diện người dùng chặn nào được hiển thị cho người dùng hay không. Được sử dụng để đo tốc độ khởi động của các ứng dụng Office và dung lượng bộ nhớ mà chúng sử dụng khi khởi động, để đảm bảo có trải nghiệm người dùng có thể chấp nhận được.

Các trường sau đây sẽ được thu thập:

  - **ActivationKind** - Ứng dụng đã được khởi động bằng cách khởi chạy từ menu Bắt đầu, bằng cách mở tệp hay thông qua Tự động hoá OLE.

  - **FirstBoot** - Đây có phải là lần khởi động đầu tiên của ứng dụng hay không.

  - **InitializationDuration** - Khoảng thời gian tính bằng micrô giây cần để khởi tạo quy trình Office trước.

  - **InterruptionMessageId** - Nếu khởi động bị gián đoạn bởi hộp thoại yêu cầu thông tin nhập của người dùng của người dùng, ID của hộp thoại.

  - **TotalWorkingSetMB** - Dung lượng bộ nhớ tính bằng megabyte trong bộ làm việc của quy trình.

  - **VirtualSetMB** - Dung lượng bộ nhớ tính bằng megabyte trong bộ ảo của quy trình. (Chỉ dành cho MacOS/iOS)

  - **WorkingSetPeakMB** - Dung lượng bộ nhớ lớn nhất tính bằng megabyte đã từng có từ trước đến nay trong bộ làm việc của quy trình.

#### <a name="officeuxofficeinsidercanshowofficeinsiderslab"></a>Office.UX.OfficeInsider.CanShowOfficeInsiderSlab

Hoạt động theo dõi xem liệu trình Người dùng nội bộ Office có thể được hiển thị cho người dùng trên tab Tài khoản trong giao diện người dùng Backstage Office hay không.

Các trường sau đây sẽ được thu thập:

  - **Data_CanShow** - Cho biết liệu trình Người dùng nội bộ Office có thể được hiển thị cho người dùng trên tab Tài khoản trong giao diện người dùng Backstage Office hay không.
  
  - **Data_Event** - Chưa được sử dụng

  - **Data_EventInfo** - Chưa được sử dụng

  - **Data_Reason** - Chưa được sử dụng

#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a>Office. UX. OfficeInsider. ShowOfficeInsiderDlg

Hoạt động theo dõi việc sử dụng và hiệu suất của hộp thoại Người dùng nội bộ Office.

Các trường sau đây sẽ được thu thập:

  - **Data_AcceptedContactMeNew** - Khi chọn tham gia cấp độ Người dùng nội bộ và khi lựa chọn của người dùng được ghi lại thành công, cho biết liệu người dùng có chấp nhận để được Microsoft liên hệ hay không.

  - **Data_DialogChoice** = Chưa được sử dụng
  
  - **Data_DialogId** = Chưa được sử dụng
  
  - **Data_Event** - Chưa được sử dụng
  
  - **Data_EventInfo** - Chưa được sử dụng
  
  - **Data_InsiderLevel** - Cấp độ Người dùng nội bộ khi hộp thoại được hiển thị lần đầu tiên cho người dùng.
  
  - **Data_InsiderLevelNew** - Cấp độ Người dùng nội bộ mới được người dùng chọn.
  
  - **Data_IsInternalUser** - Cho biết ứng dụng có chạy dưới thông tin đăng nhập của tài khoản @microsoft.com hay không.
  
  - **Data_IsInternalUserInit** - Cho biết liệu mã có thể xác định xem liệu ứng dụng có chạy dưới thông tin đăng nhập của tài khoản @microsoft.com hay không.
  
  - **Data_OpenNewsletterWebpage** - Khi tính năng Đăng ký Bản tin Người dùng nội bộ Office được bật và người dùng chuyển sang cấp độ Người dùng nội bộ từ Sản xuất, cho biết liệu dẫn hướng trình duyệt đến liên kết Đăng ký Bản tin Người dùng nội bộ Office đã được kích hoạt hay chưa.

#### <a name="officevisiosharedvisiofilerender"></a>Office.Visio.Shared.VisioFileRender

Sự kiện này ghi lại thời gian kết xuất tệp. Sự kiện này giúp chúng tôi duy trì việc kiểm tra hiệu suất kết xuất tệp.

Các trường sau đây sẽ được thu thập:

  - **Data\_AvgTime: integer** - Thời gian trung bình để hiển thị hình vẽ Visio trong một phiên

  - **Data\_CompositeSurfEnabled: bool** - True là chế độ kết xuất tổng hợp được bật

  - **Data\_Count: integer** - Số lần Visio kết xuất bản vẽ trong một phiên

  - **Data\_FirstRenderTime: long** - Khoảng thời gian để kết xuất tệp khi khởi chạy lần đầu tiên tính bằng mili giây

  - **Data\_AvgTime: integer** - Thời gian trung bình để hiển thị hình vẽ Visio trong một phiên

#### <a name="officevisiovisiofileopenreliability"></a>Office.Visio.VisioFileOpenReliability

Sự kiện này thu thập dữ liệu hiệu suất Mở tệp cho Visio Dev16. Sự kiện này được sử dụng để theo dõi hiệu suất của Tệp mở và liên kết nó với các thuộc tính tệp như kích thước tệp cho Visio Dev16. Thuộc tính tệp cho phép chúng tôi gỡ lỗi và truy ra được nguyên nhân nhanh hơn.

Các trường sau đây sẽ được thu thập:

  - **Data\_CorrelationId: string -** Mã định danh tương quan tài liệu

  - **Data\_DocIsEnterpriseProtected: bool -** True nếu tài liệu được bảo vệ với Bảo vệ thông tin Windows

  - **Data\_DocumentId: string -** GUID hoặc đường dẫn tệp

  - **Data\_DurationToCompleteInMilliseconds: double -** Khoảng thời gian để hoàn thành quá trình lưu dưới dạng tính bằng mili giây

  - **Data\_DurationToCompleteInMillisecondsSquared: double -** Giá trị bình phương cho DurationToCompleteInMilliseconds

  - **Data\_ErrorCode: integer -** Mã lỗi nội bộ cho lỗi mở tệp

  - **Data\_Extension\_Docs: string -** Phần mở rộng tệp của sơ đồ đã mở

  - **Data\_FileIOBytesRead: int -** Tổng số byte đọc trong khi lưu

  - **Data\_FileIOBytesReadSquared: int -** Giá trị bình phương của dữ liệu\_FileIOBytesRead

  - **Data\_FileIOBytesWritten:int -** Tổng số byte được ghi trong khi lưu

  - **Data\_FileIOBytesWrittenSquared:int-** Giá trị bình phương của dữ liệu\_FileIOBytesWritten

  - **Data\_FileName: binary -** Hàm băm nhị phân của tên tệp

  - **Data\_FileOpenDownloadDurationInMs: long -** Khoảng thời gian để tải xuống tệp tính bằng mili giây

  - **Data\_FileOpenEndDurationInMs: long: -** Khoảng thời gian để mở tệp tính bằng mili giây

  - **Data\_FileOpenTimeStamp: time: -** Dấu thời gian khi tệp bắt đầu mở

  - **Data\_FilePathHash: binary - ** GUID cho đường dẫn tệp

  - **Data\_FileSize: long -** Kích cỡ tài liệu tính bằng byte

  - **Data\_FileType: string -** Phần mở rộng tệp của sơ đồ đã mở

  - **Data\_IsInternalFile: bool -** True nếu tệp là một tệp nội bộ. Ví dụ: mẫu tô

  - **Data\_IsIRM: bool -** True nếu tệp được bảo vệ Quyền Thông tin

  - **Data\_IsReadOnly: bool -** True nếu tệp ở chế độ chỉ đọc

  - **Data\_IsSuccess: bool -** True khi mở tệp thành công

  - **Data\_Location: string -** Vị trí của tệp như Local, SharePoint, OneDrive, WopiConsumer, WopiBusiness, GenericThirdPartyConsumer

  - **Data\_NetworkIOBytesRead:int -** Tổng số byte đọc trong khi lưu

  - **Data\_NetworkIOBytesReadSquared:int -** Giá trị bình phương của dữ liệu\_NetworkIOBytesRead

  - **Data\_FileIOBytesWritten:int -** Tổng số byte được ghi trong khi lưu

  - **Data\_FileIOBytesWrittenSquared:int-** Giá trị bình phương của NetworkIOBytesWritten

  - **Data\_OpenLocation: integer -** Vị trí của tệp mà nó được mở 0 - Cục bộ, 1 - Mạng, 2 - SharePoint, 3 - Web

  - **Data\_Size\_Docs: integer -** Tài liệu kích cỡ tính bằng byte

  - **Data\_Tag:string -** Mã định danh duy nhất để xác định sự kiện Lưu dưới dạng

  - **Data\_WasSuccessful: bool -** True nếu quá trình mở dưới dạng được thực hiện thành công

### <a name="application-activity-error-subtype"></a>*Loại con lỗi hoạt động ứng dụng*

Lỗi về chức năng của một tính năng hoặc trải nghiệm người dùng.

#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Giúp Microsoft tách rời trình điều khiển card màn hình dài từ các trình điều khiển ngắn, điều này giúp đưa ra quyết định về trình điều khiển card màn hình có thể gặp sự cố. Trình điều khiển card màn hình của người dùng đã khiến Office bị treo, nhưng tác động của việc treo vẫn chưa được biết đến

Các trường sau đây sẽ được thu thập:

  - **Data\_InDeviceCall** - Phương thức được gọi trên card màn hình đã tạo ra sự cố treo

  - **Data\_Timeout** - Thời gian kéo dài sự cố treo

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Thông tin báo cáo ngoại lệ này rất quan trọng để đánh giá trạng thái tổng thể của ngăn xếp đồ họa, cũng như xác định các phần của mã nơi xảy ra lỗi ở tần suất cao, để ưu tiên việc điều tra. Thông tin báo cáo ngoại lệ này rất quan trọng để đánh giá trạng thái tổng thể của ngăn xếp đồ họa, cũng như xác định các phần của mã nơi xảy ra lỗi ở tần suất cao. Điều này giúp các kỹ sư có thể xác định những lỗi kết xuất đang ảnh hưởng đến hầu hết người dùng, cho phép chúng tôi ưu tiên điều tra để khắc phục các sự cố sẽ mang lại lợi ích cao nhất cho người dùng.

Các trường sau đây sẽ được thu thập:

  - **Data\_HResult** - Mã lỗi được trả về từ lỗi

  - **Data\_TagCount** - Số lần từng lỗi xảy ra

  - **Data\_TagID** - Mã định danh của sự cố đã xảy ra

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfoldererror"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Error

Thu thập thông tin khi bất kỳ lỗi xảy ra khi trong khi dẫn hướng đến lịch dùng chung. Dữ liệu này được sử dụng để theo dõi trạng thái của API chia sẻ lịch cũng như tương tác của Outlook với lịch dùng chung.

Các trường sau đây sẽ được thu thập:

  - **FailedCaseHResult** - Mã lỗi được trả về từ lỗi

#### <a name="officeoutlookdesktopedpedpopenstorefailure"></a>Office.Outlook.Desktop.EDP.EDPOpenStoreFailure

Thành công hay thất bại khi mở lưu trữ thư được bảo vệ Bảo vệ Dữ liệu Doanh nghiệp dựa trên kết quả của lệnh gọi Windows API để lấy khóa nhằm giải mã lưu trữ. Chúng tôi sử dụng thao tác này để chẩn đoán một trong những sự cố Bảo vệ Dữ liệu Doanh nghiệp hàng đầu có thể ngăn Outlook khởi động. Nguyên nhân chính gây ra lỗi là sự tương tác của Outlook với API Windows được sử dụng để giải mã khóa lưu trữ.

Các trường sau đây sẽ được thu thập:

  - **Hoạt dộng HVA** **-** với các trường dữ liệu tùy chỉnh

  - **IsFlightOn** – Cho biết liệu EDPDecryption Flight có được bật không

#### <a name="officeoutlookdesktopndbcorruptionresult"></a>Office.Outlook.Desktop.NdbCorruptionResult

Office.Outlook.Desktop.NdbCorruptionResult và Office.Outlook.Desktop.NDBCorruptStore. Cảnh báo được thu thập khi chúng tôi phát hiện lỗi trong PST/OST của người dùng. Khi chúng tôi phát hiện lỗi, Microsoft sẽ thu thập định dạng của cơ sở dữ liệu, nơi phát hiện ra cơ sở dữ liệu và một lượng nhỏ bối cảnh về lỗi. Lỗi OST/PST ngăn người dùng truy nhập vào email của họ. Chúng tôi tích cực giám sát dữ liệu này cho các hoạt động bất thường. Chúng tôi mong muốn điều tra và chẩn đoán các sự cố để hạn chế việc mất dữ liệu của khách hàng.

Các trường sau đây sẽ được thu thập:

  - **0 -** Tên quy trình báo cáo lỗi

  - **1 -** Bool cho biết người dùng có chọn tệp mới hay không

  - **2 -** Số lượng quy trình khác có cơ sở dữ liệu mở

#### <a name="officeoutlookdesktopndbcorruptstorewarning"></a>Office.Outlook.Desktop.NDBCorruptStore.Warning

Office.Outlook.Desktop.NdbCorruptionResult và Office.Outlook.Desktop.NDBCorruptStore. Cảnh báo được thu thập khi chúng tôi phát hiện lỗi trong PST/OST của người dùng. Khi chúng tôi phát hiện lỗi, Microsoft sẽ thu thập định dạng của cơ sở dữ liệu, nơi phát hiện ra cơ sở dữ liệu và một lượng nhỏ bối cảnh về lỗi. Lỗi OST/PST ngăn người dùng truy nhập vào email của họ. Chúng tôi tích cực giám sát dữ liệu này cho các hoạt động bất thường. Chúng tôi mong muốn điều tra và chẩn đoán các sự cố để hạn chế việc mất dữ liệu của khách hàng.

Các trường sau đây sẽ được thu thập:

  - **CollectionTime** - Thời gian thu thập

  - **Context** - Ngữ cảnh lưu trữ lỗi, nơi phát hiện lỗi

  - **CreatedWithVersion** – (Tùy chọn) trường với phiên bản lưu trữ

  - **Details** – Chi tiết về sự cố

  - **NdbType** - Loại lưu trữ, có thể bằng 0 = NdbUndefined, 1 = NdbSmall, 2 = NdbLarge, 3 = NdbTardis

  - **ProcessName** - Tên quy trình khiến lưu trữ bị lỗi

  - **PstVersion** - Phiên bản của MSPST32.DLL

  - **Version** - Phiên bản định dạng tệp lưu trữ

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptforwardactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ForwardActions.Rule.O16

Thu thập thành công và thất bại của Chuyển tiếp, Chuyển tiếp dưới dạng tệp đính kèm và Chuyển tiếp dưới dạng thao tác iCalWiki cho các Phản hồi cuộc họp đơn, định kỳ và ngoại lệ trong Thư, Lịch và dạng xem Giám định viên Outlook. Tỷ lệ lỗi của Chuyển tiếp, Chuyển tiếp dưới dạng Đính kèm và Chuyển tiếp khi các hành động của iCalWiki được theo dõi tích cực cho các bất thường. Thống kê bất thường cho thấy khả năng Outlook thất bại trong việc thực hiện các thao tác lịch cốt lõi. Dữ liệu này cũng được sử dụng để chẩn đoán các vấn đề khác liên quan đến Lịch có thể được phát hiện.

Các trường sau đây sẽ được thu thập:

  - **CountExceptionForward- Số lượng Ngoại lệ Cuộc họp được chuyển tiếp**

  - **CountExceptionForwardAsiCal- Số lượng Ngoại lệ Cuộc họp được chuyển tiếp dưới dạng iCal**

  - **CountExceptionForwardInSplit- Số lượng Ngoại lệ Cuộc họp được chuyển tiếp từ menu Tách trong Dải băng**

  - **CountExceptionForwardWithAttach- Số lượng Ngoại lệ Cuộc họp được chuyển tiếp dưới dạng tệp đính kèm**

  - **CountRecurringForward - Số lượng cuộc họp định kỳ chuyển tiếp**

  - **CountRecurringForwardAsiCal - Số lượng cuộc họp định kỳ chuyển tiếp dưới dạng iCal**

  - **CountRecurringForwardInSplit**- Số lượng cuộc họp định kỳ chuyển tiếp từ menu Tách trong Dải băng

  - **CountRecurringForwardWithAttach- Số lượng cuộc họp định kỳ chuyển tiếp dưới dạng tệp đính kèm**

  - **CountSingleForward - Số lượng Cuộc họp Đơn chuyển tiếp**

  - **CountSingleForwardAsiCal - Số lượng Cuộc họp Đơn chuyển tiếp dưới dạng iCal**

  - **CountSingleForwardInSplit- Số lượng Cuộc họp Đơn được chuyển tiếp từ menu Tách trong Dải băng**

  - **CountSingleForwardWithAttach - Số lượng Cuộc họp Đơn chuyển tiếp dưới dạng tệp đính kèm**

  - **HResult - ErrorCode**

  - **OlkViewName -- Cho biết Thư, Lịch hoặc Dạng xem Giám định viên**

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16

Thu thập thành công và thất bại của Trả lời, Trả lời Tất cả, Trả lời bằng IM và Trả lời Tất cả bằng thao tác tin nhắn tức thời (IM) cho các Phản hồi Cuộc họp Đơn, Định kỳ và Ngoại lệ trong Thư, Lịch hoặc Dạng xem Giám định viên Outlook. Tỷ lệ thất bại của Trả lời, Trả lời Tất cả, Trả lời bằng tin nhắn tức thời (IM) và Trả lời Tất cả bằng các thao tác IM được theo dõi tích cực cho các bất thường. Thống kê bất thường cho thấy khả năng Outlook thất bại trong việc thực hiện các thao tác lịch cốt lõi. Dữ liệu này cũng được sử dụng để chẩn đoán các vấn đề khác liên quan đến Lịch có thể được phát hiện.

Các trường sau đây sẽ được thu thập:

  - **CountExceptionReply - Số lượng thư trả lời cuộc họp cho các trường hợp ngoại lệ**

  - **CountExceptionReplyAll - Số lượng trả lời tất cả cho cuộc họp cho các trường hợp ngoại lệ**

  - **CountExceptionReplyAllWithIM - Số lượng trả lời tất cả cho cuộc họp với tin nhắn tức thời (IM) cho các trường hợp ngoại lệ**

  - **CountExceptionReplyWithIM- Số lượng trả lời cuộc họp với tin nhắn tức thời (IM) cho các trường hợp ngoại lệ**

  - **CountRecurringReply - Số lượng trả lời cuộc họp định kỳ**

  - **CountRecurringReplyAll- Số lượng trả lời tất cả cho cuộc họp định kỳ**

  - **CountRecurringReplyAllWithIM- Số lượng trả lời tất cả cho cuộc họp định kỳ với tin nhắn tức thời (IM) cho các trường hợp ngoại lệ**

  - **CountRecurringReplyWithIM- Số lượng trả lời cuộc họp định kỳ với tin nhắn tức thời (IM)**

  - **CountSingleReply- Số lượng trả lời cuộc họp đơn**

  - **CountSingleReplyAll- Số lượng trả lời tất cả cho cuộc họp đơn**

  - **CountSingleReplyAll- Số lượng trả lời tất cả cho cuộc họp đơn**

  - **CountSingleReplyWithIM- Số lượng trả lời cuộc họp đơn với tin nhắn tức thời (IM)**

  - **HResult - ErrorCode**

  - **OlkViewName -- Cho biết Thư, Lịch hoặc Dạng xem Giám định viên**

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a>Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail

Quy tắc này thu thập các lỗi Chia sẻ lịch khi thêm người dùng mới (loại EX hoặc SMTP) từ sổ Địa chỉ. Dữ liệu này được sử dụng để chẩn đoán và giải quyết các sự cố được phát hiện trong hộp thoại Chia sẻ lịch

Các trường sau đây sẽ được thu thập:

  - **CountAccountWizardEnd** - Số lần hộp thoại trình hướng dẫn kế thừa kết thúc

  - **CountCreatePIMAccount** - Đã bao nhiêu lần người dùng tạo Hồ sơ PIM

#### <a name="officesystemsystemhealthasserts"></a>Office.System.SystemHealthAsserts

Các lỗi mà sự kiện này xác định giúp chúng tôi hiểu khi trải nghiệm của khách hàng đang xuống cấp. Nhiều trong số các ShipAsserts này dẫn đến sự cố và thông tin này giúp khắc phục nhiều lỗi trong số đó. Thu thập ShipAsserts từ sản phẩm giúp xác định lỗi.

Các trường sau đây sẽ được thu thập:

Count – Số lượng từng xác nhận được báo cáo

  - **EndTime** – Thời gian mà tại đó xác nhận cuối cùng được báo cáo xảy ra

  - **ErrorGroup** – Mã định danh bucketing cho từng xác nhận

  - **FirstTimeStamp** – Lần đầu tiên mà tại đó xác nhận xảy ra

  - **Trackback** – Mã định danh duy nhất cho một xác nhận cụ thể

#### <a name="officesystemsystemhealtherrorsetwshim"></a>Office.System.SystemHealthErrorsEtwShim

Được sử dụng để xác định các sự cố ảnh hưởng đến khách hàng trong ứng dụng đang chạy có thể biểu hiện là sự cố hoặc chức năng bị xuống cấp. Ghi lại các lỗi xảy ra trong thời gian chạy quy trình.

Các trường sau đây sẽ được thu thập:

  - **EndTime** – Thời gian mà tại đó lỗi cuối cùng được báo cáo xảy ra

  - **Trackback** – Mã định danh duy nhất cho một lỗi cụ thể

  - **ErrorGroup** – Mã định danh bucketing cho từng lỗi

  - **Count** – Số lượng từng lỗi

  - **FirstTimeStamp** – Lần đầu tiên mà tại đó lỗi xảy ra

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a>Office.System.SystemHealthErrorsUlsAndAsserts

Được sử dụng để xác định các sự cố ảnh hưởng đến khách hàng trong ứng dụng đang chạy có thể biểu hiện là sự cố hoặc chức năng bị xuống cấp. Ghi lại các lỗi xảy ra trong thời gian chạy quy trình.

Các trường sau đây sẽ được thu thập:

  - **EndTime** – Thời gian mà tại đó lỗi cuối cùng được báo cáo xảy ra

  - **Trackback** – Mã định danh duy nhất cho một lỗi cụ thể

  - **ErrorGroup** – Mã định danh bucketing cho từng lỗi

  - **Count** – Số lượng từng lỗi

  - **FirstTimeStamp** – Lần đầu tiên mà tại đó lỗi xảy ra

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a>Office.System.SystemHealthErrorsUlsWorkaround

Được sử dụng để xác định các sự cố ảnh hưởng đến khách hàng trong ứng dụng đang chạy có thể biểu hiện là sự cố hoặc chức năng bị xuống cấp. Ghi lại các lỗi xảy ra trong thời gian chạy quy trình

Các trường sau đây sẽ được thu thập:

  - **EndTime** – Thời gian mà tại đó lỗi cuối cùng được báo cáo xảy ra

  - **Trackback** – Mã định danh duy nhất cho một lỗi cụ thể

  - **ErrorGroup** – Mã định danh bucketing cho từng lỗi

  - **Count** – Số lượng từng lỗi

#### <a name="officesystemsystemhealtherrorswithouttag"></a>Office.System.SystemHealthErrorsWithoutTag

Được sử dụng để xác định các sự cố ảnh hưởng đến khách hàng trong ứng dụng đang chạy có thể biểu hiện là sự cố hoặc chức năng bị xuống cấp. Ghi lại các lỗi xảy ra trong thời gian chạy quy trình.

Các trường sau đây sẽ được thu thập:

Count – Số lượng từng lỗi

  - **EndTime** – Thời gian mà tại đó lỗi cuối cùng được báo cáo xảy ra

  - **ErrorCode** – Mã định danh lỗi

  - **ErrorGroup** – Mã định danh bucketing cho từng lỗi

  - **ErrorCode** – Mã định danh lỗi

  - **FirstTimeStamp** – Lần đầu tiên mà tại đó lỗi xảy ra

  - **Trackback** – Mã định danh duy nhất cho một lỗi cụ thể

#### <a name="officesystemsystemhealtherrorswithtag"></a>Office.System.SystemHealthErrorsWithTag

Được sử dụng để xác định các sự cố ảnh hưởng đến khách hàng trong ứng dụng đang chạy có thể biểu hiện là sự cố hoặc chức năng bị xuống cấp. Ghi lại các lỗi xảy ra trong thời gian chạy quy trình.

Các trường sau đây sẽ được thu thập:

  - **Count** – Số lượng từng lỗi

  - **EndTime** – Thời gian mà tại đó lỗi cuối cùng được báo cáo xảy ra

  - **ErrorCode** – Mã định danh lỗi

  - **ErrorGroup** – Mã định danh bucketing cho từng lỗi

  - **ErrorCode** – Mã định danh lỗi

  - **FirstTimeStamp** – Lần đầu tiên mà tại đó lỗi xảy ra

  - **Trackback** – Mã định danh duy nhất cho một lỗi cụ thể

## <a name="device-connectivity-and-configuration-data-events"></a>Sự kiện dữ liệu cấu hình và kết nối thiết bị

Sau đây là những loại dữ liệu con trong danh mục này:

- [Khả năng kết nối và cấu hình thiết bị](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Loại con của hả năng kết nối và cấu hình thiết bị*

Trạng thái kết nối mạng và cài đặt thiết bị, chẳng hạn như bộ nhớ.

#### <a name="officeairspaceairspacelocalblocklistdriverupdated"></a>Office.AirSpace.AirSpaceLocalBlocklistDriverUpdated

Người dùng đã cập nhật trình điều khiển card màn hình trước đây đã gây ra sự cố Office và do đó không còn được sử dụng để kết xuất. Thông báo cho Microsoft rằng người dùng đã từng ở trạng thái kết xuất phụ tối ưu lại một lần nữa ở trạng thái kết xuất được đề xuất.

Các trường sau đây sẽ được thu thập:

  - **Data\_BlockedDriverVersion** - Phiên bản của trình điều khiển đã được đưa vào danh sách bị chặn.

  - **Data\_DeviceId** - Mã định danh của thiết bị card màn hình đã được đưa vào danh sách bị chặn.

  - **Data\_UpdatedDriverVersion** - Phiên bản trình điều khiển được cập nhật

#### <a name="officeairspaceairspacelocalblocklistinfo"></a>Office.AirSpace.AirSpaceLocalBlocklistInfo

Chi tiết về các điều khiển card màn hình của người dùng phát sinh do nhiều sự cố gần đây của ứng dụng Office. Office sẽ không sử dụng card màn hình này trong phiên Office này (thay vào đó sử dụng kết xuất phần mềm) cho đến khi trình điều khiển được cập nhật. Thông báo cho Microsoft về trình điều khiển card màn hình đang gây ra sự cố trong Office để có thể xác định xu hướng và người dùng có thể phân tích tác động của các trình điều khiển đó. Thông báo cho Microsoft biết số lượng người dùng ở trạng thái tối ưu phụ này.

Các trường sau đây sẽ được thu thập:

  - **Data\_AllAppsBlocked** - Tất cả các ứng dụng Office có nằm trong danh sách bị chặn hay không

  - **Data\_BlockedDeviceId** - Mã định danh của thiết bị card màn hình đã được đưa vào danh sách bị chặn.

  - **Data\_BlockedDriverVersion** - Phiên bản của trình điều khiển đã được đưa vào danh sách bị chặn

  - **Data\_CrashHistory** - Chuỗi đại diện cho lịch sử trình điều khiển card màn hình gây ra sự cố để phân tích

  - **Data\_SecsBetweenCrashes** - Tần suất card trình điều khiển xảy ra sự cố

#### <a name="officeairspaceairspacewincompisenabled"></a>Office.AirSpace.AirSpaceWinCompIsEnabled

Nền tảng kết xuất cấp thấp mới nhất của Office dựa trên cấu phần Windows có được sử dụng hay không.

Khi nền tảng kết xuất cấp thấp mới nhất của Office được phát triển và bắt đầu được phát hành cho khách hàng, điều này sẽ cho phép Microsoft xem có bao nhiêu người dùng trên mỗi phiên bản để đảm bảo nền tảng này không có lỗi.

Các trường sau đây sẽ được thu thập:

  - **Data\_WinCompEnabled** - Thiết bị phụ trợ dựa trên cấu phần Windows có được sử dụng hay không

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorblocklistapp"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorBlocklistApp

Card màn hình của người dùng đã được phát hiện là nguyên nhân gây sự cố treo lâu hoặc không thể phục hồi. Office sẽ không sử dụng card màn hình này trong phiên Office này (thay vào đó sử dụng kết xuất phần mềm) cho đến khi trình điều khiển được cập nhật. Thông báo cho Microsoft về trình điều khiển card màn hình đang gây ra sự cố trong Office để có thể xác định xu hướng và người dùng có thể phân tích tác động của các trình điều khiển đó. Đồng thời giúp thông báo số lượng người dùng ở trạng thái tối ưu phụ này.

Các trường sau đây sẽ được thu thập:

  - **Data\_AppName** - Ứng dụng đã gặp phải sự cố trình điều khiển card màn hình bị treo

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorregistrywrite"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorRegistryWrite

Office đã xác định rằng trình điều khiển card màn hình của người dùng đã gây ra sự cố treo cần được phân tích trong lần khởi động ứng dụng Office tiếp theo. Được sử dụng để xác định xem việc sử dụng trình điều khiển hoặc bộ điều hợp card màn hình khác nhau sẽ mang lại trải nghiệm tốt hơn cho người dùng. Khi các mẫu xảy ra, Microsoft có thể thực hiện các điều chỉnh để duy trì trải nghiệm Office mượt mà nhất có thể.

Các trường sau đây sẽ được thu thập:

  - **Data\_HangDetected** - Sự cố treo có được phát hiện hay không

  - **Data\_InDeviceCall** - Lệnh gọi kết xuất card màn hình mà Office đã ở trong đó khi sự cố treo xảy ra

  - **Data\_Timeout** - Thời gian kéo dài sự cố treo nếu nó khôi phục

  - **Data\_UnrecoverableCommand** - Sự cố treo trong lệnh kết xuất card màn hình này thường có thể phục hồi được hay không.

#### <a name="officeairspacebackendwin32localblocklistactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistActivity

Chi tiết về các điều khiển card màn hình của người dùng phát sinh do nhiều sự cố gần đây của ứng dụng Office. Office sẽ không sử dụng card màn hình này trong phiên Office này (thay vào đó sử dụng kết xuất phần mềm) cho đến khi trình điều khiển được cập nhật. Thông báo cho Microsoft về trình điều khiển card màn hình đang gây ra sự cố trong Office để có thể xác định xu hướng và người dùng có thể phân tích tác động của các trình điều khiển đó. Thông báo cho Microsoft biết số lượng người dùng ở trạng thái tối ưu phụ này.

Các trường sau đây sẽ được thu thập:

  - **Data.AllAppsBlocked** - Tất cả các ứng dụng Office có nằm trong danh sách bị chặn hay không

  - **Data.BlockedDeviceId** - Mã định danh của thiết bị card màn hình đã bị chặn

  - **Data.BlockedDriverVersion** - Phiên bản của trình điều khiển đã được đưa vào danh sách bị chặn

  - **Data.CrashHistory System.String** - Chuỗi đại diện cho lịch sử trình điều khiển card màn hình gây ra sự cố để phân tích

  - **Data.SecsBetweenCrashes** - Tần suất card trình điều khiển xảy ra sự cố

#### <a name="officeairspacebackendwin32localblocklistdriverupdatedactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistDriverUpdatedActivity

Người dùng đã cập nhật trình điều khiển card màn hình trước đây đã gây ra sự cố Office và do đó không còn được sử dụng để kết xuất. Thông báo cho Microsoft rằng người dùng đã từng ở trạng thái kết xuất phụ tối ưu lại một lần nữa ở trạng thái kết xuất được đề xuất.

Các trường sau đây sẽ được thu thập:

  - **Data\_BlockedDeviceId** - Mã định danh của thiết bị card màn hình đã được đưa vào danh sách bị chặn.

  - **Data\_BlockedDriverVersion** - Phiên bản của trình điều khiển đã được đưa vào danh sách bị chặn

  - **Data\_UpdatedDriverVersion** - Phiên bản trình điều khiển được cập nhật

#### <a name="officegraphicsspritememcorrupt"></a>Office.Graphics.SpriteMemCorrupt

Báo cáo bất kỳ lỗi nào được phát hiện trong phép đo từ xa kế toán bộ nhớ sprite. Quan trọng để đánh giá trạng thái của phép đo từ xa sử dụng bộ nhớ đồ họa. Thông tin này là cần thiết để xác thực tính chính xác của phép đo từ xa SpriteMem của chúng tôi.

Các trường sau đây sẽ được thu thập:

  - **Data\_CurrentSpriteMem** - Tổng dung lượng bộ nhớ được phân bổ tích cực để giữ sprite (hình ảnh) dẫn đến nội dung màn hình.

  - **Data\_Function** - Tên của hàm đang cố gắng giải phóng bộ nhớ sprite.

  - **Data\_SpriteMemToRemove** - Số lượng bộ nhớ được loại bỏ khỏi phân bổ sprite.

#### <a name="officepowerpointpptsharednointernetconnectivity"></a>Office.PowerPoint.PPT.Shared.NoInternetConnectivity

Thu thập bất cứ khi nào PowerPoint phát hiện không có kết nối internet. Microsoft sử dụng dữ liệu này để có được thông tin chẩn đoán về kết nối internet của người dùng để có thể hiểu cách điều đó tác động đến kết nối với các dịch vụ Office.

Các trường sau đây sẽ được thu thập:

- **Data\_IsNexusDetected:bool** - Cho biết liệu chúng tôi có trạng thái kết nối Internet khi gọi dịch vụ Nexus (giá trị đúng) hay khi gọi lệnh gọi API dịch vụ web chung (giá trị sai)
