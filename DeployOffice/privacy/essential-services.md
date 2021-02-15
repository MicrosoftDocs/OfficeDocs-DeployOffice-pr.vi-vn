---
title: Dịch vụ cần thiết cho Office
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
description: Cung cấp cho người quản trị Office thông tin về các dịch vụ cần thiết trong Office, chẳng hạn như Click-to-Run và Cấp phép và cung cấp danh sách các sự kiện và trường dữ liệu cho các dịch vụ cần thiết đó.
hideEdit: true
ms.openlocfilehash: 7660e79628e31b17fb2b1c606378391419f15e8e
ms.sourcegitcommit: 163de1916420d26e4a0ef9de941fc4e86ade0412
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 02/14/2021
ms.locfileid: "50242176"
---
# <a name="essential-services-for-office"></a>Dịch vụ cần thiết cho Office

> [!NOTE]
> Để biết danh sách các sản phẩm Office nằm trong thông tin về quyền riêng tư này, hãy xem [Kiểm soát về quyền riêng tư sẵn có cho các sản phẩm Office](products-versions-privacy-controls.md).

Office bao gồm các ứng dụng phần mềm máy khách và trải nghiệm được kết nối được thiết kế để hỗ trợ bạn sáng tạo, giao tiếp và cộng tác một cách hiệu quả hơn. Mặc dù bạn có thể kiểm soát nhiều trải nghiệm được kết nối sẵn dùng cho bạn hoặc cho người dùng của bạn nếu bạn là người quản trị trong tổ chức của mình, nhưng vẫn có một bộ dịch vụ rất cần thiết cho cách thức Office làm việc và do đó nó không vô hiệu hóa. Ví dụ: dịch vụ cấp phép xác nhận bạn được cấp phép sử dụng Office đúng cách. Dữ liệu dịch vụ bắt buộc về các dịch vụ này sẽ được thu thập và gửi đến Microsoft mà không phụ thuộc vào bất cứ thiết đặt chính sách liên quan nào khác mà bạn đã đặt cấu hình.

Để biết thêm thông tin, hãy xem các bài viết sau đây:

- [Dữ liệu dịch vụ bắt buộc cho Office](required-service-data.md)
- [Các trải nghiệm kết nối trong Office](connected-experiences.md)

Nếu bạn là người quản trị cho tổ chức của mình, bạn cũng có thể quan tâm đến các bài viết sau:

- [Tổng quan về các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](overview-privacy-controls.md)
- [Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư đối với Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn](manage-privacy-controls.md)
- [Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office cho Mac](mac-privacy-preferences.md)
- [Sử dụng tùy chọn để quản lý kiểm soát quyền riêng tư cho Office trên thiết bị iOS](ios-privacy-preferences.md)
- [Sử dụng cài đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên thiết bị Android](android-privacy-controls.md)
- [Sử dụng thiết đặt chính sách để quản lý các biện pháp kiểm soát quyền riêng tư cho Office trên ứng dụng web](office-web-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Danh sách các dịch vụ cần thiết cho Office 

Bảng sau đây cung cấp danh sách các dịch vụ cần thiết cho Office và mô tả của từng dịch vụ.

| **Service**  | **Mô tả**  |
| ------ | ---- |
| [Xác thực](#authentication-events) | Xác thực là một dịch vụ đa nền tảng xác thực danh tính người dùng Office của bạn.  Nó là điều bắt buộc để cho phép bạn đăng nhập vào Office, kích hoạt giấy phép Office, truy nhập các tệp được lưu trữ trên đám mây và cung cấp trải nghiệm nhất quán trên các phiên Office và thiết bị của bạn.    |
| [Click-to-Run](#click-to-run-events) | Click-to-Run là công nghệ cài đặt được sử dụng để cài đặt và cập nhật Office trên Windows. Công nghệ này kiểm tra các phiên bản mới của Office và tải xuống và cài đặt khi có phiên bản mới. Click-to-Run sẽ phát hiện nhu cầu, thực hiện tải xuống và cài đặt các bản cập nhật Office, bao gồm các bản cập nhật bảo mật.     |
| [Dịch vụ cấu hình nâng cao (ECS)](#enhanced-configuration-service-ecs-events) | ECS cung cấp cho Microsoft khả năng cấu hình lại các bản cài đặt Office mà không cần bạn phải triển khai lại Office. Dịch vụ này được sử dụng để kiểm soát việc triển khai dần các tính năng hoặc bản cập nhật, trong khi ảnh hưởng của việc triển khai được theo dõi từ dữ liệu chẩn đoán được thu thập. Nó cũng được sử dụng để giảm thiểu các vấn đề về bảo mật hoặc hiệu suất với một tính năng hoặc bản cập nhật. Ngoài ra, ECS còn hỗ trợ thay đổi cấu hình liên quan đến dữ liệu chẩn đoán để giúp đảm bảo rằng các sự kiện thích hợp sẽ được thu thập. |
| [Cấp phép](#licensing-events)     | Cấp phép là dịch vụ dựa trên nền điện toán đám mây hỗ trợ kích hoạt Office của bạn để cài đặt mới và duy trì giấy phép trên thiết bị của bạn sau khi Office được kích hoạt. Dịch vụ này đăng ký cho từng thiết bị của bạn, kích hoạt Office, kiểm tra trạng thái đăng ký Office và quản lý khóa của các sản phẩm của bạn.    |
|[Microsoft AutoUpdate (MAU)](#microsoft-autoupdate-mau-events)|Microsoft AutoUpdate (MAU) là công nghệ dùng để cập nhật các ứng dụng Microsoft được làm ra dành cho MacOS, chẳng hạn như Office. MAU sẽ phát hiện nhu cầu, thực hiện tải xuống và cài đặt các bản cập nhật ứng dụng, bao gồm cả các bản cập nhật bảo mật.|
|[Đồng bộ OneNote](#onenote-sync-events)|OneNote cho Mac chỉ hỗ trợ sổ tay được lưu trữ trên Internet trong OneDrive hoặc SharePoint Online. OneNote cho Mac sẽ liên tục đồng bộ hoá mọi ghi chú của người dùng bằng OneDrive hoặc SharePoint Online. Ứng dụng này cho phép người dùng mở, xem và chỉnh sửa sổ tay trên tất cả các thiết bị của mình, nhờ vậy sổ tay luôn được cập nhật.
 [Cấu hình dịch vụ](#services-configuration-events)  | Cấu hình dịch vụ cung cấp khả năng cập nhật các cài đặt cấu hình Office để bật hoặc tắt các tính năng của máy khách. Nó được gọi mỗi khi ứng dụng Office được khởi động và cung cấp chi tiết về các cấu hình và dịch vụ khác của Office. Cấu hình dịch vụ cũng kiểm soát các dịch vụ được chỉ định là dịch vụ cần thiết.  |
| [Phép đo từ xa](#telemetry-events)  | Dịch vụ phép đo từ xa được dùng để thu thập dữ liệu chẩn đoán từ ứng dụng Office. Dịch vụ này cho phép thu thập dữ liệu chẩn đoán do Office tạo ra, gồm cả dữ liệu chẩn đoán bắt buộc lẫn tùy chọn. Nó cũng chịu trách nhiệm thu thập một số dữ liệu dịch vụ bắt buộc cho Office.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Các sự kiện và trường dữ liệu cho các dịch vụ cần thiết cho Office

Phần tiếp theo sẽ cung cấp các thông tin sau đây:

- Danh sách các sự kiện cho từng dịch vụ cần thiết
- Mô tả về từng sự kiện
- Danh sách các trường dữ liệu trong mỗi sự kiện
- Mô tả về từng trường dữ liệu


## <a name="authentication-events"></a>Sự kiện xác thực

Các sự kiện dữ liệu chẩn đoán này được thu thập khi Office cố gắng lấy mã thông báo xác thực, bằng cách âm thầm hoặc thông qua nhắc nhở.

### <a name="officeandroidmsaguesttoaad"></a>Office.Android.MSAGuestToAAD

Sự kiện này giúp biết rõ số lượng người dùng đang nhận được lời nhắc cung cấp mật khẩu cho tài khoản cá nhân trong khi truy nhập vào tài nguyên công việc, vì tài khoản cá nhân của họ có thể là khách hợp lệ để trở thành đối tượng thuê tài khoản cơ quan.

Dữ liệu này giúp chúng tôi biết được số lượng người dùng đang có trải nghiệm khó chịu vì mỗi khi đăng nhập, lại bị nhắc phải ưu tiên mua lại mã thông báo AAD âm thầm dựa trên xác nhận SAML (Ngôn ngữ Đánh dấu Xác nhận Bảo mật) tài khoản Microsoft.

Các trường sau đây sẽ được thu thập:

- **Thẻ** - Biểu thị người dùng nhận được lời nhắc đăng nhập dành cho tài khoản cá nhân trong khi truy nhập tài nguyên của tài khoản cơ quan.


### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Được thu thập khi Office hiển thị cho người dùng lời nhắc đăng nhập xác thực dựa trên biểu mẫu.

Cùng với việc tiếp nhận mã thông báo tĩnh, lời nhắc xác thực được sử dụng để xác định xem người dùng có ở trạng thái xác thực bị lỗi hay không, đối với người dùng, điều này dẫn đến trạng thái Máy khách ngoại tuyến hoặc trong trường hợp xấu nhất, xác thực bị lỗi có thể ngăn chặn việc mua lại giấy phép và dẫn đến việc máy khách hoàn toàn không sử dụng được.

Lời nhắc đăng nhập xác thực dựa trên biểu mẫu (FBA) được sử dụng cho một số tình huống xác thực tại chỗ và thông thường chúng tôi muốn đảm bảo điều này không xảy ra, vì mọi người sẽ sử dụng Xác thực hiện đại do các lỗ hổng bảo mật liên quan đến FBA.

Các trường sau đây sẽ được thu thập:

  - **AuthScheme** - Lược đồ xác thực được sử dụng

  - **DocumentUrlHash** - Yêu cầu URL được mã hóa

  - **EndTag** - Thẻ nơi hoàn tất biểu mẫu FBA

  - **Flags** - Đã lỗi thời

  - **EndTag** - Thẻ nơi bắt đầu biểu mẫu FBA

  - **LastError** – Mã lỗi được trả về

  - **PromptEndTime** - thời gian khi lời nhắc kết thúc

  - **PromptStartTime** - thời gian khi lời nhắc bắt đầu

  - **Result** - Quá trình xác thực có thành công hay không

  - **SessionEndTime** – Thời gian kết thúc phiên sự kiện

  - **Timeout** - Thời gian khi lời nhắc hết thời gian

### <a name="officeidentitysignoutevent"></a>Office.Identity.SignOutEvent

Được thu thập khi người dùng đăng xuất khỏi Office.

Việc biết được người dùng đã đăng xuất giúp phân loại các sự kiện khác, ví dụ: lời nhắc, như dự kiến, để có thể tính toán chính xác những sự kiện này trong các số liệu về độ tin cậy / khả năng sẵn sàng phát hành và tránh cảnh báo hoặc quay lại bản dựng dựa trên cơ sở lỗi mà người dùng đang gặp phải lời nhắc đăng nhập không mong muốn.

Các trường sau đây sẽ được thu thập:

  - **FlowEndTime** - Thời gian khi hành động đăng xuất kết thúc

  - **FlowStartTime** - Thời gian khi hành động đăng xuất bắt đầu

  - **IdentityErrorState** - bất kỳ trạng thái lỗi nhận dạng trong khi đăng xuất

  - **IdentityHashedUniqueId** - ID nhận dạng được mã hóa khi được đăng xuất

  - **IdentityProviderType** - nhà cung cấp danh tính của danh tính được đăng xuất

  - **IdentityUniqueID** - ID danh tính được đăng xuất

  - **SessionEndTime** – Thời gian kết thúc phiên sự kiện

  - **SignOutUserAction** - Cho biết người dùng bắt đầu hành động đăng xuất

### <a name="officeidentitysspipromptwin32"></a>Office.Identity.SspiPromptWin32

Được thu thập khi Office hiển thị cho người dùng lời nhắc đăng nhập Windows SSPI. Cùng với việc tiếp nhận mã thông báo tĩnh, lời nhắc xác thực xác định xem người dùng có ở một trạng thái xác thực bị lỗi hay không, điều này dẫn đến trạng thái Máy khách ngoại tuyến. Xác thực bị lỗi có thể ngăn chặn việc mua lại giấy phép và dẫn đến việc máy khách hoàn toàn không sử dụng được.

Lời nhắc Windows SSPI được sử dụng để xác thực với Exchange (để đồng bộ hóa thư) khi tài nguyên Exchange của người dùng chưa được thiết lập để xác thực đa yếu tố.

Các sự kiện này, cùng với các sự kiện không gian tên Office.MATS, được sử dụng cho mục đích sau đây:

1\) Xác định xem máy khách có thể nhận được mã thông báo xác thực thành công hay đã nhập trạng thái xác thực bị lỗi.

2\) Đánh giá xem các thay đổi đã xảy ra trên máy khách hoặc dịch vụ có dẫn đến quá trình hồi quy quan trọng trong trải nghiệm xác thực và độ tin cậy của người dùng hay không

3\) Khi xảy ra lỗi, các tín hiệu này phát ra các mã lỗi quan trọng từ cấu phần chịu trách nhiệm (mã máy khách Office, thư viện xác thực hoặc dịch vụ ủy quyền) có thể được sử dụng để phân loại, chẩn đoán và giảm thiểu

4\) Các tín hiệu này ảnh hưởng đến khả năng sẵn sàng phát hành và các màn hình trạng thái, tạo ra cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi chặn người dùng quan trọng

Các trường sau đây sẽ được thu thập:

  - **AllowSavedCreds** - Thông tin đăng nhập mới có được duy trì hay không

  - **AuthScheme** - Lược đồ xác thực được sử dụng

  - **CredsSaved** - Thông tin đăng nhập mới có được lưu hay không

  - **DocumentUrlHash** - Yêu cầu URL được mã hóa

  - **EndTag** - Thẻ nơi lời nhắc kết thúc

  - **NewIdentity**\_ErrorState – Danh tính mới có hợp lệ hay không

  - **NewIdentity\_HashedUniqueId** - ID nhận dạng mới được mã hóa sau khi hoàn thành lời nhắc

  - **NewIdentity\_ProviderType** - nhà cung cấp danh tính mới sau khi hoàn thành lời nhắc

  - **NewIdentity\_HashedUniqueId** - ID nhận dạng mới được mã hóa sau khi hoàn thành lời nhắc

  - **OutStatus** - Đầu ra lời nhắc có hợp lệ hay không

  - **PromptEndTime** - Thời gian khi lời nhắc kết thúc

  - **PromptFailedTag** - Thẻ cho biết lỗi lời nhắc SSPI

  - **PromptFlow** - Thẻ thu hồi lời nhắc SSPI

  - **PromptStartTime** - Thời gian khi lời nhắc bắt đầu

  - **Proxy** - Proxy có được sử dụng hay không

  - **ServerHash** - Địa chỉ máy chủ được mã hóa

  - **SessionEndTime** – Thời gian kết thúc phiên sự kiện

  - **Timeout** - Thời gian khi lời nhắc hết thời gian

  - **UiMessage** - Thông báo giao diện người dùng trong lời nhắc

  - **UserNameHash** - Tên người dùng được mã hóa

### <a name="officeidentitywin32prompt"></a>Office.Identity.Win32Prompt

Được thu thập khi Office hiển thị cho người dùng lời nhắc đăng nhập xác thực đa yếu tố. Cùng với việc tiếp nhận mã thông báo tĩnh, lời nhắc xác thực xác định xem người dùng có ở một trạng thái xác thực bị lỗi hay không, điều này dẫn đến trạng thái Máy khách ngoại tuyến. Xác thực bị lỗi có thể ngăn chặn việc mua lại giấy phép và dẫn đến việc máy khách hoàn toàn không sử dụng được.

Các sự kiện này, cùng với các sự kiện không gian tên Office.MATS, được sử dụng cho mục đích sau đây:

1\) Xác định xem máy khách có thể nhận được mã thông báo xác thực thành công hay đã nhập trạng thái xác thực bị lỗi.

2\) Đánh giá xem các thay đổi đã xảy ra trên máy khách hoặc dịch vụ có dẫn đến quá trình hồi quy quan trọng trong trải nghiệm xác thực và độ tin cậy của người dùng hay không

3\) Khi xảy ra lỗi, các tín hiệu này phát ra các mã lỗi quan trọng từ cấu phần chịu trách nhiệm (mã máy khách Office, thư viện xác thực hoặc dịch vụ ủy quyền) có thể được sử dụng để phân loại, chẩn đoán và giảm thiểu

4\) Các tín hiệu này ảnh hưởng đến khả năng sẵn sàng phát hành và các màn hình trạng thái, tạo ra cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi chặn người dùng quan trọng.

Các trường sau đây sẽ được thu thập:

  - **AdalWAMUsed** – Thẻ cho biết kết quả nếuADAL-atop-WAM được sử dụng

  - **CallTag** – Thẻ cho biết người gọi giao diện người dùng đăng nhập

  - **Ngữ cảnh** - Ngữ cảnh đăng nhập cho lời nhắc

  - **EndTagIdentityProviderRequested** - Thẻ nơi nhà cung cấp danh tính được yêu cầu

  - **HrdShownTag** - Thẻ nơi đăng hộp thoại đăng nhập HRD được hiển thị

  - **IdentityProviderResulted** - Loại nhà cung cấp danh tính mà nó đang yêu cầu

  - **IdPFlowTag** - Thẻ cho biết kết quả yêu cầu danh tính

  - **LastLoginDelta** - Delta thời gian từ lần đăng nhập thành công gần nhất

  - **NewIdentity\_ErrorState** – Danh tính mới có hợp lệ sau lời nhắc hay không

  - **NewIdentity\_ProviderType** - Loại nhà cung cấp danh tính mới sau lời nhắc

  - **NewIdentity\_UniqueID** - ID nhận dạng mới được trả về sau lời nhắc

  - **PromptCorrelation** - ID tương quan lời nhắc cho mục đích chẩn đoán

  - **PromptEndTime** - Thời gian khi lời nhắc kết thúc

  - **PromptStartTime** - Thời gian khi lời nhắc bắt đầu

  - **SessionEndTime** – Thời gian kết thúc phiên sự kiện

  - **ShowUIResult** – Mã kết quả trả về từ giao diện người dùng trong lời nhắc

  - **StartTag** – Thẻ nơi lời nhắc Win32 nhắc bắt đầu

  - **Timeout** - Thời gian khi lời nhắc hết thời gian

  - **WasIdentitySignedOut** - Người dùng đã đăng hay chưa

### <a name="officematsactionofficewin32-officematsactionofficewinrt"></a>Office.MATS.actionofficewin32, Office.MATS.actionofficewinrt

Mô tả sau đây áp dụng cho cả các sự kiện Win32 và WinRT (tên phụ thuộc vào nền tảng.)

Hệ thống phép đo từ xa xác thực Microsoft (Microsoft Auth Telemetry System - MATS) được thu thập khi Office cố gắng lấy mã thông báo xác thực, bằng cách âm thầm hoặc thông qua nhắc nhở. Khi nỗ lực tiếp nhận thất bại, thông tin lỗi sẽ được bao gồm. Các sự kiện này giúp người dùng của chúng tôi không phải nhập trạng thái xác thực lỗi bằng cách:

1\) Xác định xem máy khách có thể nhận được mã thông báo xác thực thành công hay đã nhập trạng thái xác thực bị lỗi.

2\) Đánh giá xem các thay đổi đã xảy ra trên máy khách hoặc dịch vụ hay không, cho dù chúng có dẫn đến quá trình hồi quy quan trọng trong trải nghiệm xác thực và độ tin cậy của người dùng

3\) Khi xảy ra lỗi, các tín hiệu này phát ra các mã lỗi quan trọng từ cấu phần chịu trách nhiệm (mã máy khách Office, thư viện xác thực hoặc dịch vụ ủy quyền) có thể được sử dụng để phân loại, chẩn đoán và giảm thiểu

4\) Các tín hiệu này ảnh hưởng đến khả năng sẵn sàng phát hành và các màn hình trạng thái, tạo ra cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi quan trọng.

Các trường sau đây sẽ được thu thập:

  - **Actiontype** - Thư viện xác thực nào được sử dụng

  - **Appaudience** - Bản dựng ứng dụng dành cho mục đích sử dụng nội bộ hay bên ngoài

  - **Appforcedprompt** - Ứng dụng có ghi đè lên bộ đệm ẩn và buộc lời nhắc được hiển thị hay không

  - **Appname** - Tên ứng dụng thực hiện xác thực

  - **Appver** - Phiên bản ứng dụng thực hiện xác thực

  - **Askedforcreds** - Ứng dụng yêu cầu người dùng nhập thông tin đăng nhập cho hành động này hay không

  - **Authoutcome** - Nỗ lực xác thực thành công, không thành công hay đã bị hủy

  - **Blockingprompt** - Ứng dụng có thực hiện loại bỏ lời nhắc yêu cầu tương tác người dùng hay không

  - **Correlationid** - GUID được sử dụng để tham gia với dữ liệu dịch vụ

  - **Count** - Số lượng sự kiện trong các trường hợp tổng hợp

  - **Data\_accounttype** - Tài khoản người tiêu dùng hoặc tổ chức

  - **Devicenetworkstate** - Người dùng có trực tuyến không

  - **Deviceprofiletelemetryid** - ID thiết bị ẩn danh được sử dụng để đo trải nghiệm thiết bị

  - **Duration** - Khoảng thời gian diễn ra quá trình xác thực

  - **Duration_Max** - Nếu tín hiệu này được tổng hợp, khoảng thời gian tối đa của bất kỳ sự kiện tổng hợp nào.

  - **Duration_Min** - Nếu tín hiệu này được tổng hợp, khoảng thời gian tối thiểu của bất kỳ sự kiện tổng hợp nào.

  - **Duration_Sum** - Nếu tín hiệu này được tổng hợp, tổng khoảng thời gian của tất cả các sự kiện tổng hợp.

  - **Endtime** - Thời điểm sự kiện xác thực kết thúc

  - **Error** - Mã lỗi nếu tính năng xác thực không thành công

  - **Errordescription** - Mô tả ngắn về lỗi

  - **Errorsource** - Lỗi đến từ dịch vụ, thư viện xác thực hay ứng dụng

  - **Identityservice** - Tài khoản dịch vụ Microsoft (MSA) hoặc dịch vụ Azure Active Directory (AAD) có bị thu hồi hay không

  - **Interactiveauthcontainer** - Loại lời nhắc được hiển thị

  - **Issilent** - Lời nhắc có được hiển thị hay không

  - **Microsoft**\_**ADAL**\_**adal**\_**version** - Phiên bản thư viên xác thực Azure Active Directory (ADAL)

  - **Microsoft\_ADAL\_api\_error\_code** - Mã lỗi được phát ra bởi thư viện xác thực cho nỗ lực xác thực này

  - **Microsoft\_ADAL\_api\_id** - API được thu hồi cho nỗ lực xác thực này

  - **Microsoft\_ADAL\_authority** – URL ủy quyền Azure Active Directory chịu trách nhiệm xác thực người dùng

  - **Microsoft\_ADAL\_authority\_type** – Người tiêu dùng/Thỏa thuận dịch vụ Microsoft (MSA) so với Azure Active Directory (AAD) tổ chức; hiện tại luôn là AAD

  - **Microsoft\_ADAL\_authority\_validation\_status** – Cho biết liệu việc xác thực đã hoàn thành ở bên dịch vụ hay chưa

  - **Microsoft\_ADAL\_broker\_app** - Cho biết liệu ADAL có sử dụng một trình cung cấp để xác thực hay không

  - **Microsoft\_ADAL\_broker\_app\_used** – Cho biết tên của trình cung cấp (ví dụ: Quản lý tài khoản Windows)

  - **Microsoft\_ADAL\_broker\_version** - Cho biết phiên bản của trình cung cấp nếu được sử dụng

  - **Microsoft\_ADAL\_cache\_event\_count** - Số lượng sự kiện bộ đệm ẩn mà ADAL được thực hiện trong khi truy xuất mã thông báo

  - **Microsoft\_ADAL\_cache\_event\_count\_max** - Nếu tín hiệu này được tổng hợp, các sự kiện bộ đệm ẩn tối đa của bất kỳ một sự kiện tổng hợp nào.

  - **Microsoft\_ADAL\_cache\_event\_count\_min** - Nếu tín hiệu này được tổng hợp, các sự kiện bộ đệm ẩn tối thiểu của bất kỳ một sự kiện tổng hợp nào.

  - **Microsoft\_ADAL\_cache\_event\_count\_sum** - Nếu tín hiệu này được tổng hợp, tổng số các sự kiện bộ đệm ẩn của tất cả các sự kiện tổng hợp.

  - **Microsoft\_ADAL\_cache\_read\_count** - Số lần API đọc từ bộ đệm ẩn ổ đĩa. Trình bày nếu có ít nhất một lần đọc.

  - **Microsoft\_ADAL\_cache\_read\_error\_count** -Số lần bộ đệm ẩn ổ đĩa không thể đọc. Trình bày nếu có ít nhất một lần thất bại.

  - **Microsoft\_ADAL\_cache\_read\_last\_error** - Mã lỗi ADAL. Trình bày nếu có ít nhất một lần không thể đọc.

  - **Microsoft\_ADAL\_cache\_read\_last\_system\_error** - Mã lỗi hệ thống. Trình bày nếu có ít nhất một lần không thể đọc.

  - **Microsoft\_ADAL\_cache\_write\_count** - Số lần API đọc từ bộ đệm ẩn ổ đĩa. Trình bày nếu có ít nhất một lần ghi.

  - **Microsoft\_ADAL\_cache\_write\_error\_count** - Số lần bộ đệm ẩn ổ đĩa không thể ghi. Trình bày nếu có ít nhất một lần thất bại.

  - **Microsoft\_ADAL\_cache\_write\_last\_error** - Mã lỗi ADAL. Trình bày nếu có ít nhất một lần không thể ghi.

  - **Microsoft\_ADAL\_cache\_write\_last\_system\_error** - Mã lỗi hệ thống. Trình bày nếu có ít nhất một lần không thể ghi.

  - **Microsoft\_ADAL\_client\_id** - ID ứng dụng AAD được hash

  - **Microsoft\_ADAL\_extended\_expires\_on\_setting** - Cho biết việc mã thông báo có một thời hạn mở rộng là đúng hay sai.

  - **Microsoft\_ADAL\_http\_sự kiện\_coun** t - Số lượngcuộc gọi HTTP được thực hiện bởi ADAL.

  - **Microsoft\_ADAL\_http\_event\_count\_max** - tín hiệu này được tổng hợp, các cuộc gọi HTTP tối đa được thực hiện bởi ADAL của bất kỳ sự kiện tổng hợp nào.

  - **Microsoft\_ADAL\_http\_event\_count\_min** - tín hiệu này được tổng hợp, các cuộc gọi HTTP tối thiểu được thực hiện bởi ADAL của bất kỳ sự kiện tổng hợp nào.

  - **Microsoft\_ADAL\_http\_event\_count\_sum** - Gín hiệu này được tổng hợp, tổng các cuộc gọi HTTP được thực hiện bởi ADAL của tất cả các sự kiện tổng hợp.

  - **Microsoft\_ADAL\_is\_silent\_ui** - Việc giao diện người dùng được hiển thị (lời nhắc) bằng ADAL là đúng hay sai.

  - **Microsoft\_ADAL\_is\_successful** - Việc ADAL API đã thành công là đúng hay sai.

  - **Microsoft\_ADAL\_logging\_pii\_enabled** - Cho biết nếu chế độ ghi nhật ký ADAL đầy đủ được bật là đúng hay sai. Dữ liệu này chỉ ghi nhật ký cục bộ, không được phát ra trong phép đo từ xa.

  - **Microsoft\_ADAL\_oauth\_error\_code** – Mã lỗi giao thức OAuth được trả về bởi dịch vụ.

  - **Microsoft\_ADAL\_prompt\_behavior** - Đăng nhập hoặc không có tham số HTTP nào được chuyển đến dịch vụ để chỉ định nếu giao diện người dùng có thể được hiển thị.

  - **Microsoft\_ADAL\_request\_id** - GUID giao dịch cho yêu cầu do ADAL phát ra cho dịch vụ.

  - **Microsoft\_ADAL\_response\_code** - HTTP phản hồi mã từ các dịch vụ.

  - **Microsoft\_ADAL\_response\_time** - Khoảng thời gian dịch vụ trở về ADAL.

  - **Microsoft\_ADAL\_response\_time\_max** - Nếu tín hiệu được tổng hợp, thời gian tối đa để ADAL trả về từ API của nó trong số bất kỳ sự kiện tổng hợp nào.

  - **Microsoft\_ADAL\_response\_time\_min** - Nếu tín hiệu được tổng hợp, thời gian tối thiểu để ADAL trả về từ API của nó trong số bất kỳ sự kiện tổng hợp nào.

  - **Microsoft\_ADAL\_response\_time\_sum** - Nếu tín hiệu được tổng hợp, tổng thời gian để ADAL trả về từ API của nó trong số bất kỳ sự kiện tổng hợp nào.

  - **Microsoft\_ADAL\_rt\_age** – Tuổi của mã thông báo làm mới

  - **Microsoft\_ADAL\_server\_error\_code** - Mã lỗi do máy chủ trả về

  - **Microsoft\_ADAL\_server\_sub\_error\_code** -Mã lỗi phụ được máy chủ trả về để giúp định hướng tại sao yêu cầu không thành công.

  - **Microsoft\_ADAL\_spe\_ring** - Cho biết việc người dùng đã sử dụng vòng trong của Secure Production Enterprise (chỉ dành cho nhân viên của Microsoft) là đúng hay sai.

  - **Microsoft\_ADAL\_start\_time** – Thời gian cuộc gọi ADAL API đã được thực hiện

  - **Microsoft\_ADAL\_stop\_time** – Thời gian cuộc gọi ADAL API được trả về

  - **Microsoft\_ADAL\_telemetry\_pii\_enabled** - Cho biết nếu chế độ phép đo từ xa ADAL đầy đủ được bật là đúng hay sai. Tên này là một cách gọi sai, vì không có PII/EUII được phát ra.

  - **Microsoft\_ADAL\_tenant\_id** - GUID xác định đối tượng thuê mà người dùng được xác thực thuộc về.

  - **Microsoft\_ADAL\_token\_acquisition\_from\_context** - Mô tả hành vi ADAL dựa trên mã thông báo trong ngữ cảnh xác thực.

  - **Microsoft\_ADAL\_token\_type** – Mã thông báo (RT) hoặc mã thông báo làm mới đa tài nguyên (MRRT).

  - **Microsoft\_ADAL\_ui\_event\_count** - Số lượng các lời nhắc được hiển thị cho người dùng. Có thể là tĩnh.

  - **Microsoft\_ADAL\_user\_cancel** - Cho biết cửa sổ giao diện người dùng đã được hủy bỏ là đúng hay sai.

  - **Microsoft_ADAL_was_request_throttled** – Cho biết sự kiện này đã được ADAL tiết lưu do quá nhiều yêu cầu là đúng hay sai.
 
  - **Microsoft\_ADAL\_x\_ms\_request\_id** – ID yêu cầu bổ sung được cung cấp trong tiêu đề HTTP cho dịch vụ của ADAL.

  - **Platform** - Win32/WinRT/Android/iOS/Mac

  - **Promptreasoncorrelationid** – Để nhắc, đây là id tương quan của một sự kiện khác để giải thích tại sao người dùng có thể nhìn thấy lời nhắc xác thực.

  - **Resource** – Tài nguyên mà người dùng đang yêu cầu mã thông báo, chẳng hạn như Exchange hoặc SharePoint.

  - **Scenarioid** – GUID. Nhiều sự kiện có thể thuộc về một kịch bản duy nhất, ví dụ: kịch bản có thể đang thêm một tài khoản mới nhưng có nhiều lời nhắc xảy ra như một phần của kịch bản đó. ID này cho phépsự tương quan xảy ra.

  - **Scenarioname** – Tên của kịch bản sở hữu sự kiện xác thực này.

  - **SessionId** - GUID xác định phiên khởi động

  - **Skdver** - Phiên bản SDK máy khách MATS được sử dụng để tạo dữ liệu này

  - **StartTime** - Thời gian tại đó bắt đầu\*thao tác MATS API đã được gọi

  - **Tenantid** - GUID xác định đối tượng thuê mà người dùng được xác thực thuộc về (trong trường hợp không phải là ADAL).

  - **Uploadid** - GUID duy nhất cho sự kiện này, được sử dụng để khấu trừ

  - **Wamapi** - Xác định WAM API được gọi

  - **Wamtelemetrybatch** - Hiện chưa sử dụng. Trong tương lai, cho phép cấu phần WAM gửi thông tin bổ sung về sự kiện xác thực.


### <a name="officematsoneauthactionmicrosoftofficewin32"></a>Office.MATS.OneAuth.ActionMicrosoftOfficeWin32

Hệ thống phép đo từ xa xác thực Microsoft (Microsoft Auth Telemetry System - MATS) được thu thập khi Office cố gắng lấy mã thông báo xác thực, bằng cách âm thầm hoặc thông qua nhắc nhở. Khi nỗ lực tiếp nhận thất bại, thông tin lỗi sẽ được bao gồm. Các sự kiện này giúp người dùng của chúng tôi không phải nhập trạng thái xác thực lỗi bằng cách:

1) Xác định xem máy khách có thể nhận được mã thông báo xác thực từ dịch vụ thành công hay đã nhập trạng thái xác thực bị lỗi.

2) Đánh giá xem các thay đổi đã xảy ra trên máy khách hoặc dịch vụ hay không, cho dù chúng có dẫn đến quá trình hồi quy quan trọng trong trải nghiệm xác thực và độ tin cậy của người dùng

3) Khi xảy ra lỗi, các tín hiệu này phát ra các mã lỗi quan trọng từ cấu phần chịu trách nhiệm (mã máy khách Office, thư viện xác thực hoặc dịch vụ ủy quyền) có thể được sử dụng để phân loại, chẩn đoán và giảm thiểu

4) Các tín hiệu này ảnh hưởng đến khả năng sẵn sàng phát hành và các màn hình trạng thái, tạo ra cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi quan trọng.

Các trường sau đây sẽ được thu thập:

- **Accounttype** - Loại tài khoản dùng cho sự kiện xác thực này, ví dụ: người tiêu dùng hoặc tổ chức.

- **Actionname** - Tên thân thiện cho sự kiện này nếu được cung cấp.

- **Actiontype** - Chỉ định loại thư viện xác thực được sử dụng.

- **Appaudience** - Bản dựng ứng dụng dành cho mục đích sử dụng nội bộ hay bên ngoài

- **Appforcedprompt** - Ứng dụng có ghi đè lên bộ đệm ẩn và buộc lời nhắc được hiển thị hay không

- **Appname** - Tên ứng dụng thực hiện xác thực

- **Appver** - Phiên bản ứng dụng thực hiện xác thực

- **Askedforcreds** - Ứng dụng yêu cầu người dùng nhập thông tin đăng nhập cho hành động này hay không

- **Authoutcome** - Nỗ lực xác thực thành công, không thành công hay đã bị hủy

- **Blockingprompt** - Ứng dụng có thực hiện loại bỏ lời nhắc yêu cầu tương tác người dùng hay không

- **Correlationid** - Mã định danh dùng để kết hợp thông tin liên quan đến sự kiện riêng lẻ này với dữ liệu dịch vụ

- **Count** - Tổng số hành động tổng hợp được báo cáo trong một sự kiện dữ liệu này.

- **Devicenetworkstate** - Thiết bị có được kết nối với Internet không.

- **Deviceprofiletelemetryid** - ID thiết bị ẩn danh dùng để đo lường trải nghiệm và độ tin cậy của quá trình xác thực trên toàn thiết bị.

- **Duration** - Khoảng thời gian diễn ra quá trình xác thực

- **duration_max** - Khoảng thời gian tối đa của một sự kiện tổng hợp bất kỳ

- **duration_min** - Khoảng thời gian tối thiểu của một sự kiện tổng hợp bất kỳ

- **duration_sum** - Tổng thời gian của tất cả sự kiện tổng hợp

- **endtime** - Thời điểm sự kiện xác thực kết thúc

- **error** - Mã lỗi nếu xác thực không thành công

- **errordescription** - Mô tả ngắn về lỗi

- **errorsource** - Lỗi đến từ dịch vụ, thư viện xác thực hay ứng dụng

- **eventtype** - Sự kiện này báo cáo một điểm dữ liệu xác thực hay một sự kiện lỗi chất lượng dữ liệu. Dùng để đo lường chất lượng dữ liệu.

- **from_cache** - Boolean cho biết bản ghi từ bộ đệm ẩn WAM chính hoặc từ phần bổ trợ

- **hasadaltelemetry** - Cho biết Thư viện xác thực Azure Active Directory (ADAL) có cung cấp dữ liệu từ xa cho sự kiện này hay không.

- **Identityservice** - Tài khoản dịch vụ Microsoft (MSA) hoặc dịch vụ Azure Active Directory (AAD) có bị thu hồi hay không

- **Interactiveauthcontainer** - Loại lời nhắc được hiển thị

- **Issilent** - Đây là lời nhắc sẽ hiển thị hay đây là sự kiện xác thực tự hành (chạy nền). 

- **Microsoft_ADAL_adal_version** - Phiên bản thư viện xác thực Azure Active Directory (ADAL)

- **Microsoft_ADAL_api_error_code** - Mã lỗi được phát bởi thư viện xác thực cho nỗ lực xác thực này

- **Microsoft_ADAL_api_id** - API được thu hồi cho nỗ lực xác thực này

- **Microsoft_ADAL_application_name** - Tên ứng dụng/quy trình bằng ADAL.

- **Microsoft_ADAL_application_version** - Phiên bản ứng dụng bằng ADAL.

- **Microsoft_ADAL_authority** - URL xác thực Azure Active Directory chịu trách nhiệm xác thực người dùng

- **Microsoft_ADAL_authority_type** - Người tiêu dùng/Thỏa thuận dịch vụ Microsoft (MSA) so với Azure Active Directory (AAD) tổ chức; hiện luôn là AAD

- **Microsoft_ADAL_authority_validation_status** - Cho biết liệu việc xác thực đã hoàn thành ở bên dịch vụ hay chưa

- **Microsoft_ADAL_broker_app** - Cho biết liệu ADAL có sử dụng một trình cung cấp để xác thực hay không

- **Microsoft_ADAL_broker_app_used** - Cho biết tên của trình cung cấp (ví dụ: Quản lý tài khoản Windows)

- **Microsoft_ADAL_broker_version** - Cho biết phiên bản của trình cung cấp nếu được sử dụng

- **Microsoft_ADAL_cache_event_count** - Số lượng sự kiện bộ đệm ẩn mà ADAL đã thực hiện trong khi truy xuất mã thông báo

- **Microsoft_ADAL_cache_event_count_max** - Nếu tổng hợp tín hiệu này thì các sự kiện bộ đệm ẩn của bất kỳ một sự kiện tổng hợp nào là tối đa.

- **Microsoft_ADAL_cache_event_count_min** - Nếu tổng hợp tín hiệu này thì các sự kiện bộ đệm ẩn của bất kỳ một sự kiện tổng hợp nào là tối thiểu.

- **Microsoft_ADAL_cache_event_count_sum** - Nếu tổng hợp tín hiệu này thì các sự kiện bộ đệm ẩn của bất kỳ một sự kiện tổng hợp nào là tổng cộng.

- **Microsoft_ADAL_cache_read_count** - Số lần API đọc từ bộ đệm đĩa. Hiện diện nếu có ít nhất một lần đọc

- **Microsoft_ADAL_cache_read_count** - Số lần đọc bộ đệm đĩa không thành công. Hiện diện nếu có ít nhất một lần không thành công

- **Microsoft_ADAL_cache_read_last_error** - Mã lỗi ADAL. Hiện diện nếu có ít nhất một lần đọc không thành công

- **Microsoft_ADAL_cache_read_last_system_error** - Mã lỗi hệ thống.  Hiện diện nếu có ít nhất một lần đọc không thành công

- **Microsoft_ADAL_cache_write_count** - Số lần API ghi cho bộ đệm đĩa. Hiện diện nếu có ít nhất một lần ghi

- **Microsoft_ADAL_cache_write_error_count** - Số lần ghi bộ đệm đĩa không thành công. Hiện diện nếu có ít nhất một lần không thành công

- **Microsoft_ADAL_cache_write_last_error** - Mã lỗi ADAL. Hiện diện nếu có ít nhất một lần ghi không thành công

- **Microsoft_ADAL_cache_write_last_system_error** - Mã lỗi hệ thống. Hiện diện nếu có ít nhất một lần ghi không thành công

- **Microsoft_ADAL_client_id** - ID ứng dụng Azure Active Directory dạng băm

- **Microsoft_ADAL_device_id** - ID thiết bị cục bộ tạo bởi ADAL.

- **Microsoft_ADAL_error_domain** - Tên miền/cấu phần đã tạo mã lỗi.

- **Microsoft_ADAL_error_protocol_code** - Mã lỗi giao thức OAuth do dịch vụ trả về và được ADAL ghi lại.

- **Microsoft_ADAL_extended_expires_on_setting** - Cho biết việc mã thông báo có một thời hạn mở rộng là đúng hay sai.

- **Microsoft_ADAL_http_event_count** - Số yêu cầu HTTP tạo bởi ADAL.

- **Microsoft_ADAL_idp** - Nhà cung cấp danh tính (IDP) được ADAL sử dụng.

- **Microsoft_ADAL_network_event_count** - Số lần gọi mạng do ADAL thực hiện

- **Microsoft_ADAL_http_event_count_max** - Nếu tổng hợp tín hiệu này thì số lần gọi http bởi ADAL là tối đa

- **Microsoft_ADAL_http_event_count_min** - Nếu tổng hợp tín hiệu này thì số lần gọi http bởi ADAL là tối thiểu

- **Microsoft_ADAL_http_event_count_sum** - Nếu tổng hợp tín hiệu này thì số lần gọi http bởi ADAL là tổng cộng

- **Microsoft_ADAL_network_event_count_max** - Nếu tổng hợp tín hiệu này thì số lần gọi mạng bởi ADAL của bất kỳ sự kiện nào đã được tổng hợp là tối đa

- **Microsoft_ADAL_network_event_count_min** - Nếu tổng hợp tín hiệu này thì số lần gọi mạng bởi ADAL của bất kỳ sự kiện nào đã được tổng hợp là tối thiểu

- **Microsoft_ADAL_network_event_count_sum** - Nếu tổng hợp tín hiệu này thì số lần gọi mạng bởi ADAL của bất kỳ sự kiện nào đã được tổng hợp là tổng cộng.

- **Microsoft_ADAL_is_silent_ui** - Việc giao diện người dùng được hiển thị (lời nhắc) bằng ADAL là đúng hay sai

- **Microsoft_ADAL_is_successfull** - Việc API ADAL đã thành công là đúng hay sai (macOS)

- **Microsoft_ADAL_is_successfull** - Việc API ADAL đã thành công là đúng hay sai

- **Microsoft_ADAL_logging_pii_enabled** - Cho biết việc bật chế độ ghi nhật ký ADAL đầy đủ là đúng hay sai. Dữ liệu này chỉ được ghi vào nhật ký cục bộ, không được phát trong dữ liệu từ xa.

- **Microsoft_ADAL_ntlm** - Cho biết việc xác thực cơ bản sử dụng ADAL (NTLM) là đúng hay sai.

- **Microsoft_ADAL_oauth_error_code** - Mã lỗi giao thức OAuth trả về bởi dịch vụ

- **Microsoft_ADAL_prompt_behavior** - Đăng nhập hoặc không có tham số mạng nào được chuyển đến dịch vụ để chỉ định nếu giao diện người dùng có thể được hiển thị

- **Microsoft_ADAL_request_id** - GUID giao dịch cho yêu cầu do ADAL phát cho dịch vụ

- **Microsoft_ADAL_response_code** - Mã phản hồi mạng từ dịch vụ

- **Microsoft_ADAL_response_time** - Khoảng thời gian dịch vụ trở về ADAL

- **Microsoft_ADAL_response_time_max** - Nếu tổng hợp tín hiệu thì thời gian để ADAL trả về từ API trong bất kỳ sự kiện nào đã được tổng hợp là tối đa

- **Microsoft_ADAL_response_time_min** - Nếu tổng hợp tín hiệu thì thời gian để ADAL trả về từ API trong bất kỳ sự kiện nào đã được tổng hợp là tối thiểu

- **Microsoft_ADAL_response_time_sum** - Nếu tổng hợp tín hiệu thì thời gian để ADAL trả về từ API trong bất kỳ sự kiện nào đã được tổng hợp là tổng cộng

- **Microsoft_ADAL_rt_age** - Tuổi của mã thông báo làm mới

- **Microsoft_ADAL_server_error_code** - Mã lỗi do máy chủ trả về

- **Microsoft_ADAL_server_sub_error_code** - Mã lỗi phụ do máy chủ trả về để giúp định hướng tại sao yêu cầu không thành công

- **Microsoft_ADAL_spe_info** - Cho biết việc người dùng đã sử dụng vòng cập nhật nội bộ của Secure Production Enterprise (chỉ dành cho nhân viên của Microsoft) là đúng hay sai

- **Microsoft_ADAL_spe_ring** - Cho biết việc người dùng đã sử dụng vòng cập nhật nội bộ của Secure Production Enterprise (chỉ dành cho nhân viên của Microsoft) là đúng hay sai

- **Microsoft_ADAL_start_time** - Thời gian thực hiện cuộc gọi API ADAL

- **Microsoft_ADAL_status** - Trạng thái thành công/thất bại về việc gọi ADAL tổng quan

- **Microsoft_ADAL_stop_time** - Thời gian trả về cuộc gọi API ADAL

- **Microsoft_ADAL_telemetry_pii_enabled** - Cho biết việc bật chế độ dữ liệu từ xa ADAL đầy đủ là đúng hay sai. Tên này là một cách gọi sai, vì không có phát PII/EUII

- **Microsoft_ADAL_tenant_id** - GUID xác định đối tượng thuê mà người dùng đã được xác thực thuộc về

- **Microsoft_ADAL_token_acquisition_from_context** - Mô tả hành vi ADAL dựa trên mã thông báo trong ngữ cảnh xác thực

- **Microsoft_ADAL_token_frt_status** - Trạng thái của mã thông báo làm mới: đã thử, không cần thiết, không tìm thấy hay bị xóa.

- **Microsoft_ADAL_token_mrrt_status** - Trạng thái của mã thông báo làm mới đa tài nguyên: đã thử, không cần thiết, không tìm thấy hay bị xóa.

- **Microsoft_ADAL_token_rt_status** - Trạng thái của mã thông báo làm mới: đã thử, không cần thiết, không tìm thấy hay bị xóa.

- **Microsoft_ADAL_token_type** - Mã thông báo làm mới (RT) hoặc mã thông báo làm mới đa tài nguyên (MRRT)

- **Microsoft_ADAL_ui_event_count** - Số lời nhắc hiển thị cho người dùng. Có thể tự hành

- **Microsoft_ADAL_user_cancel** - Cho biết cửa sổ giao diện người dùng bị hủy bỏ là đúng hay sai

- **Microsoft_ADAL_x_ms_request_id** - ID yêu cầu bổ sung được cung cấp trong tiêu đề HTTP cho dịch vụ của ADAL

- **Microsoft_ADAL_x_client_cpu** - Thông tin liên quan đến Kiến trúc CPU của thiết bị

- **Microsoft_ADAL_x_client_os** - Phiên bản HĐH của thiết bị.

- **Microsoft_ADAL_x_client_sku** - Tên SKU HĐH của thiết bị.

- **Microsoft_ADAL_x_client_ver** - Phiên bản thư viện ADAL.

- **MSAL_all_error_tags** - Tất cả các thẻ lỗi mà Thư viện xác thực Microsoft (MSAL) gặp phải trong dòng xác thực.

- **MSAL_api_error_code** - Nếu MSAL gặp lỗi phát sinh từ HĐH, mã lỗi nền tảng được lưu trữ tại đây.

- **MSAL_api_error_context** - Chuỗi chứa các chi tiết bổ sung mà con người có thể đọc được về lỗi cuối cùng mà MSAL gặp phải. 

- **MSAL_api_error_tag** - Chuỗi duy nhất cho vị trí trong mã xảy ra lỗi này.

- **MSAL_api_name** - Tên của API cấp cao nhất MSAL được gọi để bắt đầu dòng xác thực này.

- **MSAL_api_status_code** - Mã trạng thái MSAL được trả về cho kết quả dòng xác thực này.

- **MSAL_auth_flow** - Các bước MSAL đã thử trong dòng xác thực này (AT, PRT, LRT, FRT, ART, IRT). Được phân tách bằng dấu "|" để phân tích dễ dàng.

- **MSAL_auth_flow_last_error** - Mã lỗi chúng tôi nhận được từ máy chủ từ mục thứ 2 đến mục cuối cùng trong AuthFlow. (Ví dụ: nếu AuthFlow = "PRT|LRT", lỗi của PRT sẽ là ở trong AuthFlowLastError).

- **MSAL_authority_type** - Có phải là yêu cầu cho người dùng trong: AAD, Federated hoặc MSA.

- **MSAL_broker_app_used** - Có phải là một ứng dụng cung cấp dùng trong dòng xác thực này.

- **MSAL_client_id** - ID máy khách của ứng dụng gọi

- **MSAL_correlation_id** - GUID duy nhất cho sự kiện này dùng để tham gia các hành động trên máy khách, máy chủ và nhật ký ứng dụng.

- **MSAL_delete_token** - Danh sách các mã thông báo đã bị xóa khỏi bộ đệm ẩn trong dòng xác thực này.

- **MSAL_http_call_count** - Số lượng cuộc gọi HTTP mà MSAL đã thực hiện trong dòng xác thực.

- **MSAL_is_successful** - Dòng xác thực có thành công không.

- **MSAL_last_http_response_code** - Nếu MSAL thực hiện một hoặc nhiều lệnh gọi HTTP thì đây là mã phản hồi HTTP cuối cùng mà chúng tôi nhận được.

- **MSAL_msal_version** - Chuỗi phiên bản của MSAL có định dạng X.X.X+ (“OneAuth”, “cục bộ” hoặc commit hash).

- **MSAL_read_token** - Các mã thông báo đã được đọc từ bộ đệm ẩn (AT, ART, FRT, LRT, IRT, PRT, EAT [EAT = AT hết hạn đã được đọc, nhưng bị loại bỏ]).

- **MSAL_read_token_last_error** - Nếu MSAL gặp lỗi khi đọc từ bộ đệm ẩn, chúng tôi sẽ lưu trữ thông tin tại đây. (Ví dụ: Lỗi đọc đĩa phát sinh từ HĐH, Lỗi chuỗi khóa trên macOS).

- **MSAL_request_duration** - Thời gian xử lý yêu cầu kể từ khi gọi API cấp cao nhất của MSAL cho đến khi chúng tôi trả về kết quả.

- **MSAL_request_id** - Yêu cầu ID cho cuộc gọi cuối cùng mà chúng tôi đã thực hiện tới dịch vụ mã thông báo bảo mật của Microsoft.

- **MSAL_server_error_code** - Mã lỗi số dịch vụ mã thông báo an toàn cụ thể của Microsoft nếu chúng tôi nhận được.

- **MSAL_server_spe_ring** - Thông tin vòng cập nhật Secure Production Enterprise của dịch vụ mã thông báo an toàn của Microsoft nếu chúng tôi nhận được.

- **MSAL_server_suberror_code** - Chuỗi mã lỗi phụ dịch vụ mã thông báo an toàn cụ thể của Microsoft nếu chúng tôi nhận được.

- **MSAL_start_time** - Thời gian yêu cầu MSAL bắt đầu ở API công khai cấp cao nhất.

- **MSAL_stop_time** - Thời gian MSAL xử lý xong yêu cầu và trả về kết quả cho người gọi.

- **MSAL_tenant_id** - Microsoft GUID xác định đối tượng thuê mà người dùng tồn tại.

- **MSAL_ui_event_count** - Số lời nhắc giao diện người dùng MSAL đã hiển thị trên màn hình.

- **MSAL_wam_telemetry** - Chứa một lô dữ liệu từ xa WAM trong một chuỗi JSON sẽ được phân tích cú pháp và chuyển đổi thành các trường trong tài liệu này có nguồn từ WAM.

- **MSAL_was_request_throttled** - Đúng nếu MSAL chặn yêu cầu này và ngăn không cho yêu cầu truy cập mạng. Nếu điều này đúng, rất có thể có một vòng lặp trong ứng dụng gọi điện.

- **MSAL_write_token** - Các mã thông báo đã được ghi vào bộ đệm ẩn (AT, ART, FRT, LRT, IRT, PRT, EAT [EAT = AT hết hạn đã được đọc, nhưng bị loại bỏ]).

- **MSAL_write_token_last_error** - Nếu MSAL gặp lỗi ghi vào bộ đệm ẩn, chúng tôi sẽ lưu trữ thông tin tại đây. (Ví dụ: Lỗi đọc đĩa phát sinh từ HĐH, Lỗi chuỗi khóa trên macOS).

- **oneauth_api** - API OneAuth đã được gọi cho nỗ lực xác thực này.

- **oneauth_transactionuploadid** - GUID chỉ định một lệnh gọi riêng lẻ tới API OneAuth.

- **oneauth_version** - Phiên bản của SDK OneAuth.

- **Platform** - Nền tảng HĐH (0: Windows Desktop, 1: Android, 2: iOS, 3: macOS, 4: UWP)

- **Promptreasoncorrelationid** - Mã định danh tương quan có thể dùng để tra cứu sự kiện xác thực trước đó để giải thích lý do tại sao người dùng đã được nhắc để xác thực.

- **Resource** - Tài nguyên yêu cầu mã thông báo.

- **Scenarioid** - Nhiều sự kiện có thể thuộc về một kịch bản duy nhất, ví dụ: kịch bản có thể đang thêm một tài khoản mới nhưng có nhiều lời nhắc xảy ra như một phần của kịch bản đó. Mã định danh này cho phép mối tương quan của các sự kiện liên quan đó.

- **Scenarioname** - Tên của tình huống ứng dụng yêu cầu xác thực, ví dụ: lần khởi động đầu tiên, kiểm tra cấp phép, v.v.

- **Scope** - Phạm vi yêu cầu mã thông báo.

- **Sdkver** - Phiên bản thư viện Hệ thống đo từ xa Microsoft Auth dùng để tạo dữ liệu này

- **Sessionid** - Mã định danh cho phiên khởi động

- **Starttime** - Thời gian bắt đầu sự kiện xác thực.

- **Tenantid** - GUID xác định đối tượng thuê mà người dùng đã xác thực thuộc về (trong các trường hợp không phải ADAL)

- **Uploadid** - GUID duy nhất cho sự kiện này dùng để loại trừ

- **wamapi** - Xác định gọi API quản lý tài khoản web (WAM) của Windows nào

- **wamtelemetrybatch** - Hiện không sử dụng. Trong tương lai, cho phép cấu phần WAM gửi thông tin bổ sung về sự kiện xác thực

- **WAM_account_join_on_end** - Trạng thái tham gia tài khoản khi kết thúc hoạt động WAM.  Giá trị có thể xuất hiện: “primary” (chính), “secondary” (phụ), “not_joined” (không tham gia)

- **WAM_account_join_on_start** - Trạng thái tham gia tài khoản khi bắt đầu hoạt động WAM.  Giá trị có thể xuất hiện: “primary” (chính), “secondary” (phụ), “not_joined” (không tham gia)

- **WAM_api_error_code** - Nếu phản hồi lỗi đến từ phần bổ trợ AAD WAM, trường này sẽ tồn tại và sẽ chứa mã lỗi đó

- **WAM_authority** - Chuỗi chứa url ủy quyền — đây phải là điểm cuối login.windows.net được sử dụng

- **WAM_broker_version** - Hiện diện nếu WAM đã được sử dụng, đây là chuỗi phiên bản trình cung cấp

- **WAM_cache_event_count** - Số lượng sự kiện bộ đệm ẩn WAM trong hoạt động

- **WAM_client_id** - Mã định danh để kết hợp với dữ liệu dịch vụ, mã này xác định ứng dụng máy khách.

- **WAM_correlation_id** - Mã định danh để tham gia các sự kiện với dữ liệu dịch vụ

- **WAM_device_join** - Trạng thái tham gia thiết bị; giá trị có thể là “aadj”, “haadj”

- **WAM_network_event_count** - Hiện diện nếu có ít nhất một cuộc gọi mạng đã xảy ra; số lượng cuộc gọi mạng tới dịch vụ cho hoạt động WAM đó

- **WAM_network_status** - Hiện diện nếu ít nhất một cuộc gọi mạng đã xảy ra, có chứa mã lỗi HTTP nếu yêu cầu mạng không thành công.

- **WAM_idp** - Cho biết xem phần bổ trợ xác thực người dùng hoặc tổ chức WAM đã được sử dụng hay chưa.

- **WAM_is_cached** - Cho biết phản hồi do WAM cung cấp có được truy xuất từ bộ đệm ẩn hay không.

- **WAM_oauth_error_code** - Chứa mã lỗi do dịch vụ trả về như một phần của giao thức oauth.

- **WAM_prompt_behavior** - Cho biết lời nhắc này có bị ứng dụng ép buộc hay không, hoặc nếu yêu cầu này có thể bỏ qua lời nhắc nếu có thể xác thực tự hành.

- **WAM_provider_id** - Chỉ định điểm cuối của Microsoft để cấp quyền sử dụng cho tình huống xác thực.

- **WAM_redirect_uri** - URI chuyển hướng đã đăng ký cho ứng dụng trong Azure Active Directory.

- **WAM_resource**  - Tài nguyên yêu cầu mã thông báo.

- **WAM_server_error_code** - Mã lỗi do dịch vụ trả về cho WAM.

- **WAM_server_sub_code** - Mã lỗi bổ sung dùng để phân tích thêm các nguyên nhân gây ra lỗi do dịch vụ trả về.

- **WAM_silent_code** - Mã lỗi gặp phải do nỗ lực nội bộ tự hành mà WAM thực hiện trước khi nhắc người dùng.

- **WAM_silent_mats** - Không sử dụng.

- **WAM_silent_message** - Thông báo lỗi liên quan đến nỗ lực nội bộ tự hành mà WAM thực hiện trước khi nhắc người dùng.

- **WAM_silent_status** - Trạng thái thành công/thất bại của nỗ lực nội bộ tự hành mà WAM thực hiện trước khi nhắc người dùng.

- **WAM_tenant_id** - Mã định danh cho đối tượng thuê mà người dùng AAD đã xác thực thuộc về nếu được dịch vụ trả lại

- **WAM_ui_visible** - Hiện diện nếu có ít nhất một cửa sổ giao diện người dùng được hiển thị cho người dùng là “true” (đúng) hoặc “false” (sai)

- **WAM_x_ms_clitelem** - Hiện diện nếu dịch vụ trả về tiêu đề “x-ms-clitelem"


### <a name="officematsoneauthtransactionmicrosoftofficewin32"></a>Office.MATS.OneAuth.TransactionMicrosoftOfficeWin32

Hệ thống phép đo từ xa xác thực Microsoft (Microsoft Auth Telemetry System - MATS) được thu thập khi Office cố gắng lấy mã thông báo xác thực, bằng cách âm thầm hoặc thông qua nhắc nhở. Sự kiện này là phần tử cha của một hoặc nhiều sự kiện ActionMicrosoftOffice, cho phép nhóm các sự kiện liên quan lại với nhau. Các sự kiện này giúp người dùng của chúng tôi không phải nhập trạng thái xác thực lỗi bằng cách:

1) Xác định xem máy khách có thể nhận được mã thông báo xác thực từ dịch vụ thành công hay đã nhập trạng thái xác thực bị lỗi.

2) Đánh giá xem các thay đổi đã xảy ra trên máy khách hoặc dịch vụ hay không, cho dù chúng có dẫn đến quá trình hồi quy quan trọng trong trải nghiệm xác thực và độ tin cậy của người dùng

3) Khi xảy ra lỗi, các tín hiệu này phát ra các mã lỗi quan trọng từ cấu phần chịu trách nhiệm (mã máy khách Office, thư viện xác thực hoặc dịch vụ ủy quyền) có thể được sử dụng để phân loại, chẩn đoán và giảm thiểu

4) Các tín hiệu này ảnh hưởng đến khả năng sẵn sàng phát hành và các màn hình trạng thái, tạo ra cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi quan trọng.

Các trường sau đây sẽ được thu thập:

- **Actiontype** - "oneauthtransaction" là giá trị duy nhất.

- **Appaudience** - Đối tượng ứng dụng (Tự động hóa, Tiền sản xuất hoặc Sản xuất)

- **Appname** - Tên ứng dụng

- **Appver** - Phiên bản ứng dụng

- **Authoutcome** - Nỗ lực xác thực thành công, không thành công hay đã bị hủy

- **Correlationid** - Mã định danh dùng để kết hợp thông tin liên quan đến sự kiện riêng lẻ này với dữ liệu dịch vụ

- **Count** - Số lần lỗi xảy ra

- **Devicenetworkstate** - Trạng thái mạng thiết bị

- **Deviceprofiletelemetryid** - ID đo từ xa của cấu hình thiết bị (chuỗi được MATS sử dụng để xác định một thiết bị cụ thể)

- **duration_max** - Thời lượng tối thiểu của các giao dịch được tổng hợp trên tín hiệu này tính bằng mili giây.

- **duration_min** - Thời lượng tối đa của các giao dịch được tổng hợp trên tín hiệu này tính bằng mili giây.

- **duration_sum** - Tổng thời lượng của các giao dịch được tổng hợp trên tín hiệu này tính bằng mili giây.

- **Endtime** - Thời gian mà giao dịch OneAuth kết thúc.

- **Error** - Lỗi trạng thái OneAuth.

- **Eventtype** - Loại sự kiện

- **Issilent** - Sai nếu hiển thị giao diện người dùng; đúng nếu đó là sự kiện nền.

- **oneauth_api** - Cho biết API công khai của OneAuth đã được gọi.

- **oneauth_Domain** - Nếu lệnh gọi API dẫn đến lỗi, đây là miền hệ thống của lỗi đó.

- **oneauth_ErrorCode** - Mã lỗi biểu thị trạng thái lỗi nội bộ cho OneAuth. Thay thế trường oneauth_errortag cũ.

- **oneauth_errortag** - Số định danh cho một dòng mã chịu trách nhiệm tạo ra lỗi.

- **oneauth_ExecutionFlow** - Một chuỗi thẻ xác định đường dẫn mã mà lệnh gọi API này đã sử dụng.

- **oneauth_internalerror** - Mã lỗi biểu thị trạng thái lỗi nội bộ cho OneAuth.

- **oneauth_ServerErrorCode** - Lỗi máy chủ đã trả về OneAuth khi kết thúc lệnh gọi API này nếu gặp phải.

- **oneauth_SystemErrorCode** - Lỗi hệ thống đã trả về OneAuth khi kết thúc lệnh gọi API này nếu gặp phải.

- **oneauth_Tag** - Thẻ OneAuth chỉ định vị trí cuối cùng trong mã đạt được khi kết thúc lệnh gọi API này.

- **oneauth_transactionuploadid** - Chỉ định GUID nội bộ được tạo ngẫu nhiên ánh xạ tới lệnh gọi cụ thể của API OneAuth.

- **oneauth_version** - Phiên bản của SDK OneAuth.

- **Platform** - Nền tảng HĐH (0: Win32, 1: Android, 2: iOS, 3:macOS, 4: WinRT

- **Scenarioname** - Tên của kịch bản cần thiết để xác thực được chỉ định bởi ứng dụng gọi.

- **Schemaver** - Phiên bản sơ đồ

- **Sdkver** - Phiên bản SDK MATS

- **Sessionid** - ID phiên

- **severityError** - Mức độ nghiêm trọng

- **starttime** - Thời gian bắt đầu giao dịch OneAuth.

- **Timestamp** - Dấu thời gian

- **Type** - Loại lỗi

- **Uploaded** - Mã định danh duy nhất cho sự kiện cụ thể này cho mục đích loại trừ.


### <a name="onenotesigninssoexternalappsaccountfound"></a>OneNote.SignIn.SSOExternalAppsAccountFound
 
Sự kiện này đã được ghi nhật ký khi một tài khoản có mã thông báo làm mới hợp lệ được tìm thấy trong danh sách tài khoản được cung cấp bởi TokenSharingManager.  Kịch bản này sẽ được dành riêng để Đăng nhập một lần (SSO).
 
Các trường sau đây sẽ được thu thập:
 
- **AccountType** - Nhập loại tài khoản

- **ProviderPackageID**- Ghi nhật ký ID gói của ứng dụng cung cấp tài khoản này

### <a name="onenotesigninssoexternalappsinvalidaccount"></a>OneNote.SignIn.SSOExternalAppsInvalidAccount

Sự kiện này đã được ghi nhật ký khi xảy ra lỗi trong quá trình tìm cách làm mới một mã thông báo cho tài khoản trong danh sách các tài khoản được cung cấp bởi TokenSharingManager. Kịch bản này dành riêng cho trường hợp Đăng nhập một lần (SSO).
 
Các trường sau đây sẽ được thu thập:
 
- **RawError** - Nhật ký lỗi gốc thu được trong quá trình cố gắng nhận mã thông báo làm mới với tài khoản đã cho

### <a name="onenotestickynotesfetchtokencompleted"></a>OneNote.StickyNotes.FetchTokenCompleted
 
Sự kiện này đã được ghi nhật ký bài đăng xác thực, sau khi hoàn tất tải lại mã thông báo làm mới.
 
Các trường sau đây sẽ được thu thập:
 
- **ErrorMessage** - Nếu việc lấy lại mã thông báo không thành công thì điều này sẽ ghi nhật ký thông báo lỗi 

- **Result** - Nhật ký kết quả của việc lấy mã thông báo

- **StickyNoteAccountType** - Loại Nhật ký của tài khoản mà ứng dụng đang tìm cách lấy mã thông báo làm mới


## <a name="click-to-run-events"></a>Sự kiện Click-to-Run

### <a name="officeclicktorunbootstrapper"></a>Office.ClickToRun.Bootstrapper 

Dữ liệu thiết lập Office và kiểm kê thu thập được khi người dùng đang chạy Office setup.exe để sửa đổi các sản phẩm Office mà họ đã cài đặt. Được sử dụng để đo lường mức độ thành công/thất bại của cài đặt Office do người dùng khởi tạo đầy đủ bao gồm cả kiểm tra điều kiện tiên quyết.

Các trường sau đây sẽ được thu thập:

  - **Data\_BootStrapperStateFailure\_ErrorCode** – Mã lỗi chúng tôi không thành công

  - **Data\_BootStrapperStateFailure\_ErrorSource** – Hàm mà chúng tôi không thành công

  - **Data\_BootStrapperStateFailure\_FailingState** – Phần mà chúng tôi không thành công trong boostrapperbootstrapper

  - **Data\_BootStrapperStateFailure\_OExceptionType** – Kiểu ngoại lệ mà chúng tôi không thành công

  - **Data\_Culture** - Văn hóa mà chúng tôi đang chạy exe này, ví dụ: en-us

  - **Data\_HashedOLSToken** - Hàm băm sha-256 của mã thông báo dịch vụ OLS cung cấp cho chúng tôi

  - **Data\_Platform** - Cài đặt x64 hoặc x86

  - **Data\_PrereqFailure\_Type** – Lỗi điều kiện tiên quyết mà chúng tôi gặp phải, ví dụ: hệ điều hành không được hỗ trợ

  - **Data\_ProductReleaseId** - Sản phẩm chúng tôi đang cài đặt, ví dụ: Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang chạy kiểm tra lỗi hỏng để đảm bảo rằng các nhị phân Office là chính xác. Sử dụng để đo lường lỗi hỏng của nhị phân Office và các nhị phân bị hỏng.

Các trường sau đây sẽ được thu thập:

  - **Data\_Active -** Tệp kê khai luồng hiện tại mà chúng tôi đang kiểm tra trên ổ đĩa

  - **Data\_ActivePackages -** Những điều có trong tệp kê khai

  - **Data\_ActiveVersion -** Phiên bản của tệp kê khai

  - **Data\_AddFileCount -** Số tệp chúng tôi đang thêm

  - **Data\_AddFileFiles -** Mẫu tệp mà chúng tôi đang thêm

  - **Data\_CompressionLevel -** Cách các tệp được nén

  - **Data\_CorruptionCheckLevel -** Cách chúng tôi đang kiểm tra cho lỗi hỏng, giai đoạn

  - **Data\_CorruptSizeCount -** Số lượng tệp có kích cỡ hỏng

  - **Data\_CorruptSizeFiles -** Mẫu của các tệp có một kích cỡ bị hỏng

  - **Data\_CorruptVersionCount -** Số lượng tệp có phiên bản bị hỏng

  - **Data\_CorruptVersionFiles -** Mẫu của các tệp có một phiên bản bị hỏng

  - **Data\_FileBadDigestCount -** Số tệp chúng tôi không mở thành công

  - **Data\_FileBadDigestFiles -** Mẫu của các tệp chúng tôi đã không thể mở

  - **Data\_FileNotSignedCount -** Số lượng tệp không được đăng nhập

  - **Data\_FileNotSignedFiles -** Mẫu của các tệp không được đăng nhập

  - **Data\_FileNotTrustedCount -** Số lượng tệp không đáng tin cậy

  - **Data\_FileNotTrustedFiles -** Mẫu của các tệp không đáng tin cậy

  - **Data\_IncompleteFileCount -** Số lượng tệp có vẻ như không đầy đủ

  - **Data\_IncompleteFileFiles -** Mẫu của các tệp có thể không đầy đủ

  - **Data\_KeepFileCount -** Số lượng tệp chúng tôi không thực hiện bất kỳ điều gì

  - **Data\_KeepFileFiles -** Mẫu các tệp chúng tôi đang duy trì

  - **Data\_KeepIncompleteFileCount -** Số lượng tệp chúng tôi đang không thay đổi dù chúng đang không đầy đủ

  - **Data\_KeepIncompleteFileFiles -** Mẫu của các tệp không đầy đủ chúng tôi đang duy trì

  - **Data\_MismatchSizeCount -** Số lượng tệp có kích cỡ không khớp với tệp kê khai của chúng tôi

  - **Data\_MismatchSizeFiles -** Mẫu của các tệp không khớp về kích cỡ

  - **Data\_MismatchVersionCount -** Số lượng tệp có phiên bản khác với tệp kê khai của chúng tôi

  - **Data\_MismatchVersionFiles -** Mẫu của các tệp có một phiên bản không khớp

  - **Data\_MissingFileCount -** Số lượng tệp có vẻ bị thiếu

  - **Data\_MissingFileFiles -** Mẫu của các tệp bị thiếu

  - **Data\_NotToBeStreamedFileCount -** Số lượng tệp chúng tôi đang không phát trực tuyến

  - **Data\_RemoveFileCount -** Số lượng tệp chúng tôi đang loại bỏ

  - **Data\_RemoveFileFiles -** Mẫu tệp mà chúng tôi đang loại bỏ

  - **Data\_StreamUnitsMismatchCount -** Số lượng tệp có đơn vị không khớp với tệp kê khai

  - **Data\_StreamUnitsMismatchFiles -** Mẫu của các tệp có luồng với đơn vị không khớp

  - **Data\_TimeElapsed -** Thời gian mà chúng tôi cần có để kiểm tra lỗi hỏng

  - **Data\_UpdateFileCount -** Số lượng tệp chúng tôi đang cập nhật

  - **Data\_UpdateFileFiles -** Mẫu của các tệp mà chúng tôi đang thêm

  - **Data\_Working -** Tệp kê khai mới mà chúng tôi đang kiểm tra

  - **Data\_WorkingVersion -** Phiên bản của tệp kê khai mới

### <a name="officeclicktorunmachinemetadata"></a>Office.ClickToRun.MachineMetadata

Thiết lập Office và dữ liệu kiểm kê cung cấp siêu dữ liệu cần thiết để thiết lập và kiểm kê và được sử dụng để xác định chính xác thông tin cơ bản về cài đặt.

Các trường sau đây sẽ được thu thập:

  - **Dữ liệu\_C2RClientVer** – Phiên bản của OfficeClickToRun.exe trên máy

  - **Data\_OfficeBitness** – Bitness mà Office được cài đặt, x86 hoặc x64

  - **Data\_OfficeVersion** - Phiên bản Office được cài đặt

  - **Data\_Sku** - Đã cài đặt SKU, nghĩa là Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn

  - **Data\_SqmMachineID** – ID máy duy nhất được sử dụng bơi dữ liệu Windows SQM\_SusClientID - Mã định danh cập nhật Office trên máy

### <a name="officeclicktorunodt"></a>Office.ClickToRun.ODT

Thiết lập Office và dữ liệu kiểm kê được thu thập khi người quản trị CNTT đang chạy Công cụ triển khai Office Click-to-Run setup.exe để sửa đổi sản phẩm Office được cài đặt của người dùng của họ. Được sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office do người quản trị CNTT khởi tạo đầy đủ bao gồm cả kiểm tra điều kiện tiên quyết.

Các trường sau đây sẽ được thu thập:

  - **Data\_BootStrapperStateFailure\_ErrorCode** – Mã lỗi chúng tôi không thành công

  - **Data\_BootStrapperStateFailure\_ErrorSource** – Hàm mà chúng tôi không thành công

  - **Data\_BootStrapperStateFailure\_FailingState** – Phần mà chúng tôi không thành công trong boot-strapper

  - **Data\_BootStrapperStateFailure\_OExceptionType** – Kiểu ngoại lệ mà chúng tôi không thành công

  - **Data\_ConfigurationHost-** Máy chủ lưu trữ configuration.xml

  - **Data\_ConfigurationId-** ID chúng tôi nhận được từ configuration.xml

  - **Data\_ConfigurationSource-** Nguồn configuration.xml

  - **Data\_Culture** - Văn hóa mà chúng tôi đang chạy exe này, ví dụ: en-us

  - **Data\_HashedOLSToken**  - Hàm băm sha-256 của mã thông báo dịch vụ OLS cung cấp cho chúng tôi

  - **Data\_MigrateArchRequest-** Nếu chúng tôi đang di chuyển người dùng từ x86 để x64 hoặc ngược lại

  - **Data\_MigrateArchRequestValid-** Nếu chúng tôi cho rằng yêu cầu di chuyển là hợp lệ

  - **Data\_Platform** - Cài đặt x64 hoặc x86

  - **Data\_PlatformMigratedFrom-** Nền tảng bắt đầu, ví dụ: x86

  - **Data\_PlatformMigratedTo-** Nền tảng kết thúc, ví dụ: x64

  - **Data\_PrereqFailure\_Type-** Lỗi tiên quyết mà chúng tôi gặp phải

  - **Data\_ProductReleaseId-** Sản phẩm chúng tôi đang cài đặt, ví dụ: Ứng dụng Microsoft 365 dành cho doanh nghiệp lớn

### <a name="officeclicktorunrepomanlogger"></a>Office.ClickToRun.RepomanLogger

Báo cáo về trạng thái đối với đường ống dẫn cập nhật Click-to-Run mới ("Repoman") và liệu sản phẩm có tải xuống và áp dụng thành công các bản cập nhật Office hay không.

Các trường sau đây sẽ được thu thập:

  - **ApplySucceeded -** Đúng nếu đường ống dẫn áp dụng thành công một bản cập nhật Office, sai nếu không thành công.
  
  - **DownloadSucceeded -** Đúng nếu đường ống dẫn tải xuống thành công một bản cập nhật Office, sai nếu không thành công.

  - **ErrorCode -** Mã của lỗi cuối cùng xảy ra trong đường ống dẫn Repoman Click-to-run.

  - **ErrorDetails -**  Thông tin lỗi bổ sung về lỗi cuối cùng xảy ra trong đường ống dẫn Repoman Click-to-run.
 
  - **ErrorMessage -** Thông báo của lỗi cuối cùng xảy ra trong đường ống dẫn Repoman Click-to-run.

  - **OpenStreamSessionSucceeded -** Đúng nếu đường ống dẫn tạo ra phiên thành công để truyền trực tiếp một bản cập nhật Office, sai nếu không thành công.

  - **RepomanErrorMessage -** Thông báo lỗi nhận được từ trepoman.dll.
 

### <a name="officeclicktorunscenarioinstalltaskconfigure"></a>Office.ClickToRun.Scenario.InstallTaskConfigure

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang đặt các tệp mới tải xuống. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails-** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskconfigurelight"></a>Office.ClickToRun.Scenario.InstallTaskConfigurelight

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office quyết định tệp cần được tải xuống. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskfinalintegrate"></a>Office.ClickToRun.Scenario.InstallTaskFinalintegrate

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang cài đặt giấy phép và thiết đặt đăng ký. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails-** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskfonts"></a>Office.ClickToRun.Scenario.InstallTaskFonts

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang cài đặt phông chữ. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskinitupdates"></a>Office.ClickToRun.Scenario.InstallTaskInitupdates

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang tạo thiết đặt để cập nhật hoạt động đúng. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office tạo mục nhập đăng ký cho ứng dụng Office Được sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltasklastrun"></a>Office.ClickToRun.Scenario.InstallTaskLastrun

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office hoàn tất cài đặt, ghim các phím tắt và tạo thiết đặt đăng ký cuối cùng. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskmigrate"></a>Office.ClickToRun.Scenario.InstallTaskMigrate

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang di chuyển cài đặt từ các phiên bản cũ hơn của Office. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskpublishrsod"></a>Office.ClickToRun.Scenario.InstallTaskPublishrsod

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang xuất bản đăng ký ảo cho lớp ảo hóa AppV. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy, ví dụ: cài đặt. 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskremoveinstallation"></a>Office.ClickToRun.Scenario.InstallTaskRemoveinstallation

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang loại bỏ các phần của Office khỏi thiết bị. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang tải xuống các tệp mới cho Office. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi được yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

Dữ liệu thiết lập Office và kiểm kê thu thập được khi trình cài đặt Office đang gỡ cài đặt phiên bản Office trước đó đã được cài đặt khỏi Cửa hàng. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskfinalintegrate"></a>Office.ClickToRun.Scenario.RepairTaskFinalintegrate

Dữ liệu thiết lập Office và kiểm kê thu thập được khi máy khách sửa chữa Office phát hành lại các tệp .msi và tiện ích mở rộng Office. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskfullrepair"></a>Office.ClickToRun.Scenario.RepairTaskFullrepair

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách sửa chữa Office tải xuống phiên bản mới nhất của ứng dụng khách Click-to-Run để chuẩn bị máy tính gỡ cài đặt và cài đặt lại. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskintegraterepair"></a>Office.ClickToRun.Scenario.RepairTaskIntegraterepair

Office thiết lập và kiểm kê dữ liệu được thu thập khi máy khách sửa chữa Office cố gắng sửa chữa một số mục nhập đăng ký sự cố đã biết. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskremoveinstallation"></a>Office.ClickToRun.Scenario.RepairTaskRemoveinstallation

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách sửa chữa Office xóa Office khỏi thiết bị để chuẩn bị cài đặt lại khi sửa chữa. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskintegrateupdate"></a>Office.ClickToRun.Scenario.UpdateTaskIntegrateupdate 

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run cập nhật giấy phép nếu cần. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskpublishrsod"></a>Office.ClickToRun.Scenario.UpdateTaskPublishrsod

Office được thiết lập và kiểm kê được thu thập khi máy khách Click-to-Run cập nhật thiết đặt đăng ký cho các nhị phân mới. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdateapply"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateapply

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run tắt các ứng dụng đang chạy nếu cần và cài đặt các tệp mới đã được tải xuống. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi được yêu cầu thêm vào 

  - **Data\_AvailableVersion to-** Phiên bản Office có sẵn để cập nhật

  - **Data\_CompletedWithoutActionInfo -** Lý do tại sao chúng tôi chưa hoàn tất kịch bản, ví dụ: ứng dụng đã được mở

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_CorruptionChecksOnly -** Cho biết nếu chúng tôi chỉ kiểm tra lỗi hỏng và không cập nhật

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_HardlinkingException -** Trường hợp ngoại lệ chúng tôi gặp phải khi tìm cách tạo liên kết cứng

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_PackageOperationSuccessful -** Việc chúng tôi hoàn thành thành công tác vụ của chúng tôi trên gói chương trình Office có đúng hay không

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

  - **Data\_WorkstationLockState -** Việc chúng tôi cho rằng máy tính bị khóa có đúng hay không

### <a name="officeclicktorunscenarioupdatetaskupdateclientdownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateclientdownload

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run tải xuống phiên bản mới hơn của chính nó. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdatedetection"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedetection

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run kiểm tra nếu có bản cập nhật mới. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi được yêu cầu thêm vào 

  - **Data\_AvailableVersion to-** Phiên bản Office có sẵn để cập nhật

  - **Data\_ComAction -** Một số nguyên đại diện cho một thao tác com chúng tôi thực hiện

  - **Data\_CompletedWithoutActionInfo -** Lý do tại sao chúng tôi chưa hoàn tất kịch bản, ví dụ: ứng dụng đã được mở

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_PackageUpdateAvailable -** Việc chúng tôi có sẵn phiên bản Office mới có đúng hay không

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdatedownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedownload

Dữ liệu thiết lập Office và kiểm kê thu thập được khi máy khách Click-to-Run đang tải xuống bản cập nhật mới. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi được yêu cầu thêm vào 

  - **Data\_AvailableVersion to-** Phiên bản Office có sẵn để cập nhật

  - **Data\_CompletedWithoutActionInfo -** Lý do tại sao chúng tôi chưa hoàn tất kịch bản, ví dụ: ứng dụng đã được mở

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_CorruptionChecksOnly -** Cho biết nếu chúng tôi chỉ kiểm tra lỗi hỏng và không cập nhật

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_FoundCorruptFiles -** Việc chúng tôi tìm thấy tệp hỏng có đúng hay không

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_PackageOperationSuccessful -** Việc chúng tôi hoàn thành thành công tác vụ của chúng tôi trên gói chương trình Office có đúng hay không

  - **Data\_PipelineExitCode -** Mã thoát mà đường dẫn tệp của chúng tôi đã trả về

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdatefinalize"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatefinalize

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang dọn dẹp từ bản cập nhật và khôi phục các ứng dụng đã mở trước đó. Sử dụng để đánh giá thành công/thất bại của bản cập nhật Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ: CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ: CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled -** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts -** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails -** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm vào 

  - **Data\_ProductsToRemove -** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID -** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktoruntransport"></a>Office.ClickToRun.Transport

Báo cáo về hành động tải xuống tệp để xác định vận hành có thành công hay không, loại hình tải xuống được thực hiện và các thông tin chẩn đoán.


- **BytesFromGroupPeers -** Byte từ các mạng nhóm ngang hàng, chỉ dành cho các bản tải xuống sử dụng Tối ưu hóa Phân phối

- **BytesFromHttp -**    Byte từ http, chỉ dành cho các bản tải xuống sử dụng Tối ưu hóa Phân phối

- **ByteFromInternetPeers -**   Byte từ các mạng Internet ngang hàng, chỉ dành cho các bản tải xuống sử dụng Tối ưu hóa Phân phối 

- **BytesFromLanPeers -**   Byte từ các mạng LAN ngang hàng, chỉ dành cho các bản tải xuống sử dụng Tối ưu hóa Phân phối 

- **cancelledJobs -** Số lượng yêu cầu bị hủy trong phiên

- **Connected -**   Liệu đã được kết nối với nguồn chưa

- **ErrorCode -**   Mã lỗi gần nhất

- **ErrorDetails -**     Thông tin chi tiết về lỗi gần nhất

- **ErrorMessage -**    Thông báo về lỗi gần nhất 

- **ErrorSource -**    Nguồn gốc của lỗi gần nhất, ví dụ như Connection, LoadFile hoặc LoadRange

- **FailedJob -**    Số lượng yêu cầu không thành công trong phiên

- **FileSize -**    Kích thước của tài nguyên

- **SourcePathNoFilePath -**    Đường dẫn nguồn của tài nguyên chỉ có nguồn http được báo cáo, đường dẫn tệp cục bộ hoặc đường dẫn UNC bị lọc ra

- **SucceededJobs -**   Số lượng yêu cầu thành công trong phiên

- **TotalJobs -**    Tổng số yêu cầu trong phiên

- **TotalRequestedBytes -**  Tổng số byte đã yêu cầu trong phiên

- **TotalTransferTime -**   Tổng thời gian chuyển giao trong phiên

- **TransferredBytes -**    Tổng số byte đã chuyển giao trong phiên

- **TransportType -**   Phương thức chuyển giao (Ví dụ: Trong bộ nhớ Tối ưu hóa phân phối, HTTP, Dịch vụ Truyền tải tệp thông minh dưới nền)



### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang tạo một luồng truyền dẫn để tải xuống các tệp Office. Được sử dụng để xác định trang thái của các công nghệ truyền dẫn khác nhau (ví dụ: HTTP, BITS, DO), điều này rất quan trọng để tải xuống Office đúng cách để cài đặt và cập nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_IsForeGroundStreaming**- Cho biết nếu chúng tôi đang phát trực tuyến trong mặt trước hoặc nền

  - **Data\_IsInstallMode** - 1 nếu chúng tôi đang cài đặt và tải xuống tệp, 0 nếu chúng tôi không làm điều đó

  - **Data\_SourceProtocol –** Nếu chúng tôi tải xuống từ mạng dữ liệu nội dung, CDN, máy chúng tôi cài đặt trên đó, cục bộ hoặc từ một tài nguyên trên mạng cục bộ,

  - **Data\_Status** - Thành công hay thất bại 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang hoàn thành trạng thái cập nhật

Các trường sau đây sẽ được thu thập:

  - **Data\_build** - Phiên bản Office hiện đang được cài đặt

  - **Data\_channel** – Kênh mà người dùng đang sử dụng

  - **Data\_errorCode** – Một mã số nguyên, xác định loại lỗi đã xảy ra, nếu có

  - **Data\_errorMessage** – Một chuỗi cung cấp mô tả về lỗi đã xảy ra, nếu có

  - **Data\_status** – Một trạng thái ngắn về những gì đã xảy ra trong quá trình cập nhật, chẳng hạn như thành công hoặc đã tải xuống

  - **Data\_targetBuild -** -Phiên bản Office chúng tôi đang thử cập nhật


### <a name="officeclicktorununiversalbootstrapperapplication"></a>Office.ClickToRun.UniversalBootstrapper.Application

Báo cáo kết quả thử nghiệm cài đặt từ đầu đến cuối

 - **ErrorCode –**   Giá trị nguyên liên kết với một ngoại lệ chưa được xử lý

 - **ErrorDetails –**    Chuỗi mô tả vị trí mà ở đó, ngoại lệ chưa được xử lý xảy ra (hàm, tệp, số đường truyền, các tham số bổ sung được thiết lập bởi trình loại bỏ)

 - **ErrorMessage –**    Chuỗi được xác định tại điểm mà ngoại lệ chưa được xử lý được đưa ra, từ đó mô tả bản chất của trạng thái không thành công

 - **ErrorType –**   Chuỗi mô tả danh mục của ngoại lệ chưa được xử lý

 - **ExitCode -**   Giá trị nguyên liên kết với kết quả của việc chạy trình khởi động, biểu thị sự so sánh phương thức thành công và không thành công cụ thể

### <a name="officeclicktorununiversalbootstrappercalculateparameters"></a>Office.ClickToRun.UniversalBootstrapper.CalculateParameters

Báo cáo về hành động giải thích lý do cho việc đầu vào được thu thập bằng cách sử dụng CollectParameters

- **BitField –**    Giá trị nguyên của đối số BitField cho chúng ta biết có yêu cầu kênh cài đặt/cập nhật cụ thể không. Ví dụ: Kênh Beta, Kênh hiện tại (Xem trước), Kênh hiện tại, Kênh Enterprise hàng tháng, Kênh Enterprise nửa năm một lần (Xem trước) hoặc Kênh Enterprise nửa năm một lần.

- **ChannelID –** Số nguyên thể hiện giá trị enum của kênh cập nhật/cài đặt đã chọn. Ví dụ: Kênh Beta, Kênh hiện tại (Xem trước), Kênh hiện tại, Kênh Enterprise hàng tháng, Kênh Enterprise nửa năm một lần (Xem trước), Kênh Enterprise nửa năm một lần, hoặc Không hợp lệ.

- **CMDMode –** Chuỗi thân thiện tương ứng với việc chuyển đổi chế độ tổng thể đã phát hiện trong đối số cmd được chuyển sang cho exe.

- **C2RClientUICulture –**  Văn hóa của Máy khách C2R để cài đặt

- **ErrorCode –**   Giá trị nguyên liên kết với một ngoại lệ chưa được xử lý

- **ErrorDetails –**    Chuỗi mô tả vị trí mà ở đó, ngoại lệ chưa được xử lý xảy ra (hàm, tệp, số đường truyền, các tham số bổ sung được thiết lập bởi trình loại bỏ)

- **ErrorMessage –**    Chuỗi được xác định tại điểm mà ngoại lệ chưa được xử lý được đưa ra, từ đó mô tả bản chất của trạng thái không thành công

- **ErrorType –**   Chuỗi mô tả danh mục của ngoại lệ chưa được xử lý

- **ExcludedApps –**    Chuỗi liệt kê tên các ứng dụng Office riêng lẻ được yêu cầu loại trừ khỏi bộ Office đã cài đặt

- **InstalledCabVersion –**    Phiên bản "16.0.xxxxx.yyyyy" của Máy khách Office C2R đã được cài đặt

- **InstalledProductVersion –**    Phiên bản "16.0.xxxxx.yyyyy" của sản phẩm Office C2R đã được cài đặt

- **IsC2RServiceRunning –**    Cờ Boolean cho biết liệu dịch vụ máy cục bộ của một Máy khách C2R hiện đại có đang được thiết lập và hoạt động trên thiết bị hay không

- **IsElevatedFlagSet –**    Cờ Boolean cho biết liệu trình khởi động đã thử nâng quyền của quản trị viên hay chưa

- **IsFireFlyInstalled –**    Cờ Boolean cho biết liệu Máy khách Office 2013 RTM C2R hiện được cài đặt hay chưa

- **IsFireflyServiceRunning –**    Cờ Boolean cho biết liệu dịch vụ máy cục bộ của một Máy khách 2013 RTM C2R có đang được thiết lập và hoạt động trên thiết bị hay không

- **IsOfficeInstalled –**    Cờ Boolean cho biết liệu Máy khách Office hiện đại đã được cài đặt hay chưa

- **OfficeCultures –**    Danh sách một chuỗi những văn hóa Office để cài đặt

- **OfficeSourceType –**    Chuỗi thân thiện liên kết với giá trị bộ đếm của nguồn cài đặt (CDN, HTTP, UNC, CMBITS, DVD, CỤC BỘ)

- **Origin –**    Giá trị chuỗi cho chúng ta biết nguồn gốc được hỗ trợ nào (Puerto Rico [PR], Singapore [SG], Dublin [DB]) nên được sử dụng cho việc phát trực tuyến cài đặt ban đầu

- **PlatformFromLink –**    Chuỗi cho biết hệ thống bit x86|x64|mặc định mà Office yêu cầu từ dịch vụ thiết lập C2R

- **PlatformOfExistingInstallation –**    Chuỗi cho biết liệu Office x86 hay X64 đã được cài đặt trên thiết bị

- **PlatformToInstall –**    Chuỗi cho biết quyết định cuối cùng về việc liệu Office x86 hay X64 nên được cài đặt. Các khả năng có thể là: tự hoạt động, đặt cấu hình, người tiêu dùng, tải xuống, trợ giúp, trình đóng gói

- **PRID –**    Giá trị chuỗi đại diện cho ID Bản phát hành sản phẩm được yêu cầu trong một tình huống cài đặt dành cho người tiêu dùng (ví dụ: "O365ProPlusRetail")

- **PridsToMigrateFromCentennial-**    Chuỗi các sản phẩm Office để di chuyển từ bản cài đặt Store sang Click-to-Run

- **ProductsToAdd –**    Chuỗi đã xê-ri hoá sẽ hướng dẫn Máy khách C2R về việc nên cài đặt tổ hợp Sản phẩm/Văn hóa nào

- **ProductsToMigrateFromO15C2R -**  Chuỗi các sản phẩm và văn hóa Office để chuyển từ một bản cài đặt Office 2013 Click-To-Run

- **ProductsToRemove –**    Chuỗi đã xê-ri hoá sẽ hướng dẫn Máy khách C2R về việc nên gỡ cài đặt tổ hợp Sản phẩm/ Văn hóa nào

- **SharedComputerLicensing –**    Boolean cho biết liệu Quản trị viên CNTT có yêu cầu thiết lập để bật tính năng "SharedComputerLicensing" hay không

- **ShouldActivate–**    Boolean cho biết liệu Quản trị viên CNTT có yêu cầu thử kích hoạt cấp phép tự động trong tệp configuration.xml của họ hay không

- **ShouldUninstallCentennial-** Cờ Boolean cho biết các sản phẩm Office từ Store nên được gỡ cài đặt

- **VersionToInstall –**    Giá trị chuỗi của phiên bản Office "16.0.xxxxx.yyyyy" đang được cài đặt
 

### <a name="officeclicktorununiversalbootstrappercollectembeddedsignature"></a>Office.ClickToRun.UniversalBootstrapper.CollectEmbeddedSignature

Báo cáo về hành động đọc đầu vào đã gắn thẻ từ chữ ký nhúng của exe.  Đây là một khái niệm chưa được chứng minh, việc lặp lại trước đó của setup.exe đã không diễn ra và là những gì chúng tôi đang dựa vào để truyền tải những lựa chọn về sản phẩm/ ngôn ngữ/ bitness của người dùng từ trang web tới quá trình bên trong setup.exe.
 
- **ErrorCode -**    Số nguyên được liên kết với một ngoại lệ chưa được xử lý

- **ErrorDetails –**    Chuỗi mô tả vị trí mà ở đó, ngoại lệ chưa được xử lý xảy ra (hàm, tệp, số đường truyền, các tham số bổ sung được thiết lập bởi trình loại bỏ)

- **ErrorMessage –**    Chuỗi được xác định tại điểm mà ngoại lệ chưa được xử lý được đưa ra, từ đó mô tả bản chất của trạng thái không thành công

- **ErrorType –**   Chuỗi mô tả danh mục của ngoại lệ chưa được xử lý

### <a name="officeclicktorununiversalbootstrappercollectparameters"></a>Office.ClickToRun.UniversalBootstrapper.CollectParameters

Báo cáo các tham số được sử dụng cho cài đặt Office

- **BitField –**    Giá trị nguyên của đối số BitField cho chúng ta biết có yêu cầu kênh cài đặt/cập nhật cụ thể không. Ví dụ: Kênh Beta, Kênh hiện tại (Xem trước), Kênh hiện tại, Kênh Enterprise hàng tháng, Kênh Enterprise nửa năm một lần (Xem trước) hoặc Kênh Enterprise nửa năm một lần.

- **ChannelID –** Số nguyên thể hiện giá trị enum của kênh cập nhật/cài đặt đã chọn. Ví dụ: Kênh Beta, Kênh hiện tại (Xem trước), Kênh hiện tại, Kênh Enterprise hàng tháng, Kênh Enterprise nửa năm một lần (Xem trước), Kênh Enterprise nửa năm một lần, hoặc Không hợp lệ.

- **CMDMode –** Chuỗi thân thiện tương ứng với việc chuyển đổi chế độ tổng thể đã phát hiện trong đối số cmd được chuyển sang cho exe. Các khả năng có thể là: tự hoạt động, đặt cấu hình, người tiêu dùng, tải xuống, trợ giúp, trình đóng gói

- **C2RClientUICulture –**  Văn hóa của Máy khách C2R để cài đặt

- **ErrorCode –**   Giá trị nguyên liên kết với một ngoại lệ chưa được xử lý

- **ErrorDetails –**    Chuỗi mô tả vị trí mà ở đó, ngoại lệ chưa được xử lý xảy ra (hàm, tệp, số đường truyền, các tham số bổ sung được thiết lập bởi trình loại bỏ)

- **ErrorMessage –**    Chuỗi được xác định tại điểm mà ngoại lệ chưa được xử lý được đưa ra, từ đó mô tả bản chất của trạng thái không thành công

- **ErrorType –**   Chuỗi mô tả danh mục của ngoại lệ chưa được xử lý

- **ExcludedApps –**    Chuỗi liệt kê tên các ứng dụng Office riêng lẻ được yêu cầu loại trừ khỏi bộ Office đã cài đặt

- **InstalledCabVersion –**    Phiên bản "16.0.xxxxx.yyyyy" của Máy khách Office C2R đã được cài đặt

- **InstalledProductVersion –**    Phiên bản "16.0.xxxxx.yyyyy" của sản phẩm Office C2R đã được cài đặt

- **IsC2RServiceRunning –**    Cờ Boolean cho biết liệu dịch vụ máy cục bộ của một Máy khách C2R hiện đại có đang được thiết lập và hoạt động trên thiết bị hay không

- **IsElevatedFlagSet –**    Cờ Boolean cho biết liệu trình khởi động đã thử nâng quyền của quản trị viên hay chưa

- **IsFireFlyInstalled –**    Cờ Boolean cho biết liệu Máy khách Office 2013 RTM C2R hiện được cài đặt hay chưa

- **IsFireflyServiceRunning –**    Cờ Boolean cho biết liệu dịch vụ máy cục bộ của một Máy khách 2013 RTM C2R có đang được thiết lập và hoạt động trên thiết bị hay không

- **IsOfficeInstalled –**    Cờ Boolean cho biết liệu Máy khách Office hiện đại đã được cài đặt hay chưa

- **OfficeCultures –**    Danh sách một chuỗi những văn hóa Office để cài đặt

- **OfficeSourceType –**    Chuỗi thân thiện liên kết với giá trị bộ đếm của nguồn cài đặt (CDN, HTTP, UNC, CMBITS, DVD, CỤC BỘ)

- **Origin –**    Giá trị chuỗi cho chúng ta biết nguồn gốc được hỗ trợ nào (Puerto Rico [PR], Singapore [SG], Dublin [DB]) nên được sử dụng cho việc phát trực tuyến cài đặt ban đầu

- **PlatformFromLink –**    Chuỗi cho biết hệ thống bit x86|x64|mặc định mà Office yêu cầu từ dịch vụ thiết lập C2R

- **PlatformOfExistingInstallation –**    Chuỗi cho biết liệu Office x86 hay X64 đã được cài đặt trên thiết bị

- **PlatformToInstall –**    Chuỗi cho biết quyết định cuối cùng về việc liệu Office x86 hay X64 nên được cài đặt

- **PRID –**    Giá trị chuỗi đại diện cho ID Bản phát hành sản phẩm được yêu cầu trong một tình huống cài đặt dành cho người tiêu dùng (ví dụ: "O365ProPlusRetail")

- **PridsToMigrateFromCentennial-** Chuỗi các sản phẩm Office để di chuyển từ bản cài đặt Store sang Click-to-Run

- **ProductsToAdd –**    Chuỗi đã xê-ri hoá sẽ hướng dẫn Máy khách C2R về việc nên cài đặt tổ hợp Sản phẩm/Văn hóa nào

- **ProductsToMigrateFromO15C2R -** Chuỗi các sản phẩm và văn hóa Office để chuyển từ một bản cài đặt Office 2013 Click-To-Run

- **ProductsToRemove –**    Chuỗi đã xê-ri hoá sẽ hướng dẫn Máy khách C2R về việc nên gỡ cài đặt tổ hợp Sản phẩm/ Văn hóa nào

- **SharedComputerLicensing –**    Boolean cho biết liệu Quản trị viên CNTT có yêu cầu thiết lập để bật tính năng "SharedComputerLicensing" hay không

- **ShouldActivate–**    Boolean cho biết liệu Quản trị viên CNTT có yêu cầu thử kích hoạt cấp phép tự động trong tệp configuration.xml của họ hay không

- **ShouldUninstallCentennial-** Cờ Boolean cho biết các sản phẩm Office từ Store nên được gỡ cài đặt

- **VersionToInstall–**    Giá trị chuỗi của phiên bản Office "16.0.xxxxx.yyyyy" đang được cài đặt

### <a name="officeclicktorununiversalbootstrapperexecute"></a>Office.ClickToRun.UniversalBootstrapper.Execute

Báo cáo về các hành động gây ảnh hưởng đến máy đã thực hiện, như từng được dữ liệu lấy lý do từ "CalculateParameters" xác định

- **AvailableClientVersionText –**    Giá trị chuỗi của phiên bản Máy khách C2R "16.0.xxxxx.yyyyy" được tìm thấy trong Trình mô tả phiên bản XML, giá trị này được sử dụng để xác định xem Máy khách C2R hiện cài đặt có nên cập nhật hay không

- **CleanFireflyAction -**    "đúng" nếu tác vụ CleanFireFlyAction được lên lịch hoạt động trong quá trình cài đặt này

- **CleanO15Action -**    "đúng" nếu tác vụ CleanO15Action được lên lịch hoạt động trong quá trình cài đặt này

- **CMDMode –** Chuỗi thân thiện tương ứng với việc chuyển đổi chế độ tổng thể đã phát hiện trong đối số cmd được chuyển sang cho exe. Các khả năng có thể là: tự hoạt động, đặt cấu hình, người tiêu dùng, tải xuống, trợ giúp, trình đóng gói

- **DeliveryMechanism -**    GUID "FFNRoot" được trích xuất từ Trình mô tả phiên bản XML (đóng dấu bởi RDX), điều này cho chúng ta biết nguồn dựng đến từ khán giả/ kênh nào

- **DownloadC2RClientAction -**    "đúng" nếu tác vụ DownloadC2RClientAction được lên lịch hoạt động trong quá trình cài đặt này

- **ErrorCode –**   Giá trị nguyên liên kết với một ngoại lệ chưa được xử lý

- **ErrorDetails –**    Chuỗi mô tả vị trí mà ở đó, ngoại lệ chưa được xử lý xảy ra (hàm, tệp, số đường truyền, các tham số bổ sung được thiết lập bởi trình loại bỏ)

- **ErrorMessage –**    Chuỗi được xác định tại điểm mà ngoại lệ chưa được xử lý được đưa ra, từ đó mô tả bản chất của trạng thái không thành công

- **ErrorType –**   Chuỗi mô tả danh mục của ngoại lệ chưa được xử lý

- **ExitCode -**    Giá trị nguyên liên kết với kết quả của việc trình khởi động chạy giai đoạn thực thi, biểu thị sự so sánh phương thức thành công và không thành công cụ thể

- **LaunchAction -**    "đúng" nếu tác vụ LaunchAction được lên lịch hoạt động trong quá trình cài đặt này

- **LaunchUpdateAction -**    "đúng" nếu tác vụ LaunchUpdateAction được lên lịch hoạt động trong quá trình cài đặt này

- **PreReqResult -**    Giá trị nguyên bộ đếm của kết quả khi thực hiện kiểm tra PreReq (đạt/ không đạt/ khởi chạy lại)

- **UnexpectedAction -**    "đúng" nếu tác vụ UnexpectedAction (trường hợp lỗi) được lên lịch hoạt động trong quá trình cài đặt này

- **VersionToInstall -**    Giá trị chuỗi của phiên bản Office "16.0.xxxxx.yyyyy" đang được cài đặt

### <a name="officeserviceabilitymanagerinventoryaddonheartbeat"></a>Office.ServiceabilityManager.InventoryAddon.Heartbeat

*[Sự kiện này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

Sự kiện này dùng để thu thập siêu dữ liệu tiêu chuẩn về mỗi lần chạy phần bổ trợ Hàng tồn kho, nằm trong Trình quản lý Khả năng bảo trì Office và dùng để thu thập thông tin kiểm kê Office về những máy mà người quản trị CNTT đã chọn. Siêu dữ liệu về nội dung đáng quan tâm cụ thể tại đây là mã ID phiên và dùng để liên kết đến các dữ liệu khác được lưu trữ trong một dịch vụ đám mây cho mỗi đối tượng thuê.

Sự kiện này không chứa trường bổ sung vì chỉ siêu dữ liệu có liên quan.

### <a name="officeserviceabilitymanagerinventoryaddonresults"></a>Office.ServiceabilityManager.InventoryAddon.Results

Sự kiện này đã được ghi nhật ký khi cuộc gọi đến các WebService được thực hiện trong phần bổ trợ của Trình quản lý Khả năng bảo trì Hàng tồn kho Click-to-Run, bất kể thành công hay thất bại. Đây là thao tác cuối cùng trong phần bổ trợ để theo dõi trạng thái hoạt động tổng thể.

Các trường sau đây sẽ được thu thập:

- **ActionDetail** -  Chi tiết bổ sung khi thất bại xảy ra.
   - Nếu yêu cầu HTTP thành công, ActionDetail sẽ bằng 0.
   - Nếu trường Kết quả không phải là OK (tức là không phải bằng 0), nghĩa là yêu cầu chưa được gửi, trường này sẽ ghi lại mã lỗi nội bộ tương tự như trường Kết quả.
   - Nếu trường Kết quả là OK (từc là bằng 0), nghĩa là mã phản hồi HTTP >= 300, trường sẽ ghi lại mã phản hồi HTTP (ví dụ: 404).

- **Result** - Cờ mã lỗi số được trả về bởi các API cuộc gọi dịch vụ web Office. – ví dụ: 3 nghĩa là có sự cố xảy ra trong khi khởi tạo đầu đề HTTP.

- **Type** - Thông tin loại bổ sung. Trong trường hợp Tồn kho, thông tin này cho biết loại tải trọng đang được gửi – ví dụ: đầy đủ hoặc chỉ chênh lệch thay đổi. 

-  **WebCallSource** - Một giá trị liệt kê (cụ thể là số nguyên) cho biết phần bổ trợ Trình quản lý Khả năng bảo trì là nguồn gốc của cuộc gọi:
   - Hàng tồn kho: 0
   - Cấu hình hàng tồn kho: 1
   - Chính sách hàng tồn kho: 2
   - Trạng thái Mạng lưới Hàng tồn kho: 3
   - Trình quản lý khả năng dịch vụ: 4
   - Khả năng quản lý: 5

### <a name="officeserviceabilitymanagerwebservicefailure"></a>Office.ServiceabilityManager.WebserviceFailure

Bất cứ khi nào cuộc gọi đến dịch vụ web trong một trong các phần bổ trợ Trình quản lý khả năng bảo trì Office không thành công, câu lệnh này sẽ được ghi lại. Thát bại có thể là do lỗi nội bộ hoặc không thể kết nối với dịch vụ web.

Các trường sau đây sẽ được thu thập:

- **Add-on** - Phần bổ trợ Trình quản lý Khả năng bảo trì Click-to-Run mà từ đó cuộc gọi dịch vụ web đã được thực hiện. Phần này có thể có các giá trị như hàng tồn kho, khả năng quản lý, v.v. được mã hóa là giá trị số.

- **Correlation ID** - Một GUID được tạo ngẫu nhiên cụ thể cho phiên bản hiện tại được gửi tới dịch vụ web để kết nối cuộc gọi giữa máy khách và máy chủ.

- **ErrorInfo** - Thông tin mã số lỗi số được trả về bởi các API cuộc gọi dịch vụ web Office.

- **ErrorMessage** - Một thông báo cung cấp thêm thông tin chuyên sâu về thất bại. Mỗi loại lỗi ánh xạ tới một chuỗi được mã hóa cứng, với một số loại lỗi ánh xạ tới nhiều chuỗi có thể tùy thuộc vào tính chất cụ thể của lỗi.

- **Function** - Hàm trong mã mà cuộc gọi hiện tại đã diễn ra.

- **Status** - Mã trạng thái HTTP được trả về bằng cuộc gọi đến dịch vụ web, ví dụ: 404, 500, v.v.


## <a name="enhanced-configuration-service-ecs-events"></a>Sự kiện Dịch vụ cấu hình nâng cao (ECS)

### <a name="officeexperimentationfeaturequerybatched"></a>Office.Experimentation.FeatureQueryBatched

Thu thập thông tin về Cổng tính năng/Cổng thay đổi được truy vấn bằng mã thực thi.

Các trường sau đây sẽ được thu thập:

  - **Count** - Số lượng cổng tính năng được truy vấn trong sự kiện hàng loạt này

  - **Features** - Thông tin về cổng được truy vấn.

  - **Sequence** - Thứ tự mà trong đó FeatureGate đã được truy vấn

### <a name="officeexperimentationflightnumberline"></a>Office.Experimentation.FlightNumberLine

Thu thập danh sách các cấu hình đã nhận được bằng máy khách từ ECS

Các trường sau đây sẽ được thu thập:

  - **ECSConfigs** - Danh sách cấu hình ECS được phân tách bằng dấu phẩy

  - **LockType** - Loại khóa FlightManager.

  - **TasFlightingVersion** - Số phiên bản

  - **TimeToLock** - Thời gian giữa khởi đầu liblet và khóa FlightManager

  - **UnmergedConfigs** - Danh sách các cấu hình không hợp nhất

### <a name="officeexperimentationtriggeranalysis"></a>Office.Experimentation.TriggerAnalysis

Sự kiện này giúp phân tích phạm vi trong việc sử dụng sản phẩm và các số liệu về hiệu suất (chẳng hạn như sự cố, bị treo, v.v.) cho tập hợp con những người dùng hoặc thiết bị đủ điều kiện dùng tính năng này, từ đó giúp đảm bảo rằng sản phẩm đang hoạt động đúng cách.

Các trường sau đây sẽ được thu thập:

  - **FeatureGate -** Xác định tập hợp các tính năng mà có thể áp dụng phân tích kích hoạt.

### <a name="onenoteflightdefault"></a>OneNote.FlightDefault
 
Sự kiện này đã được ghi nhật ký khi OneNote yêu cầu máy chủ ECS Server cung cấp giá trị chuyến bay.  Việc này đã được sử dụng để cho phép các tính năng thử nghiệm đối với những người dùng đã chọn tham gia vào việc nhận những chuyến bay như vậy.
 
Các trường sau đây sẽ được thu thập:
 
- **ConfigParam** - Cấu hình mà giá trị đó đang được truy nhập

## <a name="licensing-events"></a>Sự kiện cấp phép

### <a name="officeandroiddocsuipaywallcontrolautoredeempendingpurchaseresult"></a>Office.Android.DocsUI.PaywallControl.AutoRedeemPendingPurchaseResult

Phép đo từ xa kỹ thuật quan trọng để ghi lại kết quả của nỗ lực tự động tìm cách đổi các giao dịch mua đang chờ xử lý của người dùng. Phép đo từ xa của sản phẩm được sử dụng để đối chiếu thông tin giao dịch mua hàng với hệ thống thương mại của Microsoft nhằm hỗ trợ các lợi ích đăng ký liên quan.

Các trường sau đây sẽ được thu thập:

- **EventDate** – Dấu thời gian xảy ra sự kiện 

- **Result** – Int biểu thị kết quả enum của hoạt động. 

- **SessionID** – GUID để kết nối các sự kiện theo phiên

### <a name="officeandroiddocsuipaywallcontrolpaywalluishown"></a>Office.Android.DocsUI.PaywallControl.PaywallUIShown

Phép đo từ xa mức sử dụng quan trọng khi hiển thị quyền kiểm soát của Paywall cho người dùng. Được sử dụng để hiểu trải nghiệm mua hàng trong ứng dụng cho người dùng và tối ưu hóa trải nghiệm tương tự cho các phiên bản trong tương lai.

Các trường sau đây sẽ được thu thập:

- **EventDate** – Dấu thời gian xảy ra sự kiện 

- **IsModeFRE** – Boolean để chỉ ra loại trải nghiệm, hộp thoại Bán thêm hoặc Bộ chọn SKU

- **SessionID** – GUID để kết nối các sự kiện theo phiên

### <a name="officeandroiddocsuipaywallcontrolpurchasebuttonclicked"></a>Office.Android.DocsUI.PaywallControl.PurchaseButtonClicked

Phép đo từ xa mức sử dụng quan trọng để biết khi nào người dùng nhấp vào nút Mua. Được sử dụng để suy ra mẫu hình sử dụng và chỉ số chuyển đổi cho những người dùng cố gắng mua gói đăng ký trong ứng dụng.

Các trường sau đây sẽ được thu thập:

- **EventDate** – Dấu thời gian xảy ra sự kiện

- **IsDefaultSku** – Boolean cho biết nếu người dùng đang cố gắng mua Sku được hiển thị đầu tiên/mặc định

- **ProductID** – Chuỗi xác định gói đăng ký nào người dùng đang cố gắng mua như được định cấu hình trong cửa hàng

- **SessionID** – GUID để kết nối các sự kiện theo phiên

### <a name="officeandroiddocsuipaywallcontrolpurchaseresult"></a>Office.Android.DocsUI.PaywallControl.PurchaseResult

Phép đo từ xa kỹ thuật quan trọng để ghi lại kết quả của nỗ lực mua hàng do người dùng kích hoạt thủ công. Phép đo từ xa của sản phẩm được sử dụng để đối chiếu thông tin giao dịch mua hàng với hệ thống thương mại của Microsoft nhằm hỗ trợ các lợi ích đăng ký liên quan.

Các trường sau đây sẽ được thu thập:

- **EventDate** – Dấu thời gian xảy ra sự kiện 

- **IsModeFre** – Boolean cho biết liệu giao dịch mua được thực hiện từ màn hình FRE bán thêm hoặc Bộ chọn Sku

- **Result** – Int biểu thị kết quả enum của hoạt động.

- **SessionID** – GUID để kết nối các sự kiện theo phiên

### <a name="officeandroiddocsuipaywallcontrolpurchasetokenredemptionresponse"></a>Office.Android.DocsUI.PaywallControl.PurchaseTokenRedemptionResponse

*[Sự kiện này trước đây có tên Office.Android.DocsUI.Views.PurchaseTokenRedemptionResponse.]*

Phép đo từ xa của sản phẩm này được thu thập để theo dõi và ghi lại trạng thái giao dịch nội bộ và thông tin đối chiếu nhằm cải thiện độ tin cậy và hiệu suất. Microsoft sử dụng dữ liệu này để phân tích và cải thiện độ tin cậy và hiệu suất của các cơ chế xử lý và đối chiếu giao dịch nội bộ.

Các trường sau đây sẽ được thu thập:

- **MicrosoftPurchaseOrderId** - ID đơn đặt hàng Microsoft được gửi bởi Dịch vụ liên kết bán lẻ (RFS) cho các mục đích theo dõi.

- **ResponseCode** - Mã phản hồi HTTP (số nguyên)

- **StatusCode** - Mã trạng thái phản hồi RFS (số nguyên enum hữu hạn do RFS xác định)


### <a name="officeandroiddocsuipaywallcontrolseeallfeaturesanalytics"></a>Office.Android.DocsUI.PaywallControl.SeeAllFeaturesAnalytics

Chúng tôi thu thập phép đo từ xa mức sử dụng này để xem người dùng dành bao nhiêu thời gian trên màn hình "Xem thêm lợi ích".  Dữ liệu được sử dụng để hiểu mức sử dụng tính năng "Xem thêm lợi ích" và tối ưu hóa hơn nữa trải nghiệm trong các phiên bản tương lai.

Các trường sau đây sẽ được thu thập:

- **Duration** - Số nguyên dài cho biết thời gian người dùng dành cho màn hình “Xem tất cả tính năng” tính bằng mili giây

- **EventDate** - Dấu thời gian xảy ra sự kiện 

- **MostExplored** - Số nguyên biểu thị chỉ mục của mục được chuyển đổi nhiều nhất trong danh sách ứng dụng Microsoft 365 và tính năng của chúng

- **SessionID** - Mã nhận dạng duy nhất toàn cầu (GUID) để kết nối các sự kiện theo phiên

### <a name="officeandroiddocsuipaywallcontrolskuchooseranalytics"></a>Office.Android.DocsUI.PaywallControl.SkuChooserAnalytics

Phép đo từ xa mức sử dụng để xem người dùng dành bao nhiêu thời gian trên màn hình Bộ chọn SKU. Phép đo từ xa mức sử dụng để xem người dùng dành bao nhiêu thời gian trên màn hình Bộ chọn Sku.

Các trường sau đây sẽ được thu thập:

- **Duration** – Số nguyên dài cho biết thời gian người dùng dành cho màn hình Bộ chọn Sku tính bằng mili giây

- **EventDate** – Dấu thời gian xảy ra sự kiện

- **SessionID** – GUID để kết nối các sự kiện theo phiên


### <a name="officeandroiddocsuiviewsdimeerror"></a>Office.Android.DocsUI.Views.DimeError

Sự kiện này được thu thập cho ứng dụng Office for Android (được phát hành trên Huawei và ở các Cửa hàng Trung Quốc). Sự kiện này cho biết nỗ lực mua đăng ký Microsoft 365 qua Dime (một webURL được tải trong webview của máy khách) không thành công. Chỉ thu được các kịch bản lỗi. Dữ liệu của sự kiện này chỉ là dữ liệu lỗi và được sử dụng để đảm bảo trạng thái của dòng mua sản phẩm trên Dime trong máy khách.

Các trường sau đây sẽ được thu thập:

- **CorrelationID** - ID xác định duy nhất một phiên mua sản phẩm trên Dime.

- **ErrorReason** - Cho biết nguyên nhân xảy ra lỗi.
  - 0 – Lỗi không xác định
  - 1 – Không có internet
  - 2 – Xác thực mã định danh duy nhất toàn cầu (UUID) không thành công
  - 3 - Mã định danh duy nhất toàn cầu (UUID) null hoặc trống
  - 4 – Lỗi nạp JavaScript khi ứng dụng Office for Android không thể truyền authToken qua Dime
  - 5 – WebURL cơ sở được tải trên máy khách không hợp lệ


### <a name="officedimesdkhealth"></a>Office.Dime.Sdk.Health

Sự kiện này thu thập dữ liệu giúp giám sát trạng thái của các thành phần Dime. Ví dụ: đối với dòng mua sản phẩm trong ứng dụng khi người dùng chọn mua đăng ký Microsoft 365 từ trong ứng dụng Office for Android hoặc trên các thiết bị chạy Windows.

Các trường sau đây sẽ được thu thập:

- **Data_ActivityErrorDescription** - Mô tả lỗi của hoạt động

- **Data_ActivityErrorMessage** - Thông báo lỗi của hoạt động 

- **Data_CampaignId** - ID chiến dịch để phân bổ

- **Data_ContentId** - Sẽ được gắn phù hợp với ID luồng và ID nội dung dựa vào ID trải nghiệm

- **Data_CorrelationVector** - Vectơ tương quan để tương quan dime với các đối tác sử dụng vectơ tương quan

- **Data_CustomerImpacted** - Được sử dụng để khắc phục sự cố nếu khách hàng bị ảnh hưởng khi tải luồng

- **Data_DimeActivityDuration** - Thời gian diễn ra 

- **Data_DimeActivityMetadata** - Siêu dữ liệu hoạt động

- **Data_DimeActivityName** - Tên hoạt động để giám sát tình trạng

- **Data_DimeActivityResult** - Kết quả hoạt động, Thành công/Lỗi/Lỗi dự kiến

- **Data_DimeVersion** - Phiên bản dựng

- **Data_DurationLevel** - Mức độ nghiêm trọng - 0/1/2

- **Data_EcsConfigIds** - ID thử nghiệm

- **Data_EcsCountry** - Quốc gia bị phát hiện

- **Data_EcsETag** - Thông tin chuyến bay

- **Data_Environment** - Sản xuất/sản xuất trước môi trường dime

- **Data_ExperienceId** - Trải nghiệm tải 

- **Data_FlowId** - Sẽ được gắn phù hợp với ID luồng và ID nội dung dựa vào ID trải nghiệm

- **Data_Language** - Văn hóa

- **Data_Market** - Thị trường bị phát hiện

- **Data_OTelJS_Version** - Phiên bản phép đo từ xa Office

- **Data_PageSessionId** - ID phiên của trang

- **Data_PartnerId** - Ứng dụng người gọi

- **Data_QosLevel** - Mức độ nghiêm trọng 0/1/2

- **Data_SDX_AssetId** - ID nội dung của Trải nghiệm cung cấp dịch vụ (SDX) lưu trữ nội dung cho Win32

- **Data_SDX_BrowserToken** - Mã thông báo của trình duyệt cho Win32

- **Data_SDX_HostJsVersion** - Phiên bản thư viện JavaScript cho Win32

- **Data_SDX_Id** - ID Trải nghiệm cung cấp dịch vụ cho Win32

- **Data_SDX_InstanceId** - ID bản sao của SDX cho Win32

- **Data_SDX_MarketplaceType** - Loại thị trường SDX cho Win32

- **Data_SDX_OfficeJsVersion** - Phiên bản Office JS cho Win32

- **Data_SDX_SessionId** - ID phiên của SDX cho Win32

- **Data_SDX_Version** - Phiên bản SDX cho Win32

- **Data_TimestampUTC** - Dấu thời gian của sự kiện

- **Data_TsgId** - ID hướng dẫn khắc phục sự cố cho mỗi hoạt động

- **Data_UserAgent** - Thẻ tiêu đề

### <a name="officeiospaywallskuchooserbuybuttontap"></a>Office.iOS.Paywall.SKUChooser.BuyButtonTap

Phép đo từ xa mức sử dụng quan trọng được thu thập để cho biết khi nào người dùng nhấn vào nút Mua.  Dữ liệu được sử dụng để suy ra mẫu hình sử dụng và chỉ số chuyển đổi cho những người dùng cố gắng mua gói đăng ký trong ứng dụng.

Các trường sau đây sẽ được thu thập:

- **entryPoint** - Chuỗi – Nút/Dòng hiển thị Paywall. Như “Nút nâng cấp lên cao cấp” hoặc "Dòng chạy lần đầu".

- **isDefaultSKU** - Bool – Nếu người dùng đang mua sản phẩm, chúng tôi đề xuất cho họ bằng cách hiển thị sản phẩm theo mặc định.

- **productId** - Chuỗi – Id sản phẩm trong cửa hàng ứng dụng của sản phẩm mà nút Mua được nhấn vào

- **toggleCount** - Int – Số lần người dùng chuyển đổi giữa việc xem các sản phẩm khác nhau trước khi họ nhấn vào Nút Mua trong phiên hiện tại của Paywall.

### <a name="officeiospaywallsuccessscreenseeallbenefitsbuttontap"></a>Office.iOS.Paywall.SuccessScreen.SeeAllBenefitsButtonTap

Đo lường sử dụng từ xa để biết khi nào người dùng nhấn vào “Xem Tất cả Lợi ích”, sau khi mua hàng thành công để xem các ứng dụng và tính năng bao gồm trong giao dịch mua mà họ vừa thực hiện. Dữ liệu được sử dụng để giúp phát triển tính năng nâng cao trong tương lai nhằm giảm thiểu sự gián đoạn của người dùng trong quá trình cập nhật ứng dụng.

Các trường sau đây sẽ được thu thập:

- **productId** - Chuỗi - ID Ứng dụng của Microsoft Store của sản phẩm mà người dùng đang xem tất cả các lợi ích được cung cấp


### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Điều này được thu thập khi người dùng được cấp phép và chấp nhận EULA cho giấy phép hiện tại

Nó được sử dụng để phát hiện người dùng có ở trạng thái tốt hay không, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **ACID** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **DwEulaId** – Mã định danh dạng số của loại EULA vừa được người dùng chấp nhận

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Đăng thiết đặt giấy phép trên máy, chúng tôi cố gắng kích hoạt giấy phép bằng cách gọi điện cho dịch vụ AVS. Điều này báo cáo kết quả của cuộc gọi kích hoạt

Quan trọng là phát hiện số người dùng đang phải đối mặt với các vấn đề về kích hoạt. Chúng tôi có bất thường phát hiện để phát hiện bất kỳ hồi quy. Điều này là rất quan trọng vì chúng tôi có sự phụ thuộc bên ngoài vào AVS và tín hiệu này cho biết tình trạng của các đối tác bên ngoài của chúng tôi có tốt hay không. Nó cũng được sử dụng cho mục đích chẩn đoán và trạng thái hệ thống nếu người dùng báo cáo sự cố với các máy tính của họ

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **ReferralData** – Mã định danh của OEM đã cài đặt Office trên máy

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Nếu chúng tôi không thể tự động kích hoạt giấy phép vì một số lý do, chúng tôi sẽ hiển thị trình hướng dẫn kích hoạt cho người dùng. Điều này báo cáo rằng trình hướng dẫn được đang được hiển thị cho người dùng. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Sự kiện này không thu thập trường nào.

### <a name="officelicensingdialogswebviewdialogclose"></a>Office.Licensing.Dialogs.WebViewDialog.Close
 
Sự kiện này được sử dụng làm tín hiệu để cho chúng tôi biết rằng trải nghiệm mua hàng trong ứng dụng đang bị đóng bởi người dùng hoặc ứng dụng. Dữ liệu được sử dụng để giám sát và cảnh báo về trạng thái của luồng mua hàng trong ứng dụng nhằm đảm bảo tính năng này hoạt động như mong đợi.  
 
Các trường sau đây sẽ được thu thập:
 
- **Data_ClosedDialog** - cờ cho biết người dùng đã đóng hộp thoại

### <a name="officelicensingdialogswebviewdialoghandleerrornotification"></a>Office.Licensing.Dialogs.WebViewDialog.HandleErrorNotification
 
Sự kiện này được sử dụng làm tín hiệu để cho chúng tôi biết trải nghiệm mua hàng trong ứng dụng đã tìm cách tải nhưng lỗi đã xảy ra khiến hộp thoại không hiển thị. Dữ liệu được sử dụng để giám sát và cảnh báo về trạng thái của luồng mua hàng trong ứng dụng nhằm đảm bảo tính năng này hoạt động như mong đợi.  
 
Các trường sau đây sẽ được thu thập:
  
- **Data_MoeErrorCode** - Mã lỗi thấy trên khung hộp thoại web

### <a name="officelicensingdialogswebviewdialogpreload"></a>Office.Licensing.Dialogs.WebViewDialog.Preload
 
Sự kiện này được sử dụng làm tín hiệu để cho chúng tôi biết trải nghiệm mua hàng trong ứng dụng đang được tải trong nền. Dữ liệu được sử dụng để giám sát và cảnh báo về trạng thái của luồng mua hàng trong ứng dụng nhằm đảm bảo tính năng này hoạt động như mong đợi.  
 
Các trường sau đây sẽ được thu thập:

 - Không có

### <a name="officelicensingdialogswebviewdialogshow"></a>Office.Licensing.Dialogs.WebViewDialog.Show
 
Sự kiện này được sử dụng làm tín hiệu để cho chúng tôi biết trải nghiệm mua hàng trong ứng dụng đang hiển thị cho người dùng. Dữ liệu được sử dụng để giám sát và cảnh báo về trạng thái của luồng mua hàng trong ứng dụng.  

Các trường sau đây sẽ được thu thập:

 - Không có

### <a name="officelicensingdialogswebviewdialogtimeout"></a>Office.Licensing.Dialogs.WebViewDialog.Timeout

Sự kiện này được sử dụng làm tín hiệu để cho chúng tôi biết trải nghiệm mua hàng trong ứng dụng đã tìm cách tải nhưng đã hết thời gian. Dữ liệu được sử dụng để giám sát và cảnh báo về trạng thái của luồng mua hàng trong ứng dụng nhằm đảm bảo tính năng này hoạt động như mong đợi. 

Các trường sau đây sẽ được thu thập:

 - Không có


### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

Đây là tín hiệu cho chúng tôi biết nếu thử nghiệm mà chúng tôi đang chạy để thực thi đăng nhập người dùng như một phần của việc cấp phép có thành công hay không. Điều này rất quan trọng trong việc phát hiện thành công hay thất bại của thử nghiệm buộc người dùng phải đăng nhập, đây là bước bắt buộc đối với xếp chồng cấp phép hiện đại. Lỗi đăng nhập sẽ cho kết quả rằng người dùng không còn sử dụng ứng dụng.

Các trường sau đây sẽ được thu thập:

  - **Đủ điều kiện** – Xác định xem người dùng đủ điều kiện đối với việc thực hiện đăng nhập hay không

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Điều này được thu thập khi chúng tôi hiển thị hộp thoại hết hạn cho người dùng nói rằng giấy phép của họ đã hết hạn. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **LicNotificationState** – Bộ liệt kê cho chúng ta biết loại thông báo nào đang được hiển thị cho người dùng

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Điều này được thu thập trên mỗi phiên báo cáo trạng thái cấp phép của máy và báo cáo các lỗi mà người dùng đang gặp phải do họ không thể sử dụng ứng dụng. Sự kiện này cho biết nếu máy của người dùng có trạng thái tốt hay không. Chúng tôi đã phát hiện sự bất thường được thiết lập cho sự kiện này để cho biết liệu cơ chế hồi quy hoặc kích hoạt có gây ra hành vi xấu của người dùng hay không. Điều này cũng rất quan trọng khi chẩn đoán các vấn đề của người dùng và theo dõi trạng thái hệ thống.

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép 
  
  - **ActivationAttributes**- Loại cơ chế kích hoạt mà người dùng đang sử dụng.

  - **IsSessionLicensing** – Chúng tôi hiện có đang chạy dưới chế độ kích hoạt máy tính dùng chung hay không 

  - **LicenseCategory** – Danh mục giấy phép Office mà người dùng đang sử dụng 

  - **Licenses** – Danh sách tên của tất cả các giấy phép Office có trên máy 

  - **LicenseStatuses** – Trạng thái của tất cả các giấy phép Office có trên máy 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Chúng tôi thu thập điều này khi người dùng đang thiết lập một thiết bị và chúng tôi gọi dịch vụ cấp phép của chúng tôi để phát hiện xem người dùng đã đăng nhập có quyền Office hay không. Điều này báo cáo kết quả của cuộc gọi đó. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

- **EntitlementCount** – Số quyền được hưởng mà người dùng sở hữu


### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Trên mỗi phiên, chúng tôi kiểm tra xem đã qua 72 giờ kể từ khi gia hạn giấy phép mới nhất hay chưa và cố gắng gia hạn giấy phép hiện tại. Sự kiện này báo cáo sự thành công hay thất bại của cuộc gọi mà chúng tôi thực hiện để đảm bảo chúng tôi có thể gia hạn hết hạn giấy phép và giữ cho chức năng cài đặt Office của người dùng. Điều này rất quan trọng trong việc chẩn đoán các vấn đề liên quan đến đăng ký và các sự cố về dịch vụ cho người dùng cũng như trong việc phát hiện hồi quy cho người dùng đã kích hoạt đăng ký.

Các trường sau đây sẽ được thu thập:

  - **Mode** – Một đại diện bộ liệt kê của ngăn xếp cấp phép Office đang được sử dụng trên máy này

### <a name="officelicensinginclientpinredemptioncallpinredemptionapi"></a>Office.Licensing.InClientPinRedemption.CallPinRedemptionAPI

Phéo đo từ xa này theo dõi các kết quả của dịch vụ gọi điện thoại dịch vụ quy đổi của Office.

Các trường sau đây sẽ được thu thập:

- **ClientTransactionId** - Định danh duy nhất cho cuộc gọi dịch vụ.

- **ErrorCategory** - Từng loại lỗi có thể rơi vào danh mục chung khác, chẳng hạn như "Retryable".

- **ErrorType** - Lý do xảy ra lỗi, chẳng hạn như "AlreadyRedeemedByOther".

- **InAFOFlow** - Một boolean cho biết chúng tôi đang ở trong dòng thu hồi AFO.

- **StatusCode** - Kết quả gồm một từ của cuộc gọi dịch vụ, chẳng hạn như “Created”.

- **StatusMessage** - Thông tin chi tiết về mã trạng thái, như ‘Successfully provisioned."

- **UsingNulApi** - Một Boolean cho biết liệu chúng ta có đang sử dụng ngăn xếp bản quyền mới hay không.

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Nếu thiết bị chuyển về chế độ giảm chức năng, chúng tôi sẽ gửi tín hiệu này để cho biết rằng máy không ở trạng thái khỏe. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **ACID** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **DaysRemaining** - Số ngày còn lại trước khi giấy phép Office hiện tại hết hạn

  - **Mode** – Một đại diện bộ liệt kê của ngăn xếp cấp phép Office đang được sử dụng trên máy này

  - **ProductName** – Tên sản phẩm mà người dùng hiện đang sử dụng

  - **Reason** – Mã lỗi cho biết lý do cho tình trạng hiện tại của giấy phép

### <a name="officelicensinginstallkey"></a>Office.Licensing.InstallKey

Thông tin này được thu thập khi chúng tôi cố gắng cài đặt một khoá trên thiết bị để cấp phép máy. Nó báo cáo việc cài đặt có thành công hay không và nếu không thì là mã lỗi. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **Prid** – Tên của nhóm sản phẩm mà một khóa đang được cài đặt

  - **SkuId** - Mã định danh GUID đại diện cho sản phẩm Office mà một khóa đang được cài đặt 

### <a name="officelicensinginvokelicensewizard"></a>Office.Licensing.InvokeLicenseWizard

Trong trường hợp chúng tôi gặp sự cố với dòng công việc Kích hoạt, chúng tôi sẽ kích hoạt trình hướng dẫn cấp phép và gửi tín hiệu này để chỉ ra điều tương tự. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **LicenseCategory** – Trạng thái giấy phép Ofice mà người dùng đang sử dụng

  - **MachineKey** - Mã định danh chữ và số của khóa giấy phép đã được phát hành cho người dùng

### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Nếu thiết bị đang phải đối mặt với vấn đề cấp phép và cuối cùng chúng tôi hiển thị thanh cái cho người dùng, chúng tôi sẽ gửi tín hiệu này cũng báo cáo loại thanh cái được hiển thị cho người dùng. Điều quan trọng là cần phát hiện xem người dùng có đang trong trạng thái tốt và không bị thiếu chức năng hay không, kết quả này được dùng cho tình trạng hệ thống và mục đích chẩn đoán trong trường hợp người dùng báo cáo có sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **SuppressNotification** – Cho biết nếu chúng tôi ngăn thanh cái cấp phép

  - **Title** – Tiêu đề của thanh cái cấp phép được hiển thị cho người dùng

  - **Type** – Loại thanh cái cấp phép được hiển thị cho người dùng

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Nếu chúng tôi đóng hoặc gặp sự cố với Office do vấn đề cấp phép, chúng tôi sẽ gửi tín hiệu này để cho biết điều tương tự. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **ExitCode** – Mã nội bộ khiến ứng dụng bị thoát

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

Trong quá trình tìm cách giấy phép của thiết bị, ứng dụng sẽ thử tải danh tính của người dùng để xem người dùng có quyền Office hay không. Sự kiện này báo cáo trạng thái thành công hay thất bại cùng với mã lỗi. Điều quan trọng là cần phát hiện xem người dùng có đang trong trạng thái tốt và không bị thiếu chức năng hay không, kết quả này được dùng cho tình trạng hệ thống và mục đích chẩn đoán trong trường hợp người dùng báo cáo có sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **FederationProvider** – Chuỗi xác định nhà cung cấp liên kết cho người dùng hiện đang đăng nhập

  - **IdentityProvider** – Chuỗi xác định nhà cung cấp danh tính cho người dùng hiện đang đăng nhập

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Điều này được thu thập nếu chúng tôi hiển thị EULA cho người dùng và người dùng đã chọn không chấp nhận nó do chúng tôi gặp sự cố/đóng ứng dụng. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **OptInShown** – Cho biết liệu hộp thoại chọn tham gia sẽ hiển thị trong lần khởi động đầu tiên của ứng dụng đã hiển thị chưa

### <a name="officelicensingnextuserlicensingeligible"></a>Office.Licensing.NextUserLicensingEligible 

Thông báo này cho chúng ta biết một người dùng đủ điều kiện để chuyển sang ngăn xếp cấp phép mới hay không. Điều này rất quan trọng khi định lượng tác động đối với người dùng hiện có bởi vì chúng tôi sẽ triển khai ngăn xếp cấp phép mới của mình và đảm bảo rằng người dùng không bị mất chức năng.

Sự kiện này không thu thập trường nào.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Khi thiết bị nằm trong ngăn cấp phép hiện đại, chúng tôi sẽ cố gắng lấy tệp giấy phép trực tiếp từ dịch vụ. Sự kiện này báo cáo sự thành công hay thất bại cùng với mã lỗi cuộc gọi của dịch vụ đó. Điều quan trọng là phát hiện xem người dùng có ở trạng thái tốt trong ngăn xếp cấp phép hiện đại, được sử dụng cho tình trạng hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **MetadataValidationResult** – Kết quả xác thực siêu dữ liệu của giấy phép để xác minh rằng nó không bị giả mạo

  - **MetadataValidationResult** – Kết quả xác thực chữ ký của giấy phép để xác minh rằng nó đã không bị giả mạo

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Điều này được thu thập trên mỗi phiên một thiết bị đang chạy trên theo ngăn xếp cấp phép hiện đại. Điều này báo cáo trạng thái cấp phép của máy và báo cáo các lỗi mà người dùng đang gặp phải do họ không thể sử dụng ứng dụng. Sự kiện này cho biết máy của người dùng có hoạt động tốt trên ngăn xếp cấp phép hiện đại hay không. Chúng tôi có phát hiện bất thường được thiết lập cho sự kiện này để cho biết liệu hồi quy có gây ra hành vi xấu của người dùng hay không. Điều này cũng rất quan trọng khi chẩn đoán các vấn đề của người dùng và theo dõi trạng thái hệ thống.

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép 

  - **AllAcids** – Danh sách tất cả GUID sản phẩm mà người dùng hiện đang được cấp phép 

  - **Category** – Danh mục giấy phép Office mà người dùng đang sử dụng 

  - **DaysRemaining** - Số ngày còn lại trước khi giấy phép Office hiện tại hết hạn 

  - **LicenseId** - Mã định danh chữ và số của khóa giấy phép đã được phát hành cho người dùng 

  - **LicenseType** – Loại giấy phép Ofice mà người dùng đang sử dụng 

### <a name="officelicensingofficeclientlicensingdolicensevalidation"></a>Office.Licensing.OfficeClientLicensing.DoLicenseValidation 

Đây là siêu dữ liệu cấp phép được thu thập từ thiết bị trên mỗi lần khởi động báo cáo acid giấy phép, trạng thái giấy phép, loại và các thuộc tính khác của giấy phép rất quan trọng trong việc xác định các tính năng có sẵn cho người dùng. Điều này rất quan trọng trong việc xác định bộ tính năng có sẵn cho người dùng và nếu thiếu bất kỳ chức năng nào cho người dùng. Nó cũng được sử dụng cho người dùng hoạt động hàng ngày/người dùng hoạt động hàng tháng và nhiều báo cáo khác của các nhóm khác nhau trong Office vì điều này cho biết loại sản phẩm mà người dùng đang sử dụng, cho dù đó là sản phẩm đăng ký và họ có đang thiếu bất kỳ chức năng quan trọng nào.

Các trường sau đây sẽ được thu thập:

  - **FullValidationMode** – Chế độ cho biết rằng chúng tôi đang xác nhận đầy đủ xác minh giấy phép 

  - **IsRFM** – Cho biết người dùng có ở chế độ chức năng giảm hay không 

  - **IsSCA** – Cho biết liệu chúng tôi đang chạy trong chế độ kích hoạt máy tính được chia sẻ hay không 

  - **IsSubscription** – Cho biết liệu người dùng có đang sử dụng giấy phép đăng ký hay không 

  - **IsvNext** – Cho biết liệu chúng tôi có đang sử dụng ngăn xếp cấp phép hiện đại mới hay không 

  - **LicenseCategory** – Danh mục giấy phép Office mà người dùng đang sử dụng 

  - **LicenseCategory** – Trạng thái giấy phép Ofice mà người dùng đang sử dụng 

  - **LicenseType** - Loại giấy phép Ofice mà người dùng đang sử dụng 

  - **LicensingACID** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép 

  - **OlsLicenseId** - Mã định danh chữ và số của khóa giấy phép đã được phát hành cho người dùng 

  - **SkuIdIsNull** – Cho biết liệu chúng tôi có gặp phải lỗi hay không và không biết sản phẩm mà người dùng đang chạy 

  - **SlapiIsNull** – Cho biết liệu chúng tôi có gặp phải sự cố khi điền vào một trong các đối tượng cấp phép hay không 

### <a name="officelicensingonlinerepair"></a>Office.Licensing.OnlineRepair 

Nếu chúng tôi không thể kích hoạt người dùng vì một số lý do và phải cho họ xem hộp thoại yêu cầu họ truy cập trực tuyến và thử các bước sửa chữa, sự kiện này sẽ bị hủy. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Sự kiện này không thu thập trường nào.

### <a name="officelicensingoobetrybuychoice"></a>Office.Licensing.OOBE.TryBuyChoice

Người dùng có Office được cài đặt sẵn trên máy mới chưa có quyền được hưởng Office đã cho thấy một hộp thoại thông qua đó họ có thể thử, mua hoặc nhập một chìa khóa sản phẩm để đực cấp phép. Sự kiện này ghi lại hành động người dùng trên hộp thoại. Sự kiện này được sử dụng để theo dõi hành động của người dùng được thực hiện trên hộp thoại hiển thị cho người dùng không có quyền được hưởng Office cài đặt sẵn trên máy tính, đồng thời, giúp xác định xem người dùng được cấp phép hay chưa được cấp phép bằng cách thiết kế.

Các trường sau đây sẽ được thu thập:

- **Buy** - Cho biết người dùng đã bấm vào nút mua hay chưa

- **ForceAutoActivate** - Cho biết có cần phải kích hoạt trong ứng dụng hay không

- **GoBackToSignIn** - Cho biết người dùng muốn đăng nhập lại (có thể với một tài khoản khác) hay không

- **IsPin** - Cho biết người dùng đã nhập mã  hay chưa

- **ProductKey** - Cho biết người dùng đã nhập khóa sản phẩm chưa

- **Try** - Cho biết người dùng đã bấm vào nút mua hay chưa

- **UserDismissed** - Điều này cho biết liệu người dùng đã hủy bỏ hộp thoại hay chưa và do đó sẽ nằm trong chế độ ân huệ hoặc cắt giảm tính năng vì họ không chọn mua Office hoặc nhận bản dùng thử

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

*[Sự kiện này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

Chúng tôi thử cung cấp cho người dùng một tùy chọn để thử và thiết lập tự động thanh toán cho Office trực tiếp từ một ứng dụng mà không cần rời khỏi bối cảnh của ứng dụng. Qua đó, báo cáo sự thành công hay thất bại của thử nghiệm cùng với mã lỗi. Báo cáo này rất quan trọng trong việc phát hiện xem người dùng ở trạng thái tốt và không thiếu chức năng hay không. Báo cáo này dùng cho trạng thái hệ thống và cho mục đích chẩn đoán nếu người dùng báo cáo sự cố xảy ra với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **StorePurchaseStatus** – Đại diện cho mã lỗi/mã thành công của cuộc gọi mua hàng được thực hiện thông qua Windows Store

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Nếu người dùng đang chạy trong chế độ kích hoạt máy tính được chia sẻ, chúng tôi sẽ cố gắng tìm kiếm mã thông báo phiên trên máy cho phép người dùng sử dụng ứng dụng. Sự kiện này báo cáo trạng thái thành công hay thất bại của kịch bản cùng với mã lỗi. Điều quan trọng là cần phát hiện xem người dùng có đang trong trạng thái tốt và không bị thiếu chức năng hay không, kết quả này được dùng cho tình trạng hệ thống và mục đích chẩn đoán trong trường hợp người dùng báo cáo có sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **LoadLicenseResult** – Đại diện cho mã lỗi/mã thành công về việc chúng tôi có thể tải giấy phép cho người dùng hiện tại hay không

  - **OpportunisticTokenRenewalAttempted** – Cho biết liệu chúng tôi đã cố gắng gia hạn mã thông báo phiên người dùng một cách kịp thời hay chưa

  - **SetAcidResult** – Đại diện cho mã lỗi mã/thành công về việc chúng tôi có thể đặt axit thành giá trị mong đợi hay không

### <a name="officelicensingshownewdeviceactivationdialog"></a>Office.Licensing.ShowNewDeviceActivationDialog

Trong lần khởi động đầu tiên của ứng dụng Office, chúng tôi sẽ cố gắng hiển thị hộp thoại đăng nhập được điền trước thông tin đăng nhập mà người dùng sử dụng để tải xuống Office. Sau đó, người dùng có thể tiếp tục đăng nhập bằng các thông tin đăng nhập đó, sử dụng các thông tin đăng nhập khác nhau hoặc bỏ qua hộp thoại. Sự kiện này báo cáo hành động được thực hiện bởi người dùng khi được trình bày với hộp thoại này. Điều rất quan trọng để phát hiện xem người dùng ở trạng thái tốt trên ngăn xếp cấp phép hiện đại hay không, được sử dụng cho trạng hái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **UserAction** - Mã định danh hành động được thực hiện bởi người dùng khi được trình bày với hộp thoại này.

### <a name="officelicensingskutoskuconversion"></a>Office.Licensing.SkuToSkuConversion

Là một phần của việc cấp phép cho người dùng, nếu chúng tôi phải thay đổi SKU của người dùng từ SKU này sang SKU khác, chúng tôi sẽ gửi tín hiệu này cùng với mã thành công hoặc thất bại. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **DestinationSku** – Tên của SKU mà sản phẩm hiện được cài đặt sẽ được chuyển đổi thành

  - **PendingAcid** – Mã ID sản phẩm mà một chuyển đổi SKU đang chờ xử lý

  - **SourceSku** – Tên của SKU ban đầu đã được cài đặt trên máy

  - **UninstallProduct** – Cho biết liệu sản phẩm cũ sẽ được gỡ cài đặt như một phần của việc chuyển đổi hay không

### <a name="officelicensingtelemetryflowolsresults"></a>Office.Licensing.TelemetryFlow.OLSResults

Khi người dùng chưa được cấp phép, chúng tôi thực hiện một số cuộc gọi dịch vụ để đưa người dùng vào trạng thái được cấp phép và kích hoạt sản phẩm Office của mình.  Sự kiện này sẽ được kích hoạt khi gọi Dịch vụ cấp phép Office để kiểm tra xem người dùng có quyền được hưởng hay không.  Sự kiện này sẽ được sử dụng để theo dõi trạng thái cấp phép người dùng sau khi gọi Dịch vụ cấp phép Office và sức khỏe Máy khách Office sau khi cố gắng kích hoạt Office.

Các trường sau đây sẽ được thu thập:

- **EntitlementPickerShown** - Cho biết người dùng có nhiều quyền được hưởng và nếu người dùng phải chọn theo cách thủ công để có được cấp phép

- **GetAuthResult** - Cho biết các trạng thái khác nhau mà khách hàng có thể gặp tương tự như khi họ nhận được khóa sản phẩm rỗng từ Dịch vụ Cấp phép Office hoặc khi họ đã có quyền sử dụng đối với một sản phẩm khác và Office cần được chuyển đổi sang sản phẩm mới

- **EntitlementCount** - Cho biết số quyền được hưởng mà người dùng sở hữu

- **GetEntitlementsSucceeded** - Cho biết liệu cuộc gọi đến API Dịch vụ Cấp phép Office để truy xuất quyền được hưởng có thành công hay không.

- **GetKeySucceeded** - Cho biết liệu cuộc gọi đến API Dịch vụ Cấp phép Office để truy xuất chìa khóa có thành công hay không

- **GetNextUserLicenseResult** - Cho biết liệu ngăn xếp cấp phép hiện đại có thể làm việc và nếu người dùng đã được cấp phép hoặc không

- **InstallKeyResult** - Cho biết những lý do khác nhau tại sao người dùng có thể ở trạng thái xấu như khi kích hoạt không thành công hoặc quá trình cài đặt khóa không thành công

- **NotInitializedBeforeWhileAdding** - Đây chỉ là thông tin và cho biết liệu sự kiện đã được thêm vào bản đồ trình quản lý phép đo từ xa mà không cần đăng ký một cách rõ ràng cho nó hay không

- **NotInitializedBeforeWhileSending** - Đây chỉ là thông tin và cho biết liệu sự kiện đã được cố gửi đi mà không cần đăng ký một cách rõ ràng cho nó trong trình quản lý phép đo từ xa trước hay không

- **SentOnDestruction** - Đây chỉ là thông tin và cho biết liệu sự kiện đã được thêm vào bản đồ trình quản lý phép đo từ xa mà chưa được gửi một cách rõ ràng cho nó hay không

- **Tag** - Được sử dụng để cho biết sự kiến được gửi từ vị trí trong mã nào

- **VerifyEntitlementsResult** - Cho biết các trạng thái khác nhau mà người dùng có thể gặp sau khi phê chuẩn quyền được hưởng truy xuất từ Dịch vụ Cấp phép Office

### <a name="officelicensingtelemetryflowsearchforbindingresult"></a>Office.Licensing.TelemetryFlow.SearchForBindingResult

Các máy móc OEM có kèm theo Office (các đăng ký một năm hoặc vĩnh viễn).  Các sản phẩm Office này sẽ được thanh toán khi khách hàng mua máy tính của mình. Máy được thiết lập với một khóa đăng ký cụ thể (OOBEMode: OEMTA) có thể có ràng buộc Office liên kết với nó.  Khi chúng tôi khởi động Office trên các máy như vậy, chúng tôi sẽ thực hiện kiểm tra dịch vụ để xem liệu Office có liên quan đến tương ứng với máy không.

Hoạt động đo từ xa này theo dõi sự thành công cũng như thất bại trong việc tìm kiếm ràng buộc để chúng tôi có thể đảm bảo rằng các máy có ràng buộc có thể thực hiện tải thành công và dịch vụ của chúng tôi vẫn hoạt động tốt.  Hoạt động này không theo dõi máy không có bất kỳ sự kết hợp nào được liên kết với chúng sau khi chúng tôi kiểm tra với các dịch vụ của chúng tôi.

Các trường sau đây sẽ được thu thập:

- **DexShouldRetry** - Tín hiệu cho biết chúng tôi đã gặp sự cố có thể thử lại (không có internet hoặc máy chủ bị hỏng)

- **GenuineTicketFailure** - Cho chúng tôi biết KẾT QUẢ thất bại khi cố gắng lấy khóa sản phẩm/phiếu chính hãng Windows (WPK).

- **PinValidationFailure** - Cho chúng tôi biết lý do tại sao quá trình xác thực mã pin không thành công. Lỗi có thể xảy:
    - GeoBlocked
    - InvalidFormat
    - InvalidPin
    - InvalidState
    - InvalidVersion
    - Không xác định
    - Đã sử dụng

- **Lệnh PinValidationResult** - Cho chúng tôi biết kết quả xác nhận mã pin của một mã pin mà chúng tôi đã không thể crack.

- **Pkpn** - Dải pkpn chứa mã pin.

- **Success** - Cho biết rằng chúng tôi đã tải thành công một cơ sở Office ràng buộc hợp lệ (mã pin) cho máy.

- **Tag** - Cho chúng tôi biết tại bước nào chúng tôi đã ngừng tìm kiếm ràng buộc. Các thẻ có thể sử dụng:
  - 0x03113809    Không có lỗi Internet/dịch vụ trong khi xác thực mã pin
  - 0x0311380a    Xác thực mã pin thất bại, đã được gửi kèm trường PinValidationFailure
  - 0x0310410f    Thành công, đã được gửi với trường Thành công
  - 0x0311380d    Lỗi có thể thử lại (sự cố internet, lỗi không xác định)
  - 0x0311380e    Lỗi không thể thử lại (ưu đãi ràng buộc đã hết hạn)
  - 0x0311380f    Các lỗi khác (không thể cấp phép)
  - 0x03104111    Không thể bẻ khóa mã pin Office, được gửi kèm trường PinValidationResult

- **WpkBindingFailure** - Cho chúng tôi biết mã lỗi của việc nhận được mã pin Office được liên kết với WPK của máy.

### <a name="officelicensingtelemetryflowshowafodialogs"></a>Office.Licensing.TelemetryFlow.ShowAFODialogs

Sau khi nhận thành công một mã pin hợp lệ, bạn sẽ liên kết với một chiếc máy tính bảng cài sẵn Office, chúng tôi sẽ hiển thị một hộp thoại đăng nhập hoặc hộp thoại quy đổi.  Sau khi mã pin được quy đổi, chúng tôi sẽ hiển thị hộp thoại EULA.  Là một phần của tính năng hiện đại hóa AFO của chúng tôi, chúng tôi đã làm mới hai hộp thoại để truyền tải thêm thông tin về sản phẩm Office đi kèm với máy tính.  Phép đo từ xa này là để theo dõi xem liệu tính năng của chúng tôi có thành công trong việc làm giảm sự người dùng ma sát trong quy trình quy đổi sản phẩm của họ bằng cách theo dõi quy trình và các điểm thoát của quy trình quy đổi (hộp thoại bị bác bỏ).

Các trường sau đây sẽ được thu thập:

- **ActionActivate** - Tín hiệu cho biết người dùng đã bấm vào nút “Kích hoạt”.

- **ActionChangeAccount** -  Tín hiệu cho biết người dùng đã bấm vào siêu liên kết “Sử dụng tài khoản khác”.

- **ActionCreateAccount** - Tín hiệu cho biết người dùng đã bấm vào nút “Tạo tài khoản”.

- **ActionSignIn** - Tín hiệu cho biết người dùng đã bấm vào nút “Đăng nhập”.

- **CurrentView** - Loại hộp thoại người dùng đã đóng.

- **DialogEULA** -  Tín hiệu cho biết chúng tôi đã hiển thị hộp thoại “Chấp nhận EULA”. 

- **DialogRedemption** - Tín hiệu cho biết chúng tôi đã hiển thị hộp thoại quy đổi AFO.

- **DialogSignIn** - Tín hiệu cho biết chúng tôi đã hiển thị hộp thoại đăng nhập AFO.

- **EmptyRedemptionDefaults** - Tín hiệu cho biết chúng tôi không thể tải thông tin quy đổi mặc định.
 
- **GetRedemptionInfo** - Tín hiệu cho biết chúng tôi đang tải thông tin nhân khẩu học để quy đổi mã pin.

- **MalformedCountryCode** - Tín hiệu cho biết mã quốc gia cần để quy đổi mã pin không đúng.

- **OExDetails** - Chi tiết về lỗi chúng tôi nhận được khi hộp thoại đăng nhập danh tính đã bị bỏ qua.

- **OExType** - Loại lỗi chúng tôi quay trở lại khi hộp thoại đăng nhập danh tính bị bỏ qua.

- **Tag** - Cho chúng tôi biết tại bước nào người dùng thoát ra khỏi quy trình quy đổi AFO. Các thẻ có thể sử dụng:
    - 0x0311380b    Người dùng bỏ qua hộp thoại đăng nhập nhận dạng khỏi hộp thoại đổi quà
    - 0x0311380c    Không thể tự động tải đăng nhập danh tính người dùng từ hộp thoại đổi quà
    - 0x03113810    Không thể tải thông tin nhân khẩu học của tài khoản (mã quốc gia, ngôn ngữ, tiền tệ, ưu đãi bản dùng thử và tùy chọn tiếp thị)
    - 0x03113805    Người dùng bỏ qua hộp thoại đăng nhập danh tính khỏi hộp thoại đăng nhập
    - 0x03113806    Không tự động tải nhận dạng đăng nhập người dùng từ hộp thoại đăng nhập
    - 0x03113807    Không tự động tải lên nhận dạng
    - 0x03113811    Người dùng đóng hộp thoại đăng nhập/quy đổi
    - 0x03113812   Người dùng đóng hộp thoại chấp nhận EULA
    - 0x03113808   Người dùng đã chấp nhận EULA
    - 0x03113811      Người dùng đã đóng hộp thoại
    - 0x2370e3a0      Người dùng đã đóng hộp thoại
    - 0x2370e3c1      Đi đến web để quy đổi mã pin
    - 0x2370e3a1      Đi đến web để quy đổi mã pin
    - 0x2370e3c0      Chuỗi hộp thoại lặp do người dùng gây ra di chuyển qua lại trong luồng hộp thoại
    - 0x2370e3a3      Người dùng đã bấm vào siêu liên kết “Không phải bây giờ” sẽ bỏ qua khả năng cung cấp AFO cho phiên này
    - 0x2370e3a2      Người dùng đã bấm vào siêu liên kết “Đừng hiển thị cho tôi nữa” sẽ tắt khả năng cung cấp AFO


- **UseInAppRedemption** - Cho chúng tôi biết nếu chúng tôi giữ người dùng trong ứng dụng để đổi quà hoặc gửi họ đến web để đổi mã pin đã được tải (được điền trước).

- **UseModernAFO** - Cho chúng tôi biết rằng chúng tôi đang sử dụng trải nghiệm AFO mới hay cũ.

### <a name="officelicensingtelemetryflowshowtrybuydialogforoobe"></a>Office.Licensing.TelemetryFlow.ShowTryBuyDialogForOOBE

Khi máy mới cài đặt sẵn Office và người dùng không có quyền được hưởng, chúng tôi hiển thị hộp thoại cho phép người dùng dùng thử, mua hoặc nhập khóa sản phẩm để người dùng có thể nhận được cấp phép và sự kiện này theo dõi nếu hộp thoại được hiển thị. Sự kiện này sẽ giúp biết được liệu hộp thoại được hiển thị cho người dùng dùng thử, mua hoặc nhập khóa sản phẩm và do đó sẽ giúp chúng tôi xác định xem người dùng có cơ hội để có được cấp phép hay không.

Các trường sau đây sẽ được thu thập: 

- **ActiveView** - Cho biết mã ID hộp thoại được hiển thị cho người dùng

- **CurrentOOBEMode** - Cho biết chế độ cài đặt sẵn (OOBE Mode, như AFO, OEM v.v.)

- **NotInitializedBeforeWhileAdding** - Đây chỉ là thông tin và cho biết liệu sự kiện đã được thêm vào bản đồ trình quản lý phép đo từ xa mà không cần đăng ký một cách rõ ràng cho nó hay không

- **SentOnDestruction** - Đây chỉ là thông tin và cho biết liệu sự kiện đã được thêm vào bản đồ trình quản lý phép đo từ xa mà chưa được gửi một cách rõ ràng cho nó hay không

- **ShowTryButton** - Cho biết nếu nút Dùng thử được hiển thị cho người dùng trên hộp thoại hay không

- **Tag** - Được sử dụng để cho biết sự kiến được gửi từ vị trí trong mã nào

### <a name="officelicensingtelemetryflowtrialflow"></a>Office.Licensing.TelemetryFlow.TrialFlow

Khi một người dùng chưa được cấp phép của Office được cài đặt sẵn trên máy đang cố gắng lấy bản dùng thử, sự kiện này sẽ được kích hoạt.  Ứng dụng này được sử dụng để xem người dùng sẽ dùng cách nào để nhận bản dùng thử và nếu có bất kỳ lỗi nào khi nhận được bản dùng thử thông qua mua hàng trong ứng dụng.  Tùy theo hành động của người dùng và kết quả của việc mua hàng trong ứng dụng, người dùng có thể sẽ không được cấp phép.

Các trường sau đây sẽ được thu thập:

- **HasConnectivity** - Cho biết nếu người dùng có kết nối internet và trong trường hợp không có người dùng có thể phải sử dụng giấy phép gia hạn trong năm ngày hoặc có thể sử dụng ở chế độ chức năng bị giảm bớt

- **InAppTrialPurchase** - Cho biết xem chuyến bay đã được kích hoạt để khởi chạy Store Purchase SDK nhằm bắt lấy PI và mua bản dùng thử trong ứng dụng hay không *[Trường này đã bị loại bỏ khỏi bản dựng Office hiện tại, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **IsRS1OrGreater** - Cho biết liệu phiên bản OS lớn hơn RS1 hay không vì Store Purchase SDK chỉ nên được sử dụng nếu phiên bản OS lớn hơn RS1

- **NotInitializedBeforeWhileAdding** - Đây chỉ là thông tin và cho biết liệu sự kiện đã được thêm vào bản đồ trình quản lý phép đo từ xa mà không cần đăng ký một cách rõ ràng cho nó hay không

- **OEMSendToWebForTrial** - Cho biết liệu bạn đã kích hoạt tính năng sử dụng máy bay để chuyển người dùng đến web để quy đổi bản dùng thử chưa

- **StoreErrorConditions** - Cho biết các điều kiện khác nhau khi Store Purchase SDK có thể thất bại *[Trường này đã bị loại bỏ khỏi bản dựng Office hiện tại, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **StoreErrorHResult** - Cho biết mã lỗi được trả về từ the Store Purchase SDK *[Trường này đã bị loại bỏ khỏi bản dựng Office hiện tại, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **StorePurchaseStatusResult** - Cho biết kết quả khi gọi Store Purchase SDK và xem người dùng đã thực hiện mua hàng hay chưa, điều này sẽ giúp xác định xem người dùng có được cấp phép để sử dụng Office hay không *[Trường này đã bị loại bỏ khỏi bản dựng Office hiện tại, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **Tag** - Dùng để cho biết sự kiện được gửi từ vị trí trong mã nào

- **UserSignedInExplicitly** - Cho biết xem người dùng đã đăng nhập rõ ràng trong trường hợp nào, chúng tôi sẽ chuyển hướng lại người dùng đến web để lấy bản dùng thử *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Vì một số lý do nếu chúng tôi không thể cấp phép cho người dùng, chúng tôi sẽ cài đặt khóa gia hạn và gửi tín hiệu này để nhận biết. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **OpportunisticTokenRenewalAttempted** – Cho biết nếu chúng tôi đã thử gia hạn cho người dùng ở chế độ kích hoạt máy tính được chia sẻ hay chưa

  - **ReArmResult** – Cho biết kết quả của việc sắp xếp lại khóa đã cài đặt có thể kéo dài thời hạn của giấy phép hiện tại

### <a name="onenoteenrollmentresult"></a>OneNote.EnrollmentResult
 
Sự kiện này ghi nhật ký tình trạng này khi đăng ký Intune.  Kịch bản này là dành riêng cho các tài khoản được kích hoạt Intune.
 
Các trường sau đây sẽ được thu thập:
 
- **EnrollmentResult** - Kết quả của việc đăng ký Intune

## <a name="microsoft-autoupdate-mau-events"></a>Sự kiện Microsoft AutoUpdate (MAU)

### <a name="additionalappinfoinvalidpreference"></a>additionalappinfo.invalidpreference

Sự kiện này cho biết về tùy chọn không hợp lệ được đặt để hiển thị nhiều thông tin hơn về Kết thúc dịch vụ của một sản phẩm. Chúng tôi sử dụng thông tin này để khuyên khách hàng đặt tùy chọn chính xác để xem thông tin bổ sung.
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **Reason** - Chi tiết về mục nhập không hợp lệ trong các tùy chọn

- **SessionId** - Mã định danh của phiên

### <a name="appdelegatelaunch"></a>appdelegate.launch

Sự kiện này cho biết rằng đã xảy ra một lần thử khởi chạy ứng dụng. Chúng tôi ghi lại kết quả của sự kiện này (thất bại hoặc thành công). Chúng tôi sử dụng sự kiện này để xác định các trường hợp không thể khởi động MAU

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
    
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppversionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Một bộ văn bản tĩnh cho biết trạng thái khởi chạy.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="appdelegateterminate"></a>appdelegate.terminate

Sự kiện này cho biết đã xảy ra một lần Thoát ứng dụng mượt mà. Chúng tôi dùng sự kiện này để phân biệt giữa những lần Thoát ứng dụng mượt mà và những lần không mượt mà khác.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem
    
- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị
    
- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh cho biết Microsoft Autoupdate đã chấm dứt.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="appinstallconnecttoxpc"></a>appinstall.connecttoxpc

Sự kiện này cho biết đã xảy ra lỗi khi kết nối với Trình trợ giúp MAU (một cấu phần thực hiện cài đặt ứng dụng).  Sự kiện này biểu hiện ứng dụng MAU có dấu hiệu hỏng hóc. Thiết bị sẽ không thể cài đặt các bản cập nhật.

Các trường sau đây sẽ được thu thập:    

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Bao gồm thông tin về lỗi của sự cố kết nối.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="appinstalllogscanned"></a>appinstall_logscanned

Sự kiện này được sử dụng để xác định tệp nhật kí đã xử lý thành công hay không. Chúng tôi sử dụng sự kiện này để phát hiện và giải quyết các sự cố phát sinh trong quá trình cài đặt ứng dụng. 
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **Payload** – Báo cáo về các lỗi được tìm thấy trong quá trình cài đặt ứng dụng và/hoặc quét trạng thái hoàn thành 

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên

### <a name="appregistryconfig"></a>appregistry.config

Sự kiện này cho biết về các lỗi gặp phải trong quá trình tải thông tin đăng ký của ứng dụng. Chúng tôi sử dụng báo cáo này để khuyên các Quản trị viên CNTT về định dạng chính xác của việc thiết lập đăng ký ứng dụng máy khách.
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **Payload** – Chứa các thông tin về bản chất của lỗi gặp phải với đăng ký ứng dụng.

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên

### <a name="appregistryinfo"></a>appregistry.info

Sự kiện này cho biết ứng dụng đã khởi động. Chúng tôi dùng sự kiện này để liệt kê các ứng dụng mà MAU có thể kiểm soát được về bản cập nhật, số lượng bản sao sẵn dùng cũng như phiên bản và vị trí cài đặt của các ứng dụng đó (mặc định hoặc khác).

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Bao gồm thông tin về danh sách ứng dụng định danh dùng để đăng ký các dịch vụ của Microsoft Autoupdate và số lượng bản cài đặt đã đăng ký ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="appregistryremove"></a>appregistry.remove

Sự kiện này cho biết đã diễn ra một lần thử loại bỏ một Ứng dụng ra khỏi danh sách các ứng dụng quản lý bởi MAU. Chúng tôi dùng sự kiện này để xác nhận rằng MAU chỉ quản lý những ứng dụng được phát hành bởi MAU (không bao gồm bất kỳ ứng dụng AppStore nào).

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Đang loại bỏ tên và mã định danh của ứng dụng, cho dù ứng dụng vẫn tồn tại trong vị trí đã đăng ký và ứng dụng được cài đặt từ AppStore.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="catalogerrorsignature"></a>catalog_errorsignature

Sự kiện này báo cáo về các sự cố khác nhau với các tệp đã tải xuống, bao gồm cả chữ ký của nhà cung cấp và giá trị băm không khớp trên tệp đã tải xuống. Chúng tôi sử dụng sự kiện này để phát hiện sự cố khi xuất bản tập hợp tệp kê khai cho các ứng dụng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **FileHash** – Giá trị băm của tệp tải xuống

- **FileName** – Tên của tệp hiển thị giá trị băm không khớp

- **HashInCatalog** – Nhập giá trị băm trong tệp danh mục tương ứng

- **HowTocheck** - Sở thích kiểm tra các bản cập nhật

- **Payload** - chứa thông tin về sự cố báo cáo ứng dụng

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="cloningtaskbegin"></a>cloningtask_begin

Sự kiện này chỉ ra sự bắt đầu của tác vụ tạo bản sao trước khi cập nhật ứng dụng. Chúng tôi sử dụng sự kiện này cùng với sự kiện cloningtask.status để xác định số lần tạo bản sao không thành công để xác định tính năng tạo bản sao có nên được điều chỉnh trên các kênh người xem khác nhau hay không.
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppID** – Mã định danh của ứng dụng.

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên

- **UpdateID** – Mã định danh để cập nhật.


### <a name="cloningtaskhelpertoolconnection"></a>cloningtask.helpertoolconnection

Sự kiện này ghi lại sự cố khi cài đặt trên bản sao (nghĩa là chúng tôi không thể kết nối với trình trợ giúp để áp dụng bản cập nhật hoặc có thể kết nối nhưng trình trợ giúp lại không thể áp dụng bản cập nhật). Nếu chúng tôi nhận được một bản ghi được báo cáo, điều này có nghĩa là cài đặt trên bản sao đã thất bại và giờ sẽ phải chuyển sang thực hiện cập nhật tại chỗ.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Bao gồm ID để xác định một hoạt động cập nhật riêng lẻ và lỗi Proxy được ghi nhận trong quá trình sao chép.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="cloningtaskstatus"></a>cloningtask.status

Sự kiện này chỉ ra trạng thái của quy trình tạo bản sao đối với ứng dụng được cập nhật. Chúng tôi sử dụng sự kiện này để xác định tỷ lệ thành công cũng như loại lỗi gặp phải gây ra trường hợp không thành công. Sự kiện này được sử dụng để xác định tính năng tạo bản sao có nên được tiết lưu trên các kênh người xem khác nhau không.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Chuỗi này chứa thông tin lỗi nếu lỗi xảy ra trong tác vụ tạo bản sao.

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Chuỗi này đại diện cho một biến Boolean.

- **UpdateID** - Mã định danh để cập nhật.

### <a name="cloningtaskstatusfinish"></a>cloningtask.status.finish

Sự kiện này cho biết tác vụ “tạo bản sao” đã hoàn thành. Sự kiện này là một phần của báo cáo cập nhật hình phễu và chúng tôi sử dụng sự kiện này để xác định tình trạng của bản cập nhật ứng dụng.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **Success** - Cho biết tác vụ nhân bản có thành công hay không

- **UpdateID** - Mã định danh cập nhật.


### <a name="configurationchannel"></a>configuration.channel

Sự kiện này ghi lại các lần thử chuyển đổi kênh (Nhóm người xem) trong MAU.  Chúng tôi dùng sự kiện này để ghi lại các lần thử và kết quả (thành công hoặc thất bại).

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của kênh đã chọn.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="configurationmetadata"></a>configuration.metadata

Sự kiện này được ghi lại bất cứ khi nào MAU đang khởi đầu. Đây là kiểu sự kiện thông báo hoạt động của MAU

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh cho biết siêu dữ liệu riêng lẻ hoặc cấu hình đang được khởi tạo.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên.

### <a name="configurationsystemversion"></a>configuration.systemVersion

Sự kiện cho biết nỗ lực truy xuất phiên bản hệ thống đã không thành công. Sự kiện này còn chứa thông tin về thông tin Microsoft Auto Update (MAU) có thể thu thập từ hệ thống. Chúng tôi sử dụng sự kiện này để xác định MAU có nên hỗ trợ cho các trường hợp không thành công hay không. Ghi chú rằng phiên bản hệ thống được sử dụng để xác định một bản cập nhật có thể được áp dụng cho thiết bị của khách hàng hay không.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa thông tin về lỗi gặp phải trong quá trình truy xuất chuỗi phiên bản hệ thống macOS.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="controlleralertmanagerreinstallresponse"></a>controller.alertmanager.reinstallresponse

Sự kiện này cho biết rằng MAU bị rơi vào trạng thái không thể sử dụng/ không thể phục hồi và cần được cài đặt lại. Sự kiện này chỉ ra lỗi không thể phục hồi và cần có sự can thiệp của người dùng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa các lựa chọn được liệt kê ra của người dùng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controlleralertmanagertmpdiskfull"></a>controller.alertmanager.tmpdiskfull

Sự kiện này cho biết rằng đã phát hiện dung lượng đĩa không đủ. Chúng tôi sẽ không thể cài đặt các bản cập nhật do dung lượng đĩa không đủ.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controlleralertmanagertmpdiskfullretry"></a>controller.alertmanager.tmpdiskfullretry

Sự kiện này cho biết đã khởi tạo một lần thử cài đặt lại bản cập nhật sau khi phát hiện dung lượng đĩa không đủ. Chúng tôi sẽ thử cài đặt lại sau khi không thể cài đặt bản cập nhật do dung lượng đĩa không đủ.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên
    

### <a name="controlleralertmanagertmpdiskfullretrycancel"></a>controller.alertmanager.tmpdiskfullretrycancel

Sự kiện này cho biết đã hủy bỏ lần thử cài đặt lại sau khi phát hiện dung lượng đĩa không đủ. Chúng tôi dùng sự kiện này để xác định xem cơ chế dự phòng có đủ để hướng dẫn người dùng thông qua quá trình cập nhật khi phát hiện dung lượng đĩa không đủ hay không.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)
    
- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật
    
- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllercheckwindownoupdatefoundok"></a>controller.checkwindow.noupdatefoundok

Sự kiện này cho biết việc kiểm tra các bản cập nhật dẫn đến không tìm thấy bản cập nhật nào. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác, cũng như tối ưu hóa lượng tải dịch vụ và xác định tần suất kiểm tra bản cập nhật phù hợp. Chúng tôi cũng muốn tối ưu hóa nhịp độ phát hành dựa trên mong đợi về các bản cập nhật của người dùng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    

### <a name="controllercheckwindowupdatecheck"></a>controller.checkwindow.updatecheck

Sự kiện này cho biết đã thực hiện kiểm tra bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác, cũng như tối ưu hóa lượng tải dịch vụ và xác định tần suất kiểm tra bản cập nhật phù hợp. Chúng tôi cũng muốn tối ưu hóa nhịp độ phát hành dựa trên mong đợi về các bản cập nhật của người dùng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị
    
- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllercheckwindowupdatecheckcancel"></a>controller.checkwindow.updatecheckcancel

Sự kiện này cho biết quá trình kiểm tra bản cập nhật đã bị hủy (bởi người dùng hoặc hệ thống). Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác, cũng như tối ưu hóa lượng tải dịch vụ và xác định tần suất kiểm tra bản cập nhật phù hợp. Chúng tôi cũng muốn tối ưu hóa nhịp độ phát hành dựa trên mong đợi về các bản cập nhật của người dùng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllercheckwindowupdatecheckcanceluser"></a>controller.checkwindow.updatecheckcanceluser

Sự kiện này cho biết người dùng đã hủy quá trình kiểm tra bản cập nhật.  Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác, cũng như tối ưu hóa lượng tải dịch vụ và xác định tần suất kiểm tra bản cập nhật phù hợp. Chúng tôi cũng muốn tối ưu hóa nhịp độ phát hành dựa trên mong đợi về các bản cập nhật của người dùng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng
    
- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllercheckwindowupdatesfound"></a>controller.checkwindow.updatesfound

Sự kiện này cho biết đã tìm thấy các bản cập nhật từ quá trình kiểm tra bản cập nhật.  Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllercheckwindowuptodate"></a>controller.checkwindow.uptodate

Sự kiện này cho biết không tìm thấy bản cập nhật nào từ quá trình kiểm tra vì ứng dụng trong thiết bị đã được cập nhật.  Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowapplaunchwithpendingupdate"></a>controller.downloadwindow.applaunchwithpendingupdate

Sự kiện này cho biết một ứng dụng đã khởi chạy trong quá trình cập nhật. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác. Chúng tôi không nên cho phép các ứng dụng đang mở được cập nhật. Phải đóng các ứng dụng trước khi cập nhật.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP
    
- **SessionId** - Mã định danh của phiên

    
### <a name="controllerdownloadwindowcloseapplicationdialog"></a>controller.downloadwindow.closeapplicationdialog

Sự kiện này cho biết một ứng dụng đã khởi chạy trong quá trình cập nhật. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác. Chúng tôi không nên cho phép các ứng dụng đang mở được cập nhật. Phải đóng các ứng dụng trước khi cập nhật.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerdownloadwindowcurtasknull"></a>controller.downloadwindow.curtasknull

Sự kiện này cho biết đã xảy ra lỗi không mong muốn khi thử áp dụng bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerdownloadwindowdownloadcancel"></a>controller.downloadwindow.downloadcancel

Sự kiện này cho biết người dùng đã hủy quá trình tải xuống.  Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất một cách chính xác.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản tĩnh. 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerdownloadwindowdownloadfailed"></a>controller.downloadwindow.downloadfailed

Sự kiện này cho biết đã xảy ra lỗi khi tải xuống bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất và tải xuống đúng cách.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerdownloadwindowdownloadfailedok"></a>controller.downloadwindow.downloadfailedok

Sự kiện này cho biết đã xảy ra lỗi khi tải xuống bản cập nhật và người dùng đã được thông báo. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất và tải xuống đúng cách. Trong trường hợp xảy ra lỗi, người dùng sẽ nhận được thông báo.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowdownloadpathmissing"></a>controller.downloadwindow.downloadpathmissing

Sự kiện này cho biết đã xảy ra lỗi khi tải xuống bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất và tải xuống đúng cách. Sự kiện này cho biết URL tải xuống bị thiếu.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowdownloadtasknull"></a>controller.downloadwindow.downloadtasknull

Sự kiện này cho biết đã xảy ra lỗi khi tải xuống bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất và tải xuống đúng cách. Sự kiện này cho biết Microsoft Autoupdate đã được yêu cầu tạm dừng/ tiếp tục tải xuống nhưng lại không thể tìm thấy trình quản lý tải xuống tương ứng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowfilesignaturenotverified"></a>controller.downloadwindow.filesignaturenotverified

Sự kiện này cho biết đã xảy ra lỗi khi tải xuống bản cập nhật. Sự kiện này chỉ ra rằng Microsoft Autoupdate không thể xác minh bản cập nhật này do Microsoft phát hành. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất và tải xuống đúng cách. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản chứa URL tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowinstallcomplete"></a>controller.downloadwindow.installcomplete

Sự kiện này cho biết quá trình cài đặt tất cả các bản cập nhật do Microsoft Autoupdate đề xuất đã hoàn thành. Chúng tôi dùng sự kiện này để đảm bảo các bản cập nhật được đề xuất và tải xuống đúng cách. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng
    
- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindownetworkunavailablealert"></a>controller.downloadwindow.networkunavailablealert

Sự kiện này cho biết khả năng kết nối mạng bị mất trong khi đang tải xuống các bản cập nhật.  Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerdownloadwindownetworkunavailablealertok"></a>controller.downloadwindow.networkunavailablealertok

Sự kiện này cho biết khả năng kết nối mạng bị mất trong khi đang tải xuống các bản cập nhật. Sự kiện cũng cho biết người dùng đã được thông báo về lỗi này. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerdownloadwindownoconnectionok"></a>controller.downloadwindow.noconnectionok

Sự kiện này cho biết khả năng kết nối mạng bị mất trong khi đang tải xuống các bản cập nhật. Sự kiện cũng cho biết người dùng đã được thông báo về lỗi này. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowrepairrequired"></a>controller.downloadwindow.repairrequired

Sự kiện này cho biết quy trình cập nhật không thành công. Sự kiện cũng cho biết bản cập nhật đã hoàn tất nhưng Microsoft Autoupdate tìm thấy sự cố với ứng dụng đã cập nhật và yêu cầu sửa chữa. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)
    
- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị
    
- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="controllerdownloadwindowupdateaborted"></a>controller.downloadwindow.updateaborted

Sự kiện này cho biết quy trình cập nhật bị hủy bỏ. Sự kiện cũng cho biết Daemon đang trong quá trình tiến hành bản cập nhật nhưng người dùng bấm vào OK để huỷ tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowupdatefailed"></a>controller.downloadwindow.updatefailed

Sự kiện này cho biết một hoặc nhiều bản cập nhật từ lô hiện tại cài đặt không thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowupdatesuccessful"></a>controller.downloadwindow.updatesuccessful

Sự kiện này cho biết tất cả các bản cập nhật từ lô hiện tại đều cài đặt thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowuserpaused"></a>controller.downloadwindow.userpaused

Sự kiện này cho biết tất cả các bản cập nhật từ lô hiện tại đều cài đặt thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerdownloadwindowuserresumed"></a>controller.downloadwindow.userresumed

Sự kiện này cho biết quá trình tải xuống các bản cập nhật đã tiếp tục tiến hành thành công sau khi tạm dừng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
    
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllermainwindowsetautomaticchecking"></a>controller.mainwindow.setautomaticchecking

Sự kiện này cho biết thiết bị đã đăng ký chế độ Cập nhật tự động. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

 - **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllermainwindowsetautomaticdownloadinstall"></a>controller.mainwindow.setautomaticdownloadinstall

Sự kiện này cho biết thiết bị đã đăng ký chế độ Cập nhật tự động. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllermainwindowsetmanualchecking"></a>controller.mainwindow.setmanualchecking

Sự kiện này cho biết thiết bị đã đăng ký chế độ Cập nhật thủ công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllertemplateawindowcancel"></a>controller.templateawindow.cancel

Sự kiện này cho biết người dùng đã chọn hủy hoặc bỏ qua một thông báo cảnh báo được đưa ra. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllertemplateawindowenroll"></a>controller.templateawindow.enroll

Sự kiện này cho biết người dùng đã chọn làm theo đề xuất cảnh báo được đưa ra. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật
    
- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên



### <a name="controllertemplateawindowinstall"></a>controller.templateawindow.install

Sự kiện này cho biết người dùng đã chọn làm theo đề xuất cảnh báo được đưa ra và đề xuất này liên quan đến việc khởi chạy hành động cài đặt phần mềm. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerupdatewindowbegindownloadingapps"></a>controller.updatewindow.begindownloadingapps

Sự kiện này cho biết đã bắt đầu tải xuống bản cập nhật thông qua Cửa sổ cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa từ điển của các gói cập nhật sẵn dùng và thông báo dù người dùng đã chọn cài đặt mục nhập đó.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerupdatewindownetworkretry"></a>controller.updatewindow.networkretry

Sự kiện này cho biết đã kích hoạt thử lại trong trang tính Cập nhật do sự cố lỗi mạng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerupdatewindownetworkretrycancel"></a>controller.updatewindow.networkretrycancel

Sự kiện này cho biết đã không thể kích hoạt thử lại trong trang tính Cập nhật do sự cố lỗi mạng. Sự kiện này cho thấy người dùng đã chọn hủy cập nhật sau khi được cảnh báo về vấn đề mạng đang ngoại tuyến. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerupdatewindownetworkunavailable"></a>controller.updatewindow.networkunavailable

Sự kiện này cho biết khả năng kết nối mạng bị mất một cách đột ngột. Sự kiện này cho thấy không thể truy cập máy chủ trong khi cố gắng tải xuống gói cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerupdatewindownoupdateavailable"></a>controller.updatewindow.noupdateavailable

Sự kiện này cho biết không tìm thấy bản cập nhật sẵn dùng nào sau khi tìm kiếm bản cập nhật. Sự kiện này cho thấy Microsoft Autoupdate không tìm thấy bản cập nhật sẵn dùng nào. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerupdatewindownoupdatestoselect"></a>controller.updatewindow.noupdatestoselect

Sự kiện này cho biết đã xảy ra lỗi dẫn đến danh sách cập nhật trống. Sự kiện này cho thấy Microsoft Autoupdate đang hiển thị trang tính cập nhật trống. Điều này không nên xảy ra. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="controllerupdatewindowupdateavailable"></a>Controller.UpdateWindow.UpdateAvailable

Sự kiện này cho biết có bản cập nhật được đề xuất sau khi tìm kiếm bản cập nhật. Chúng tôi dùng sự kiện này để xác định xem liệu người dùng có nhìn thấy các bản cập nhật được đề xuất, liệu các bản cập nhật phù hợp có hiển thị hay liệu việc chặn cập nhật có hoạt động theo dự kiến hay không. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa từ điển của các gói cập nhật sẵn dùng và trạng thái lựa chọn của người dùng đối với từng ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="controllerupdatewindowupdateavailablecancel"></a>controller.updatewindow.updateavailablecancel

Sự kiện này cho biết người dùng đã hủy sau khi chúng tôi hiển thị trang tính mới liệt kê những thông tin cập nhật. Chúng tôi dùng sự kiện này để giải thích lý do không cập nhật (nghĩa là người dùng sẵn lòng hủy). Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadactorpause"></a>downloadactor.pause

Sự kiện này cho biết người dùng đã đưa ra yêu cầu tạm dừng tải xuống. Chúng tôi dùng sự kiện này để giải thích lý do cập nhật có vẻ chưa hoàn tất. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadactorredirect"></a>downloadactor.redirect

Sự kiện này cho biết tác vụ trình tải xuống được trỏ đến điểm kết thúc, điều này dẫn đến URL chuyển hướng để đáp ứng yêu cầu tải xuống. Chúng tôi dùng sự kiện này để giải thích lý do tải xuống không thành công và chẩn đoán sự cố proxy. Sự kiện cũng giúp chẩn đoán lý do tại sao chúng tôi nhận thấy người dùng cài đặt các bản dựng cũ. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa URL chuyển hướng. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="downloadactorresume"></a>downloadactor.resume

Sự kiện này cho biết người dùng đưa ra yêu cầu tiếp tục bản tải xuống đang tạm dừng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadactorresumeerror"></a>downloadactor.resumeerror

Sự kiện này cho biết người dùng đưa ra yêu cầu tiếp tục bản tải xuống đang tạm dừng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa đường dẫn URL tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="downloadactorstatus"></a>downloadactor.status

Sự kiện này ghi lại đã có những lần thử tải các tệp bổ sung và kết quả của những lần thử này (Thành công hoặc Thất bại). Chúng tôi muốn biết các tệp bổ sung và gói đang được tải xuống. Việc tải một tệp không đúng có thể biểu hiện sự cố về bản dựng/ tệp bổ sung. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa URL tải xuống và mã lỗi trong trường hợp không thành công. URL tải xuống là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestconfiguration"></a>downloadmanifest.configuration

Sự kiện này báo cáo lỗi với cấu hình Microsoft Auto Update (MAU) - kèm theo thiết lập Máy chủ Tùy chỉnh trong tùy chọn hay trong định nghĩa điểm cuối trong cấu phần MAU đã cài đặt. Chúng tôi sử dụng sự kiện này để khuyên các Quản trị viên CNTT đặt điểm cuối của Máy chủ bản kê một cách chính xác.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **Payload** -Chỉ ra lỗi nằm trong thiết lập máy chủ tùy chỉnh hay các cấu phần MAU đã cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestdownloadcatalogfail"></a>downloadmanifest.downloadcatalogfail

Sự kiện này đã xảy ra lỗi tải xuống. Tệp không thể tải xuống đã được ghi lại. Chúng tôi muốn biết các tệp bổ sung và gói đang được tải xuống. Việc không thể tải xuống tệp kê khai có thể chỉ ra đó là lỗi khởi tạo tệp bổ sung của bản dựng hoặc lỗi cấu hình CDN, lỗi cấu hình máy khách hay lỗi mạng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã lỗi tải xuống và URL của tệp tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="downloadmanifestdownloadcatalogsuccess"></a>downloadmanifest.downloadcatalogsuccess

Sự kiện này cho biết tệp đã được tải xuống thành công. Việc không thể tải xuống tệp kê khai có thể chỉ ra đó là lỗi khởi tạo tệp bổ sung của bản dựng hoặc lỗi cấu hình CDN, lỗi cấu hình máy khách hay lỗi mạng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
    
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã lỗi tải xuống và URL của tệp tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestdownloadfail"></a>downloadmanifest.downloadfail

Sự kiện này cho biết đã xảy ra lỗi tải xuống. Tệp kê khai hoặc tệp gói không thể tải xuống và chi tiết lỗi đã được ghi lại. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã lỗi tải xuống và URL của tệp tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestdownloadfromurl"></a>downloadmanifest.downloadfromurl

Sự kiện này cho biết đã bắt đầu tải xuống tệp danh mục. Chúng tôi đã ghi lại URL của tệp danh mục đang tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã lỗi tải xuống và URL của tệp tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestdownloading"></a>downloadmanifest.downloading

Sự kiện này cho biết đã bắt đầu tải xuống tệp danh mục. Chúng tôi đã ghi lại URL của tệp danh mục đang tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã lỗi tải xuống và URL của tệp tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestdownloadsuccess"></a>downloadmanifest.downloadsuccess

Sự kiện này cho biết việc tải xuống tệp XML và tệp gói đã thành công. Chúng tôi đã ghi lại URL của tệp đang tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã lỗi tải xuống và URL của tệp tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="downloadmanifestdownloadurl"></a>downloadmanifest.downloadurl

Sự kiện này cho biết có một yêu cầu tải xuống tệp. Chúng tôi đã ghi lại URL của tệp đang tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
    
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã lỗi tải xuống và URL của tệp tải xuống. Đây là vị trí tải xuống của Microsoft trừ khi kênh được đặt thành Tùy chỉnh. Đối với kênh Tuỳ chỉnh, giá trị này được đặt thành "Vị trí tùy chỉnh".

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestfilenameerror"></a>downloadmanifest.filenameerror

Sự kiện này cho biết đã xảy ra lỗi không mong muốn. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestinvalidhash"></a>downloadmanifest.invalidhash

Sự kiện này cho biết việc xác thực bảo mật cho các tệp của chúng tôi không thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của tệp đã tải xuống kèm giá trị hàm băm không hợp lệ.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestmissingdaemon"></a>downloadmanifest.missingdaemon

Sự kiện này cho biết người dùng thử kiểm tra bản cập nhật và chúng tôi phát hiện ra MAU bị thiếu một thành phần cốt lõi (daemon). Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifestsignatureerror"></a>downloadmanifest.signatureerror

Sự kiện này cho biết việc xác minh mã chữ ký cho gói không thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của tệp đã tải xuống kèm giá trị hàm băm không hợp lệ.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmanifeststatus"></a>downloadmanifest.status

Sự kiện này ghi lại một tập hợp tóm tắt các lần thử/ sự cố đã xảy ra trong quá trình tải xuống tệp kê khai và tệp gói. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa các thông tin bao gồm URL (địa chỉ Microsoft), tiền tố của tệp đang tải xuống, bất kỳ lỗi nào gặp phải, v.v.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmgrdownloadend"></a>downloadmgr.downloadend

Sự kiện này ghi lại dấu hiệu cho biết quá trình tải xuống đã tự hoàn tất. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa các thông tin bao gồm URL (địa chỉ Microsoft), tiền tố của tệp đang tải xuống, bất kỳ lỗi nào gặp phải, v.v.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="downloadmgrdownloadstart"></a>downloadmgr.downloadstart

Sự kiện này ghi lại bản cập nhật sắp được tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của bản cập nhật đang được tải xuống.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="downloadtaskdownloadbegin"></a>downloadtask.downloadbegin

Sự kiện này cho biết sự bắt đầu của hoạt động tải xuống của một bản cập nhật ứng dụng. Sự kiện này là một phần của phễu cập nhật và chúng tôi sử dụng sự kiện này để xác định tình trạng của bản cập nhật ứng dụng.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **BundleVersion** - Phiên bản của ứng dụng đang được cập nhật

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **PreviousUpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdatePkg** - Tên của gói cập nhật đang được áp dụng

- **UpdateVersion** - Phiên bản của ứng dụng sau khi cập nhật


### <a name="downloadtaskdownloadfailure"></a>downloadtask.downloadfailure

Sự kiện này ghi lại đã xảy ra lỗi khi tải xuống tệp gói. Chúng tôi đã ghi lại đường dẫn cập nhật và lỗi. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** – Mã định danh của ứng dụng đã không thể được tải xuống.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** – Các lỗi quan sát trong quá trình tải xuống.

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của bản cập nhật đang được tải xuống và lỗi chúng tôi quan sát được. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **UpdateID** – Mã định danh của bản cập nhật đang được tải xuống.


### <a name="downloadtaskdownloadsuccess"></a>downloadtask.downloadsuccess

Tải xuống tệp gói thành công. Chúng tôi đã ghi lại đường dẫn cập nhật được sử dụng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** – Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa đường dẫn cập nhật của bản tải xuống thành công.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **UpdateID** – Mã định danh của bản cập nhật đã được tải xuống.

### <a name="downloadtaskupdatertypeerror"></a>downloadtask.updatertypeerror

Sự kiện này cho biết lỗi loại bộ cập nhật trong tệp bản kê được tải xuống. Chúng tôi sử dụng sử dụng này để thông báo cho chủ sở hữu về tệp bản kê để khắc phục lỗi.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdaterType** - Loại bộ cập nhật xác định trong tệp bản kê được tải xuống

- **UpdateURL** - URL của gói cập nhật cần được áp dụng

### <a name="downloadtaskurlerror"></a>downloadtask.urlerror

Sự kiện này cho biết lỗi trong URL xác định trong tệp bản kê được tải xuống. Chúng tôi sử dụng sử dụng này để thông báo cho chủ sở hữu về tệp bản kê để khắc phục lỗi.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **Error** - Chỉ ra bản chất của lỗi gặp phải

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateURL** - URL của gói cập nhật cần được áp dụng

### <a name="fbachangelastupdate"></a>fba.changelastupdate

Sự kiện này cho biết thời điểm Microsoft Auto Update (MAU) kiểm tra cập nhật. Chúng tôi sử dụng sự kiện này để gỡ lỗi khi một thiết bị cụ thể chưa được cập nhật trong một khoảng thời gian kéo dài.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **Payload** - Chứa ngày giờ khi MAU kiểm tra cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbacheckforupdate"></a>fba.checkforupdate

Sự kiện này cho biết quá trình nền đang kiểm tra bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbacheckforupdateskip"></a>fba.checkforupdateskip

Sự kiện này cho biết quá trình nền đã bỏ qua cập nhật vì lý do GUI MAU đang mở. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbaforceinstallmsgsent"></a>fba.forceinstallmsgsent

Sự kiện này cho biết một bản cập nhật bắt buộc được khởi tạo từ giao diện người dùng. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbaforceupdatecheck"></a>fba.forceupdatecheck

Sự kiện này cho biết bắt buộc kiểm tra cập nhật. Chúng tôi sử dụng sự kiện này để xác định số lần kiểm tra cập nhật bắt buộc xảy ra ngoài chu kỳ kiểm tra cập nhật bình thường.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbaguiappopen"></a>fba.guiappopen

Sự kiện này cho biết giao diện người dùng được khởi chạy dưới chế độ Tự động Kiểm tra, vì một ứng dụng với bản cập nhật có thể áp dụng hiện đang mở. Sự kiện này được sử dụng để xác định số lần khởi chạy giao diện người dùng từ chế độ Tự động Kiểm tra để phát triển tính năng trong tương lai.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -  Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbainstallpending"></a>fba.installpending

Sự kiện này cho biết Microsoft Auto Update (MAU) đã gửi một thông báo về các bản cập nhật đang chờ. Sự kiện này được sử dụng để xác định số lượng bản cập nhật được khởi chạy từ thông báo của người dùng và để cải thiện trải nghiệm người dùng bằng cách giảm thiểu sự gián đoạn cho người dùng trong các bản phát hành trong tương lai.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -  Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbalaunch"></a>fba.launch

Sự kiện này cho biết sự bắt đầu của Bộ trợ giúp Microsoft Update với phương pháp được khởi chạy. Sự kiện này được sử dụng để xác định Bộ trợ giúp Microsoft Update có được khởi chạy trong ngữ cảnh không chính xác hay không.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbalaunchbyagent"></a>fba.launchbyagent

Sự kiện này cho biết Bộ trợ giúp Microsoft Update đã khởi chạy qua Tác vụ Khởi chạy. Sự kiện này được sử dụng để xác định số lần Bộ trợ giúp Microsoft Update khởi chạy từ giao diện người dùng để phát triển trong tương lai.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbalaunchfromprotocol"></a>fba.launchfromprotocol

Sự kiện này cho biết Bộ trợ giúp Microsoft Update đã khởi chạy qua giao thức URL. Sự kiện này được sử dụng để xác định số lần Bộ trợ giúp Microsoft Update khởi chạy từ URL để phát triển trong tương lai.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa thông tin về lược đồ URL và Máy chủ URL

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbalaunchgui"></a>fba.launchgui

Sự kiện này cho biết Bộ trợ giúp Microsoft Update đang cố gắng khởi chạy Giao diện Người dùng đồ hoạ (GUI). Sự kiện này được sử dụng để xác định số lần UI khởi chạy từ Bộ trợ giúp Microsoft Update để hỗ trợ cho việc phát triển trong tương lai, bao gồm giảm thiểu sự gián đoán cho người dùng trong việc khởi chạy UI thường xuyên.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbalaunchstatus"></a>fba.launchstatus

Sự kiện này ghi lại các lỗi daemon của MAU trong khi cố gắng khởi chạy. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** – Chứa trạng thái của hệ điều hành (mã trạng thái của Apple) phản ánh trạng thái khởi chạy.

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa trạng thái OS (mã trạng thái của Apple) phản ánh trạng thái khởi chạy. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** – Chuỗi Boolean cho biết liệu quy trình MAU daemon có được khởi chạy thành công hay không.


### <a name="fbamausilentupdate"></a>fba.mausilentupdate

Sự kiện này cho biết Bộ trợ giúp Microsoft Update đang khởi chạy các bản cập nhật tự hành. Sự kiện này được sử dụng để xác định số lượng bản cập nhật được áp dụng mà không có sự can thiệp của người dùng để giúp thúc đẩy cải thiện trải nghiệm người dùng.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa
 
- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh *[Trường này đã bị xóa khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **Lý do** - Văn bản tĩnh cho biết không thể tiếp tục cập nhật im lặng khi giao diện người dùng đang mở

- **SessionId** - Mã định danh của phiên

### <a name="fbamoreinfofromappnotification"></a>fba.moreinfofromappnotification

Sự kiện này cho biết thông tin về một ứng dụng đã đăng ký đang định tuyến qua Microsoft Auto Update (MAU). Ví dụ: thông báo kết thúc dịch vụ được đẩy qua thông báo của MAU. Chúng tôi sử dụng sự kiện này để xác định số lượng thiết bị hiển thị thông báo cụ thể này, nhằm xác định sự thành công của việc phổ biến thông tin.

Các trường sau đây sẽ được thu thập:

- **AdditionalInfoID** - Chỉ ra duy nhất “Xem thêm thông tin” đang được đẩy qua MAU.

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -  Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **NotificationEvent** - Văn bản tĩnh cho biết loại thông báo đang được áp dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbamultipledaemon"></a>fba.multipledaemon

Sự kiện này cho biết đã phát hiện một bản sao khác của Bộ trợ giúp Microsoft Update và bản sao hiện tại sẽ được chấm dứt. Chúng tôi sẽ sử dụng sự kiện này để xác định số lượng thiết bị cố gắng chạy nhiều bản sao Bộ trợ giúp Cập nhật và thiết kế một giải pháp thay thế nếu cần.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbanofifyappclosed"></a>fba.nofifyappclosed

Sự kiện này cho biết Bộ trợ giúp Microsoft Update đang gửi một thông báo về các bản cập nhật đang chờ vì không có ứng dụng đã đăng ký nào đang mở và bản cập nhật có thể tiếp tục mà không làm gián đoạn người dùng. Chúng tôi sử dụng sự kiện này để xác định số lượng bản cập nhật có thể được áp dụng nhưng cần hành động của người dùng để thực hiện. Sự kiện này được sử dụng để giúp thúc đẩy cải thiện trải nghiệm người dùng.

Các lĩnh vực sau đây sẽ được thu thập: 
    
- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
    
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng
    
- **AppVersionLong** - Phiên bản ứng dụng
    
- **Channel** - Tùy chọn dành cho người xem
    
- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)
    
- **DeviceID** - Mã định danh thiết bị
    
- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị
    
- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)
    
- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành
    
- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa
    
- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại
    
- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 
    
- **HowToCheck** - Cách kiểm tra cài đặt
    
- **Payload** -  Văn bản tĩnh
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)
    
- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP
    
- **SessionId** - Mã định danh của phiên

### <a name="fbanofifyappopen"></a>fba.nofifyappopen

Sự kiện này cho biết Bộ trợ giúp Microsoft Update đang gửi một thông báo về các bản cập nhật đang chờ vì ứng dụng đã đăng ký đang mở và bản cập nhật yêu cầu đóng ứng dụng để tiếp tục.  Chúng tôi sử dụng sự kiện này để xác đính số lượng bản cập nhật cần sự can thiệp của người dùng.  Sự kiện này được sử dụng để giúp thúc đẩy cải thiện trải nghiệm người dùng.

Các lĩnh vực sau đây sẽ được thu thập:  

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng
    
- **AppVersionLong** - Phiên bản ứng dụng
    
- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbasettimerfail"></a>fba.settimerfail  

Sự kiện này cho biết nỗ lực thiết lập bộ định giờ để kích hoạt cập nhật trong tương lai không thành công. Sự kiện này rất quan trọng và chúng tôi sử dụng sự kiện này để xác định số lần không thành công để phát triển giải pháp thay thế nếu cần.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Chứa thời gian về lần cập nhật gần nhất và lịch được sử dụng

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateoptin"></a>fba.silentupdateoptin

Sự kiện này cho biết người dùng đang chọn áp dụng các bản cập nhật tự hành. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbaskipforcedupdate"></a>fba.skipforcedupdate

Sự kiện này cho biết quá trình kiểm tra cập nhật bắt buộc bị bỏ qua vì lý do có các ứng dụng đang mở. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbastartforcedupdate"></a>fba.startforcedupdate

Sự kiện này cho biết đã xảy ra một lần thử áp dụng bản cập nhật bắt buộc. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbaterminate"></a>fba.terminate

Sự kiện này cho thấy daemon MAU đã chấm dứt theo cách thông thường. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbaupdatefound"></a>fba.updatefound

Sự kiện này cho thấy daemon MAU đã tìm thấy nhằm đề xuất các bản cập nhật sẵn dùng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa số lượng bản cập nhật sẵn dùng được tìm thấy.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="fbaupdatetimer"></a>fba.updatetimer

Sự kiện này cho thấy quá trình Daemon Microsoft Autoupdate đã bắt đầu hoạt động để kiểm tra cập nhật sau khi ở trạng thái ngủ trong một khoảng thời gian. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa thông tin về thời gian hiện tại.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateallappsclosed"></a>fbasilentupdate.allappsclosed

Sự kiện này sẽ ghi lại liệu đã đóng tất cả các ứng dụng trước khi cài đặt hay chưa. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem
    
- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateapplaunchafterupdate"></a>fbasilentupdate.applaunchafterupdate

Sự kiện này sẽ ghi lại một lần thử khởi chạy lại ứng dụng sau cập nhật tự hành và chế độ cập nhật (sao chép hoặc không). Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** – Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** – Chi tiết về lỗi xảy ra trong quá trình khởi chạy ứng dụng sau khi cập nhật.

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của ứng dụng sẽ khởi chạy. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)
    
- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateapplaunchwileinstalling"></a>fbasilentupdate.applaunchwileinstalling

Chúng tôi đã ghi lại thời điểm ứng dụng khởi chạy trong khi cài đặt bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateappneedtoclose"></a>fbasilentupdate.appneedtoclose

Chúng tôi đã ghi lại thời điểm quá trình cập nhật khởi động và nhận thấy rằng ứng dụng cần cập nhật đã mở. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của bản cập nhật và ID của gói ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateappterminationeventreceived"></a>fbasilentupdate.appterminationeventreceived

Sự kiện này cho thấy Microsoft Autoupdate đã nhận được thông báo từ sự kiện Apple về việc ứng dụng đã chấm dứt. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** – Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** – Chi tiết về lỗi xảy ra trong quá trình chấm dứt ứng dụng.

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và ID của gói ứng dụng. Ngoài ra, cũng có thể chứa một chuỗi lỗi nếu Microsoft Autoupdate xác định ứng dụng vẫn chạy ngay cả khi đã nhận sự kiện chấm dứt. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **UpdateID** – Mã định danh của bản cập nhật ứng dụng.


### <a name="fbasilentupdateclientsession"></a>FBASilentUpdate.ClientSession

Sự kiện này được sử dụng để tính toán số liệu tình trạng cập nhật cho Microsoft Auto Update (MAU). Sự kiện này cho phép chúng tôi xác định phiên cập nhật nào (tải xuống hay cài đặt) mà thiết bị phụ trợ hiện đang xử lý.
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **Payload** – Cho biết phiên cập nhật nào (tải xuống hay cài đặt) mà thiết bị phụ trợ hiện đang xử lý.

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên


### <a name="fbasilentupdatecodesignfailure"></a>fbasilentupdate.codesignfailure

Sự kiện này ghi lại kết quả xác minh chứng thực số sau khi áp dụng bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa kết quả của thao tác xác minh chứng thực số.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdatedownload"></a>fbasilentupdate.download

Sự kiện này cho thấy bản cập nhật đang được tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của bản cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **ScreenLocked** – Cho biết liệu quá trình tải xuống có được bắt đầu sau màn hình bị khóa hay không

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdatedownloadfailed"></a>fbasilentupdate.downloadfailed

Sự kiện này cho biết đã xảy ra lỗi khi tải xuống bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** – Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** – Chi tiết về lỗi xảy ra trong quá trình tải xuống bản cập nhật của ứng dụng.

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của bản cập nhật. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **UpdateID** – Mã định danh của bản cập nhật ứng dụng.

- **UpdateName** – Tên của bản cập nhật ứng dụng.


### <a name="fbasilentupdatedownloadinbackground"></a>fbasilentupdate.downloadinbackground

Sự kiện này cho biết chúng tôi đang bắt đầu tải xuống một tập hợp các bản cập nhật trong nền (chúng tôi sẽ ghi lại số lượng bản cập nhật đang tải xuống đồng thời). Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa số lượng bản cập nhật đang chờ.

    - **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdatedownloadingrepairupdate"></a>fbasilentupdate.downloadingrepairupdate

Sự kiện này cho biết chúng tôi đã bắt đầu một lần thử tải xuống bản sửa lỗi cho bản cập nhật không thành công. Chúng tôi sẽ ghi lại phiên bản và bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của bản cập nhật.
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **ScreenLocked** – Cho biết liệu quá trình tải xuống có được bắt đầu sau màn hình bị khóa hay không

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateduplicatedownloadattempted"></a>fbasilentupdate.duplicatedownloadattempted

Sự kiện này cho biết đã xảy ra lỗi. Chúng tôi chỉ nên tải xuống cùng một lúc một bản cập nhật cho một ứng dụng đã biết. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateinstallattemptfailed"></a>fbasilentupdate.installattemptfailed

Sự kiện này cho biết lần thử cài đặt bản cập nhật (phiên bản) đã không thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateinstallcomplete"></a>fbasilentupdate.installcomplete

Sự kiện này cho biết tất cả các bản cập nhật trong lô đã hoàn tất cài đặt. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateinstalled"></a>fbasilentupdate.installed

Sự kiện này cho biết bản cập nhật riêng lẻ đã được cài đặt thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện. Chứa mã định danh của bản cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="fbasilentupdateinstalling"></a>fbasilentupdate.installing

Sự kiện này cho biết bản cập nhật riêng lẻ đã bắt đầu. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của bản cập nhật và tên của gói cập nhật.
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbasilentupdateinstallstatus"></a>fbasilentupdate.installstatus

Sự kiện này cho biết trạng thái của tác vụ cập nhật ứng dụng. Sự kiện này là một phần của phễu cập nhật ứng dụng và chúng tôi sử dụng sự kiện này để giám sát tình trạng của bản cập nhật ứng dụng.

Các lĩnh vực sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Chứa thông tin hiển thị dạng xem tiến độ

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** -  Cho biết cập nhật ứng dụng có thành công hay không

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

- **UpdatePkg** - Tên của gói cập nhật đang được áp dụng

### <a name="fbasilentupdatenotificationerror"></a>fbasilentupdate.notificationerror

Sự kiện này cho biết lỗi gặp phải khi cố gắng gửi thông báo cho người dùng. Sự kiện này sẽ được sử dụng để gỡ lỗi vì lỗi và thực hiện hành động khắc phục.

Các trường sau đây sẽ được thu thập:  

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
 
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **ErrType** - Chỉ ra bản chất của lỗi gặp phải

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Message** - Nội dung thông báo

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Title** - Tiêu đề thông báo

- **Type** - Loại thông báo

### <a name="fbasilentupdatenotificationremoved"></a>fbasilentupdate.notificationremoved

Sự kiện này cho biết bản cập nhật đã chặn sẽ không còn bị chặn nữa. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng (mã định danh mà ứng dụng dùng để đăng ký dịch vụ Microsoft Autoupdate) của ứng dụng đã chặn trước đó
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdatequeueinstall"></a>fbasilentupdate.queueinstall

Sự kiện này cho biết bản cập nhật sẽ ở trong hàng chờ cài đặt tự hành. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của bản cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdaterequiredappsclosed"></a>fbasilentupdate.requiredappsclosed

Chúng tôi sẽ ghi lại thời điểm ứng dụng có bản cập nhật đang chờ xử lý bị đóng. Thao tác này cho biết thời gian cài đặt thực tế có thể tiến hành. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và ID của gói ứng dụng.
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="fbasilentupdatetimerforapptermination"></a>FBASilentUpdate.TimerForAppTermination

Sự kiện này được sử dụng để tính toán số liệu tình trạng cập nhật cho Microsoft Auto Update (MAU). Sự kiện này cho phép chúng tôi theo dõi sự kiện chấm dứt của ứng dụng đã mở và khoảng thời gian của trạng thái mở.
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **Payload** – Cho biết bộ định giờ có được đặt cho một ứng dụng mở khi trình cài đặt cập nhật của ứng dụng đó được kích hoạt hay không. 

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên

### <a name="fbasilentupdateupdateavailablenotification"></a>fbasilentupdate.updateavailablenotification

Sự kiện này cho thấy đã kích hoạt thông báo có bản cập nhật sẵn dùng. Chúng tôi phải đảm bảo luồng nhắc nhở cập nhật được kích hoạt mỗi khi phát hiện có bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **CustomNotification** – Boolean cho biết liệu thông báo tùy chỉnh đã được sử dụng hay chưa.

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateuserclicknotification"></a>fbasilentupdate.userclicknotification

Sự kiện này cho thấy người dùng đã bấm vào phần nội dung của thông báo có bản cập nhật sẵn dùng và GUI Microsoft Autoupdate đang khởi chạy. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateuserselectinstalllater"></a>fbasilentupdate.userselectinstalllater

Sự kiện này cho thấy người dùng chọn cài đặt sau, sau khi thông báo có bản cập nhật sẵn dùng hiển thị. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="fbasilentupdateuserselectinstallnow"></a>fbasilentupdate.userselectinstallnow

Sự kiện này cho thấy người dùng chọn cài đặt ngay bây giờ sau khi thông báo có bản cập nhật sẵn dùng hiển thị. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="guidashboardviewappisopendialogdisplay"></a>gui.dashboardview.appisopendialog.display 

Sự kiện này cho biết UI đã hiện một hộp thoại đóng ứng dụng mở để tiếp tục cập nhật ứng dụng. Sự kiện được sử dụng để xác định số lượng bản cập nhật bị trì hoãn để cải thiện trong tương lai nhằm giảm thiểu sự gián đoạn của người dùng.

Các lĩnh vực sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

### <a name="guidashboardviewappisopendialogbuttonclicked"></a>gui.dashboardview.appisopendialogbutton.clicked

Sự kiện này cho biết bản cập nhật ứng dụng có bị bỏ qua không, hay một nỗ lực khác đang được thực hiện sau khi hiện hộp thoại ứng dụng mở. Sự kiện này được sử dụng để xác định số lượng bản cập nhật bị bỏ qua để cải thiện trong tương lai nhằm giảm thiểu sự gián đoạn của người dùng.

Các trường sau đây sẽ được thu thập:   

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **ButtonType** - Bỏ qua hay Thử lại

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị 

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

### <a name="guidashboardviewupdateinprogressdialogdisplay"></a>gui.dashboardview.updateinprogressdialog.display

Sự kiện này ghi lại việc một hộp thoại được hiển thị cho người dùng cho biết đang cập nhật.
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên

### <a name="guidashboardviewupdatemodebuttonclicked"></a>gui.dashboardview.updatemodebutton.clicked

Sự kiện này cho biết chế độ cập nhật đã được thay đổi từ Điều khiển UI. Sự kiện này được sử dụng để xác định số lượng thiết bị chuyển tiếp từ chế độ này sang chế độ khác, giúp xác định nguyên nhân khách hàng không muốn cập nhật tự động. 

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
 
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** -  Cho biết tự động tải trọng có bị TẮT hay không

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="guifeedbackwindowbuttonclicked"></a>gui.feedbackwindow.buttonclicked

Sự kiện này cho biết ý kiến phản hồi đã được gửi hay bị hủy trước khi gửi. Sự kiện này được sử dụng để giúp xác định số lượng ý kiến phản hồi được gửi về một phiên bản phát hành cụ thể. Điều này giúp cô lập sớm các sự cố tiềm ẩn.

Các trường sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **ButtonType** - Cho biết ý kiến phản hồi đã được gửi hay bị hủy

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành
 
- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="guipreferenceviewconsentsheetdisplay"></a>gui.preferenceview.consentsheet.display

Sự kiện này cho biết trang tính chấp thuận cho một kênh nhất định được hiển thị, nếu có. Sự kiện này được sử dụng để xác định số lượng thiết bị đăng ký mới vào kênh người xem áp dụng (Người dùng Nội bộ Nhanh / Người dùng Nội bộ Chậm). Chúng tôi cũng sử dụng sự kiện này để đảm bảo hộp thoại chấp thuận đang hoạt động để hiện điều khoản sử dụng cho người dùng.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **ChannelName** - Kênh hiển thị hộp thoại chấp thuận

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="guipreferenceviewconsentsheetlicenseerror"></a>gui.preferenceview.consentsheet.licenseerror

Sự kiện này cho biết lỗi gặp phải khi cố gắng hiện hộp thoại chấp thuận. Sự kiện này rất quan trọng và được sử dụng để khắc phục bất kỳ sự cố nào gây ra do sản phẩm thay đổi, nếu có.

Các trường sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **ErrorCode** - Mã lỗi gặp phải

- **ErrorDomain** - Miền lỗi

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="guipreferenceviewswitchchannel"></a>gui.preferenceview.switchchannel

Sự kiện này cho biết sự chuyển tiếp giữa các kênh đã chọn của người dùng. Sự kiện này được sử dụng để giúp xác định nguyên nhân khách hàng ra khỏi các kênh của Người dùng Nội bộ.  

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PickedFrom** - Kênh cũ

- **PickedTo** - Kênh mới

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="guiupdatemanagerapplaunchduringupdate"></a>gui.updatemanager.applaunchduringupdate

Sự kiện này cho biết một ứng dụng đã khởi chạy trong khi đang được cập nhật và Microsoft AutoUpdate đang chấm dứt ứng dụng đã khởi chạy. Ghi chú rằng khởi chạy một ứng dụng trong khi đang cập nhật có thể dẫn đến ứng dụng bị hỏng. Chúng tôi sử dụng sự kiện này để đảm bảo quy trình cập nhật không bị ứng dụng đã khởi chạy ảnh hưởng trước khi sẵn sàng sử dụng.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng được khởi chạy trong quá trinh cập nhật.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Giá trị chuỗi Boolean cho biết ứng dụng đã được chấm dứt thành công hay chưa.

- **UpdateID** - Mã định danh của bản cập nhật ứng dụng.

### <a name="guiupdatemanagerdownloadupdateforapp"></a>gui.updatemanager.downloadupdateforapp

Sự kiện này cho biết trạng thái hoàn thành tải xuống của một bản cập nhật. Chúng tôi sử dụng sự kiện này để đảm bảo trạng thái của quy trình cập nhật và theo dõi/giải quyết điểm thất bại.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **IsRepair** - Chuỗi Boolean cho biết bản cập nhật cụ thể có phải bản tải xuống sửa chữa không.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **isRepair** - Cho biết bản tải xuống có phải bản tải xuống sửa chữa cho bản cập nhật đã thất bại trước đó hay không.

- **UpdateID** - Mã định danh cập nhật.

- **UpdateName** - Tên bản cập nhật.


### <a name="guiupdatemanagererror"></a>gui.updatemanager.error

Sự kiện này cho biết các lỗi gặp phải trong quá trình cập nhật ứng dụng. Sự kiện này có thể cho biết lỗi trong trình tự thực thi của Microsoft Auto Update (MAU).  Chúng tôi dùng báo cáo này để áp dụng các bản cập nhật cho MAU để hỗ trợ cho các kịch bản lỗi phổ biến.

Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **Payload** – Chứa thông tin về lỗi gặp phải trong quá trình cập nhật ứng dụng.

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên

- **Success** – Giá trị chuỗi Boolean cho biết ứng dụng đã được chấm dứt thành công hay chưa.

### <a name="guiupdatemanagerinstallcleanupforapp"></a>gui.updatemanager.installcleanupforapp

Sự kiện cho biết các tệp tạm thời được tạo trong quá trình cài đặt ứng dụng đã được dọn dẹp thành công. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng.
 
Các trường sau đây sẽ được thu thập:

- **App** – Quy trình ứng dụng để gửi sự kiện

- **AppID** – Mã định danh của ứng dụng.

- **AppInfo_Language** – Ngôn ngữ mà ứng dụng đang sử dụng

- **AppState** – Số nguyên cho biết trạng thái của ứng dụng sau khi cập nhật.

- **AppVersionLong** – Phiên bản ứng dụng

- **Channel** – Tùy chọn dành cho người xem

- **Device_NetworkCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** – Mã định danh của thiết bị

- **DeviceInfo_Model** – Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** – Loại mạng (Wi-Fi, có dây, Không xác định)

- **DeviceInfo_OsBuild** – Phiên bản hệ thống của hệ điều hành

- **Event_ReceivedTime** – Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** – Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** – Thời gian sự kiện được ghi lại xảy ra 

- **HowTocheck** – Tùy chọn kiểm tra cập nhật

- **PipelineInfo_ClientCountry** – Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** – Ba octet đầu tiên của địa chỉ IP

- **SessionId** – Mã định danh của phiên

- **UpdateID** – Mã định danh cập nhật.


### <a name="guiupdatemanagerinstallsuccessforapp"></a>gui.updatemanager.installsuccessforapp

Sự kiện này cho biết ứng dụng được cập nhật thành công. Sự kiện này là một phần của phễu cập nhật mà chúng tôi sử dụng để xác định tình trạng của bản cập nhật.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Chuỗi Boolean cho biết bản cập nhật đã được cài đặt thành công hay chưa.

- **UpdateID** - Mã định danh cập nhật.

### <a name="guiupdatemanagerinstallupdateforapp"></a>gui.updatemanager.installupdateforapp

Sự kiện này cho biết sự bắt đầu của quy trình cài đặt một bản cập nhật ứng dụng. Sự kiện này là một phần của phễu cập nhật ứng dụng mà chúng tôi sử dụng để xác định tình trạng của bản cập nhật.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **UpdateID** - Mã định danh cập nhật.

### <a name="guiupdatemanagerqueueinstallforapp"></a>gui.updatemanager.queueinstallforapp

Sự kiện này cho biết sự bắt đầu của quy trình cài đặt một bản cập nhật ứng dụng. Sự kiện này là một phần của phễu cập nhật ứng dụng mà chúng tôi sử dụng để xác định tình trạng của bản cập nhật.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **UpdateID** - Mã định danh cập nhật.

### <a name="guiupdatemanagerrelaunchapp"></a>gui.updatemanager.relaunchapp

Sự kiện này ghi lại ứng dụng có khởi chạy thành công sau khi cập nhật hay không.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Giá trị chuỗi Boolean cho biết ứng dụng đã được chấm dứt thành công hay chưa.

- **UpdateID** - Mã định danh cập nhật.

- **UpdateName** - Tên bản cập nhật.

### <a name="installdatacheckrunning"></a>installdata.checkrunning

Sự kiện này sẽ ghi lại kết quả kiểm tra giữa các ứng dụng sẽ cài đặt và liệu những lần thử cài đặt có tiến hành dựa trên ứng dụng đang mở hay không. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installdatacleanup"></a>installdata.cleanup

Các tệp gói nên được loại bỏ sau khi cài đặt. Sự kiện này ghi lại các phiên bản mà chúng tôi không thể loại bỏ tệp gói. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của tệp đã tải xuống và chi tiết lỗi.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installedappinvalidbundle"></a>installedapp.invalidbundle

Sự kiện này cho thấy Microsoft Autoupdate không thể truy xuất thông tin về gói của ứng dụng đã đăng ký tại đường dẫn cụ thể. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installedappinvalidpreference"></a>installedapp.invalidpreference

Sự kiện này ghi lại các trường hợp mà trong đó, phần tùy chọn người dùng chứa mục nhập ứng dụng không hợp lệ. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installedappnilbundleid"></a>installedapp.nilbundleid

Sự kiện này ghi lại các trường hợp mà trong đó, ID gói của ứng dụng bị thiếu. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installedappnilbundlename"></a>installedapp.nilbundlename

Sự kiện này ghi lại các trường hợp mà trong đó, tên gói của ứng dụng bị thiếu. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installedappsendcoreappleevent"></a>installedapp.sendcoreappleevent

Sự kiện này cho biết Microsoft Auto Update (MAU) đang gửi một sự kiện của Apple tới một ứng dụng đã đăng ký để chấm dứt ứng dụng nhằm tiếp tục cập nhật ứng dụng đang chờ. Sự kiện này hiện đang được sử dụng để giúp cải thiện trong tương lai nhằm giảm thiểu sự gián đoạn của người dùng trong quá trình cập nhật ứng dụng. 

Các trường sau đây sẽ được thu thập:

- **Acknowledged** - Cho biết ứng dụng chủ đã nhận được sự kiện hay chưa

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppleEventClass** - Cho biết loại sự kiện được gửi/nhận

- **AppleEventID** - Mã định danh duy nhất của sự kiện được gửi/nhận

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa số lần thử lại

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Cho biết ứng dụng chủ đã báo cáo hoạt động thành công hay chưa

- **UpdateID** – Định danh cập nhật.
    
### <a name="installstatuscodesign"></a>installstatus.codesign

Sự kiện này ghi lại trạng thái của nhị phân chứng thực số OS. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
    
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installstatusdaemon"></a>installstatus.daemon

Sự kiện này ghi lại trạng thái của daemon Microsoft AutoUpdate. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **BundleReachable** – Boolean cho biết liệu có sự cố khi đánh giá gói ứng dụng Microsoft AutoUpdate hay không.

- **Kênh** - Sở thích đối với khán giả

- **Codesigned** – Boolean cho biết liệu Trợ lý Cập nhật đã được ký mã chính xác hay chưa.

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **Tồn tại** – Boolean cho biết liệu Trợ lý Cập nhật có tồn tại trên đĩa hay không.

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa chỉ báo cho biết liệu cấu phần Daemon có xuất hiện ở vị trí dự kiến và có được chứng thực số hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installstatushelper"></a>installstatus.helper

Sự kiện này ghi lại trạng thái của công cụ trình trợ giúp Microsoft AutoUpdate. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa chỉ báo cho biết liệu cấu phần PrivilegedHelperTool có xuất hiện ở vị trí dự kiến và có được chứng thực số hay không.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installupdatestaskapplaunched"></a>installupdatestask.applaunched

Sự kiện này cho thấy Microsoft Autoupdate phát hiện ứng dụng khởi chạy một bản cập nhật đã chặn nhưng không thể tìm thấy chương trình cài đặt phù hợp. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của ứng dụng đã khởi chạy.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installupdatestaskapplaunchwithpendingupdate"></a>installupdatestask.applaunchwithpendingupdate

Sự kiện này cho thấy Microsoft Autoupdate phát hiện ứng dụng khởi chạy một ứng dụng có bản cập nhật đang chờ xử lý. Ứng dụng đã khởi chạy sẽ chấm dứt. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installupdatestaskcodesignverificationfail"></a>installupdatestask.codesignverificationfail

Sự kiện này cho biết quá trình xác minh Chứng thực số cho bản cập nhật ứng dụng đã không thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của ứng dụng được cập nhật và mã lỗi.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installupdatestaskcodesignverificationstart"></a>installupdatestask.codesignverificationstart

Sự kiện này cho biết quá trình xác minh Chứng thực số cho bản cập nhật ứng dụng đã bắt đầu. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của ứng dụng được cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installupdatestaskcodesignverificationsuccess"></a>installupdatestask.codesignverificationsuccess

Sự kiện này cho biết quá trình xác minh Chứng thực số cho bản cập nhật ứng dụng đã thành công. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của ứng dụng được cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installupdatestaskfailsilentinstall"></a>installupdatestask.failsilentinstall

Sự kiện này ghi lại lỗi trong khi áp dụng các bản cập nhật tự hành và liệu đây là bản cài đặt sao chép hay bản cài đặt thông thường. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 
    
- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và loại hình cập nhật.
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installupdatestaskmultiplerelocatablepackage"></a>installupdatestask.multiplerelocatablepackage

Sự kiện này cho thấy Microsoft Autoupdate đã tìm thấy nhiều phiên bản của mục nhập ứng dụng dành cho gói cập nhật cụ thể trong tệp kê khai đã tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật và tên của bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="installupdatestaskremoveclone"></a>installupdatestask.removeclone

Sự kiện này cho biết một bản sao đã bị loại bỏ. Chúng tôi sẽ loại bỏ bản sao sau khi quá trình Cài đặt bản sao hoàn thành hoặc khi một quá trình mới bắt đầu, cũng như khi một phiên bản sao chép cũ được tìm thấy trong máy. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của bản cập nhật, tên của gói cập nhật và trạng thái loại bỏ bản sao/ thông tin chi tiết lỗi.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installupdatestaskretryfail"></a>installupdatestask.retryfail

Sự kiện này cho biết đã gặp phải lỗi trong quá trình thử cài đặt lại. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của bản cập nhật và liệu bản cài đặt có nên được thực hiện thông qua Cài đặt bản sao hay không

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

   
### <a name="installupdatestaskretryproxyerror"></a>installupdatestask.retryproxyerror

Sự kiện này ghi lại các lỗi giao tiếp trong quá trình (giao tiếp với công cụ trình trợ giúp MAU). Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của bản cập nhật và thông tin chi tiết về lỗi proxy được báo cáo.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    

### <a name="installupdatestaskretryresponse"></a>installupdatestask.retryresponse

Sự kiện này ghi lại rằng lần thử lại không có tác dụng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của bản cập nhật, phiên bản ứng dụng, tên của gói cập nhật và chỉ báo cho biết liệu Cài đặt bản sao đã bật hay chưa, liệu bản cài đặt có thành công và nếu thất bại, có bất kỳ lỗi nào được báo cáo hay không.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installupdatestaskretrysuccess"></a>installupdatestask.retrysuccess

Sự kiện này ghi lại cài đặt bản cập nhật đã thành công sau khi thử lại. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa một mã định danh dùng để theo dõi hoạt động cập nhật, tên của bản cập nhật, phiên bản ứng dụng, tên của gói cập nhật và chỉ báo cho biết liệu Cài đặt bản sao đã bật hay chưa.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installupdatestasksetreopengui"></a>installupdatestask.setreopengui

Sự kiện này cho thấy liệu tuỳ chọn cài đặt nhằm mở lại GUI sau cài đặt có thành công hay không. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho thấy thao tác thành công.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="installupdatestaskupdatestatus"></a>installupdatestask.updatestatus

Sự kiện này cho biết trạng thái của tác vụ cài đặt. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng.

Các trường sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Cho biết bất kỳ lỗi nào gặp phải trong quy trình cập nhật, nếu có.

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **IOC** - Cho biết tính năng Cài đặt trên Bản sao đã được sử dụng hay chưa

- **Payload** - Văn bản tĩnh cho biết sự bắt đầu của quy trình cài đặt nếu có

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** -  Cho biết quy trình cài đặt đã hoàn thành thành công hay chưa

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

- **UpdatePkg** - Tên của gói cập nhật đang được áp dụng

### <a name="lifecyclecomplimentproclaunch"></a>Lifecycle.complimentproclaunch

Sự kiện này cho biết nỗ lực khởi chạy Microsoft Update Assistant từ Microsoft AutoUpdate hoặc từ Microsoft AutoUpdate từ Microsoft Update Assistant. Sự kiện này được sử dụng để xác định và đảm bảo trạng thái của Microsoft AutoUpdate và Microsoft Update Assistant.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Mọi lỗi được báo cáo trong khi cố gắng khởi chạy chương trình

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **Reason** - Lý do cố gắng khởi chạy quy trình bổ sung

- **SessionId** - Mã định danh của phiên

- **Success** -  Cho biết nỗ lực khởi chạy có thành công hay không

### <a name="lifecyclelaunch"></a>Lifecycle.launch

Sự kiện này cho biết bắt đầu Microsoft AutoUpdate hoặc Microsoft Update Assistant. Sự kiện này cũng được sử dụng để báo cáo mọi sự cố tìm thấy trong quá trình khởi chạy, cũng như làm phương pháp báo cáo dùng để khởi chạy trong trường hợp Microsoft Update Assistant.

*[Sự kiện này thay thế fba.launch và appdelegate.launch events.]*

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Mọi lỗi tìm thấy trong khi khởi chạy

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **LaunchedBy** - Phương pháp dùng để khởi chạy Microsoft Update Assistant nếu có

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="lifecycleperiodiccheck"></a>Lifecycle.periodiccheck

Sự kiện này báo cáo định kỳ về trạng thái của quy trình MicrosoftAutoUpdate. Cụ thể, sự kiện này báo cáo về những tác vụ còn lại mà quy trình đang đợi để hoàn thiện cho Công cụ trợ giúp Cập nhật và trong trường hợp UI, sự kiện này báo cáo về việc quy trình có đang chấm dứt do người dùng không hoạt động hay không.  Chúng tôi sử dụng sự kiện này để xác định yếu tố tác ngăn Công cụ trợ giúp Cập nhật hoàn thành bản cập nhật và đang chấm dứt, đồng thời xác định UI có đang chấm dứt do người dùng không hoạt động hay không.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **dataCollectionDialog** - Boolean xác định quy trình có đang đợi phản hồi của người dùng trên Hộp thoại Kết nối Dữ liệu hay không

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **forcedUpdateDialog** - Boolean xác định quy trình có đang đợi phản hồi của người dùng trên Hộp thoại Cập nhật Bắt buộc hay không

- **HowToCheck** - Cài đặt Cách kiểm tra

- **isBusy** - Boolean xác định quy trình có đang bận với bản cập nhật hiện hoạt hay không

- **isInactive** - Boolean xác định quy trình có đang đợi hành động của người dùng trong thời gian kéo dài hay không

- **isWaiting** - Boolean xác định quy trình có đang đợi phản hồi của người dùng trên thông báo hay không

- **PipelineInfo_ClientCountry** - Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **SessionLength** - Độ dài của phiên quy trình hiện tại theo giây


### <a name="lifecycleterminate"></a>Lifecycle.terminate

Sự kiện này cho biết kết thúc Microsoft AutoUpdate hoặc Microsoft Update Assistant. Sự kiện này được sử dụng để xác định trạng thái của Microsoft AutoUpdate và Microsoft Update Assistant.

*[Sự kiện này thay thế các sự kiện fba.terminate và appdelegate.terminate.]*

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** -   Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **SessionLength** - Độ dài của phiên quy trình hiện tại theo giây



### <a name="msupdateclieventhandler"></a>msupdate.cli.eventhandler

Sự kiện này được sử dụng để tính toán mức sử dụng của các loại Giao diện API Dòng lệnh của Microsoft Auto Update (MAU).

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh của ứng dụng gửi API giao diện dòng lệnh đến MAU.

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **EventType** - Loại sự kiện được ứng dụng gửi đến API giao diện dòng lệnh của MAU.

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="msupdateclieventhandlerapplyupdatesappids"></a>msupdate.cli.eventhandler.applyupdates.appids

Sự kiện này cho thấy lệnh CLI (giao diện dòng máy khách) đã được đưa ra để áp dụng bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa danh sách mã ID các ứng dụng sẽ cập nhật.
    
- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="msupdateclieventhandlerconfig"></a>msupdate.cli.eventhandler.config

Sự kiện này cho thấy mô-đun Giao diện dòng lệnh Microsoft Autoupdate đã nhận được sự kiện Apple để định cấu hình. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="msupdateclieventhandlerupdates"></a>msupdate.cli.eventhandler.updates

Sự kiện này cho thấy mô-đun Giao diện dòng lệnh Microsoft Autoupdate đã nhận được sự kiện Apple để liệt kê các bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="msupdatemonitorprogressdownloaded"></a>msupdate.monitor.progress.downloaded

Sự kiện này cho thấy các bản cập nhật đã được tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa danh sách các bản cập nhật đã tải xuống

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="msupdatemonitorprogressfailure"></a>msupdate.monitor.progress.failure

Sự kiện này ghi lại danh sách các bản cập nhật đang chờ nhưng không thể áp dụng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa danh sách các bản cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="msupdatemonitorprogressfinished"></a>msupdate.monitor.progress.finished

Sự kiện này ghi lại danh sách các bản cập nhật đang chờ và đã hoàn tất cài đặt. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa danh sách các bản cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="msupdatemonitorprogressqueued"></a>msupdate.monitor.progress.queued

Sự kiện này ghi lại danh sách các bản cập nhật đang chờ. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa danh sách các bản cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên


### <a name="optinnotificationaction"></a>Optinnotificationaction

Sự kiện này ghi lại phản hồi của người dùng vào hộp thoại chọn tham gia để đăng ký vào các bản cập nhật tự hành. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa văn bản tĩnh đại diện cho lựa chọn Tự động tải xuống và Cài đặt của người dùng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="sauforcedupdateautodismiss"></a>sauforcedupdate.autodismiss

Sự kiện này cho biết hộp thoại cập nhật được hiển thị đã được bỏ do người dùng không hoạt động. Sự kiện này được sử dụng để xác định số lượng các bản cập nhật bắt buộc được xử lý mà người dùng không cung cấp thông tin đầu vào tới thông báo được hiển thị. Sự kiện này được sử dụng để tăng cường giao diện người dùng để giảm thiểu sự gián đoạn.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị
  
- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** -Ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdateclose"></a>sauforcedupdate.close

Sự kiện này cho biết người dùng đã chọn đóng hộp thoại cập nhật bắt buộc. Sự kiện này được sử dụng để xác định số lượng bản cập nhật bắt buộc bị trì hoãn bởi hành động của người dùng. Sự kiện này được sử dụng để tăng cường giao diện người dùng để giảm thiểu sự gián đoạn. 

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdatecompleteautodismiss"></a>sauforcedupdate.completeautodismiss

Sự kiện cho biết hộp thoại cập nhật bắt buộc đã hiển thị từ tính năng hạn chót đã được bỏ do người dùng không hoạt động. Sự kiện này được sử dụng để xác định số lượng các bản cập nhật bắt buộc được xử lý mà người dùng không cung cấp thông tin đầu vào tới thông báo được hiển thị. Sự kiện này được sử dụng để tăng cường giao diện người dùng để giảm thiểu sự gián đoạn cho tính năng hạn chót.

Các lĩnh vực sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdatecompleteclose"></a>sauforcedupdate.completeclose

Sự kiện này cho biết một bản cập nhật bắt buộc đã hoàn thành thành công. Sự kiện này được sử dụng để giúp xác định tình trạng của tính năng cập nhật bắt buộc. 

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdatedisplay"></a>sauforcedupdate.display

Sự kiện này cho biết một hộp thoại cập nhật bắt buộc đã hiển thị.  Sự kiện này là một phần của phễu cập nhật bắt buộc và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc.

Các trường sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdatedisplayfinalhour"></a>sauforcedupdate.displayfinalhour

Sự kiện này cho biết một hộp thoại báo giờ cuối để cập nhật bắt buộc đã hiển thị. Sự kiện này là một phần của phễu cập nhật bắt buộc và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdatedone"></a>sauforcedupdate.done

Sự kiện này cho biết một bản cập nhật bắt buộc đã hoàn thành thành công. Sự kiện này là một phần của phễu cập nhật bắt buộc và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdateenabled"></a>sauforcedupdate.enabled

Sự kiện này được kích hoạt khi Microsoft Auto Update (MAU) xác định bản cập nhật bắt buộc có thể áp dụng.  Sự kiện này được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc. 

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Enabled** - Cho biết tính năng cập nhật bắt buộc đã bật hay chưa

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **InvalidUpdates** - Số lượng bản cập nhật bắt buộc với phiên bản cập nhật không hợp lệ

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdateforcedupdatedismiss"></a>sauforcedupdate.forcedupdatedismiss

Sự kiện này cho biết hộp thoại báo giờ cuối để cập nhật bắt buộc đã hiển thị đã được bỏ do người dùng không hoạt động. Sự kiện này được sử dụng để xác định số lượng các bản cập nhật bắt buộc được xử lý mà người dùng không cung cấp thông tin đầu vào tới thông báo được hiển thị. Sự kiện này được sử dụng để tăng cường giao diện người dùng để giảm thiểu sự gián đoạn. 

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdateforcequitandupdatenow"></a>sauforcedupdate.forcequitandupdatenow

Sự kiện này cho biết sự bắt đầu của bản cập nhật bắt buộc do người dùng khởi chạy. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên 

### <a name="sauforcedupdateforceterminate"></a>sauforcedupdate.forceterminate

Sự kiện này cho biết sự bắt đầu của bản cập nhật bắt buộc với ứng dụng bị buộc chấm dứt.  Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa số lượng ứng dụng bị chấm dứt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdatequitandupdatenow"></a>sauforcedupdate.quitandupdatenow

Sự kiện này cho biết người dùng đã chọn đóng ứng dụng và áp dụng bản cập nhật. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc. 

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdatesnooze"></a>sauforcedupdate.snooze

Sự kiện này cho biết người dùng đã chọn trì hoãn cập nhật bắt buộc. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdateterminate"></a>sauforcedupdate.terminate

Sự kiện này cho biết sự bắt đầu của bản cập nhật bắt buộc với ứng dụng bị chấm dứt. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa số lượng ứng dụng bị chấm dứt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="sauforcedupdateupdatenow"></a>sauforcedupdate.updatenow

Sự kiện này cho biết người dùng đã chọn cập nhật ứng dụng ngay bây giờ.  Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của tính năng cập nhật bắt buộc.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên


### <a name="sauupdateinfoprovider"></a>sauupdateinfoprovider

Sự kiện này sẽ ghi lại bất cứ khi nào khóa kê khai trong tệp bổ sung bị thiếu. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa chuỗi dùng để tìm kiếm vị trí hoặc kích thước bản cập nhật.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updateapplaunchdetected"></a>update.applaunchdetected

Sự kiện này cho biết một ứng dụng đã được khởi chạy trong khi đang cập nhật. Sự kiện này được sử dụng để xác định số lượng ứng dụng được khởi chạy trong quá trình cập nhật, nhằm tăng cường trải nghiệm người dùng trong các bản phát hành trong tương lai.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Cho biết ứng dụng được khởi chạy đã bị chấm dứt thành công

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

### <a name="updateappterminationreceived"></a>update.appterminationreceived

Sự kiện này cho biết một ứng dụng với cập nhật bị chặn đã bị chấm dứt và Microsoft Auto Update (MAU) có thể tiếp tục cập nhật hay không. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Cho biết có các phiên bản khác của ứng dụng vẫn đang chạy và ngăn chặn MAU tiếp tục hay không

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh cho thấy MAU đang tiếp tục cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

### <a name="updateblockedappclosed"></a>update.blockedappclosed

Sự kiện này cho biết Microsoft Auto Update (MAU) đã phát hiện một ứng dụng với cập nhật bị chặn đã đóng và có thể tiếp tục cập nhật. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời gian nhận được dữ liệu đo từ xa.

- **EventInfo_Name** - Tên của sự kiện đo từ xa được ghi lại.

- **EventInfo_Time** - Thời gian sự kiện được ghi lại xảy ra. 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

### <a name="updateblockedinstallskip"></a>update.blockedinstallskip

Sự kiện này ghi lại lỗi gặp phải khi cố gắng bỏ qua một bản cập nhật ứng dụng. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo.  

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa thông tin về lỗi gặp phải

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updateclientsession"></a>update.clientsession

Sự kiện này được báo cáo khi trạng thái thiết bị của khách hàng thay đổi, khiến Bộ trợ giúp Microsoft Update tạm dừng hoặc tiếp tục quy trình cập nhật. Sự kiện này là một phần của phễu và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Cho biết Microsoft Auto Update (MAU) đang tiếp tục hay tạm dừng

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatedownloadbegin"></a>update.download.begin 

Sự kiện này cho biết sự bắt đầu của quy trình cập nhật ứng dụng. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **IsRepair** - Cho biết bản cập nhật có phải để sửa chữa bản cập nhật không thành công hay không

- **Payload** - Cho biết có bản tải xuống được thử trước đó không

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

### <a name="updatedownloadfinish"></a>update.download.finish

Sự kiện này cho biết giai đoạn tải xuống bản cập nhật ứng dụng đã hoàn thành. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng.  

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **IsRepair** - Cho biết bản cập nhật có phải để sửa chữa bản cập nhật không thành công hay không

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

### <a name="updatedownloadresume"></a>update.downloadresume

Sự kiện này cho biết lỗi gặp phải khi nỗ lực tiếp tục tác vụ tải xuống đã tạm dừng. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **ErrType** - Chỉ ra bản chất của lỗi gặp phải

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

### <a name="updateerror"></a>update.error

Sự kiện này cho biết lỗi gặp phải khi nỗ lực cập nhật ứng dụng đã đăng ký.  Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Chứa thông tin về bản chất của lỗi gặp phải

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa thông tin về bản chất của lỗi gặp phải

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updateinstallcleanupforapp"></a>update.installcleanupforapp

Sự kiện này cho biết đã hoàn thành cài đặt cập nhật và Microsoft Auto Update (MAU) đang dọn dẹp.  Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppState** - Trạng thái của ứng dụng đã đăng ký. Có thể chỉ ra lỗi, tác vụ sửa chữa đang chờ xử lý, v.v.

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

### <a name="updateinstallupdateforapp"></a>update.installupdateforapp

Sự kiện này được sử dụng để báo cáo về việc bắt đầu quy trình cài đặt bản cập nhật ứng dụng. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Lỗi gặp phải nếu có

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

### <a name="updateinstallupdateforappsuccess"></a>update.installupdateforapp.success

Sự kiện này cho biết trạng thái của tác vụ cài đặt. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Cho biết dạng xem tiến độ có được hiển thị trong quy trình cài đặt hay không

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Chỉ báo thành công được trả về từ tác vụ cài đặt

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

### <a name="updateinstallvariance"></a>Update.InstallVariance

Sự kiện này được sử dụng để tính toán số liệu tình trạng cập nhật quan trọng cho MAU. Sự kiện này cho phép chúng tôi xác định số liệu thành công của tính năng ưu tiên cài đặt và xác minh tính toàn vẹn của tính năng.
 
Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa danh sách ID Ứng dụng và thứ tự ưu tiên cài đặt tương ứng được thể hiện bằng số.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatemultipleappupdates"></a>update.multipleappupdates 

Sự kiện này cho biết nhiều bản cập nhật ứng dụng đang chạy trong nền. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị 

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa thông tin về số lượng ứng dụng được cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatepreviousidnil"></a>update.previousidnil

Sự kiện cho biết gói cập nhật sửa chữa đang được tải xuống nhưng không có thông tin tải xuống trước đó. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **ErrType** - Chỉ ra bản chất của lỗi gặp phải

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatequeueinstallforapp"></a>update.queueinstallforapp 

Sự kiện này cho biết một gói cập nhật đã tải xuống đã được đặt trong hàng đợi để cài đặt.  Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh cho biết ứng dụng cần được đóng, nếu có

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

- **UpdateName** - Tên của bản cập nhật khi xuất hiện trong tệp bản kê được tải xuống

### <a name="updaterelaunchafterupdate"></a>update.relaunchafterupdate 

Sự kiện này cho biết ứng dụng đã hoàn tất cập nhật và đang khởi chạy lại. Sự kiện này là một phần của phễu cập nhật và được sử dụng để xác định tình trạng của bản cập nhật ứng dụng. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Chứa thông tin về các lỗi gặp phải khi cố gắng khởi chạy lại ứng dụng

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

- **UpdateID** - Mã định danh cho một bản cập nhật ứng dụng

### <a name="updatetimerforapptermination"></a>update.timerforapptermination 

Sự kiện này cho biết thời gian bắt đầu/kết thúc của bộ định giờ để kiểm tra trạng thái ứng dụng. Sự kiện này đi theo cặp và được sử dụng để xác định tất cả bộ định giờ được loại bỏ khi bản cập nhật ứng dụng tiến hành.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Cho biết bộ định giờ đã được thêm vào hay loại bỏ

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatecoreappregistration"></a>updatecore.appregistration

Sự kiện này sẽ ghi lại các lần thử đăng ký ứng dụng và kết quả/ lý do. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa mã định danh dùng để theo dõi hoạt động cập nhật, cho thấy liệu tuỳ chọn có sẵn dùng không, liệu đây có phải là lần đăng ký lại và liệu có bắt buộc đăng ký hay không.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatecoreloadinglaunchagent"></a>updatecore.loadinglaunchagent

Sự kiện này cho thấy Tác vụ khởi chạy đang được tải. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatecorerunnstaskcommand"></a>updatecore.runnstaskcommand

Sự kiện này báo cáo lỗi trong khi cố gắng khởi chạy một tác vụ. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo.  

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa đường dẫn đến lệnh được thực thi

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatecoreserverconnectionfail"></a>updatecore.server.connectionfail

Sự kiện này ghi lại các lỗi xảy ra trong khi tiếp cận với CDN. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa thông tin về tên máy chủ, liệu máy chủ có hợp lệ và có thể truy nhập hay không.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatecoreservernullurl"></a>updatecore.server.nullurl

Sự kiện này báo cáo lỗi cho biết không thể tiếp cận một máy chủ nhất định. Sự kiện này được sử dụng để xác định tỷ lệ thất bại khi cập nhật do sự cố mạng. 

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatefilterhelpercannotretrievebuilddate"></a>updatefilterhelper.cannotretrievebuilddate

Chúng tôi chỉ có thể lọc các bản cập nhật thông qua Dịch vụ MAU chỉ khi bản cập nhật được cung cấp không cũ hơn số lượng ngày nhất định. Tại đây, chúng tôi sẽ ghi lại là không thể truy xuất ngày tháng từ siêu dữ liệu của ứng dụng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefilterhelperinvalidappid"></a>updatefilterhelper.invalidappid

Sự kiện này báo cáo lỗi cho biết không tìm thấy tệp bản kê với id ứng dụng truy nhập từ phản hồi web. Sự kiện này được sử dụng để điều tra lỗi được báo cáo.

Các lĩnh vực sau đây sẽ được thu thập: 

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa ID ứng dụng trong phản hồi web

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatefilterhelperinvalidappidfromwebservices"></a>updatefilterhelper.invalidappidfromwebservices

Sự kiện này báo cáo lỗi cho biết ID ứng dụng truy nhập từ phản hồi web không ở định dạng mong muốn. Sự kiện này được sử dụng để điều tra lỗi được báo cáo.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Văn bản tĩnh

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatefilterhelperinvalidresponsefromupdatefiltering"></a>updatefilterhelper.invalidresponsefromupdatefiltering

Chúng tôi chỉ có thể lọc các bản cập nhật thông qua Dịch vụ MAU chỉ khi bản cập nhật được cung cấp không cũ hơn số lượng ngày nhất định. Tại đây, chúng tôi sẽ ghi lại ngày tháng bị thiếu trong siêu dữ liệu của ứng dụng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 
    
- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefilterhelpermissingbuilddate"></a>updatefilterhelper.missingbuilddate

Chúng tôi chỉ có thể lọc các bản cập nhật thông qua Dịch vụ MAU chỉ khi bản cập nhật được cung cấp không cũ hơn số lượng ngày nhất định. Tại đây, chúng tôi sẽ ghi lại ngày tháng bị thiếu trong siêu dữ liệu của ứng dụng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefilterhelperupdatebypassedoldage"></a>updatefilterhelper.updatebypassedoldage

Chúng tôi chỉ có thể lọc các bản cập nhật thông qua Dịch vụ MAU chỉ khi bản cập nhật được cung cấp không cũ hơn số lượng ngày nhất định. Tại đây, chúng tôi sẽ ghi lại dịch vụ bị bỏ qua do ngày cập nhật đã cũ. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindercheckerror"></a>updatefinder.check.error

Sự kiện này báo cáo lỗi gặp phải trong khi kiểm tra bản cập nhật. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo. 

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Code** - Mã lỗi 

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Domain** - Miền lỗi

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

 
### <a name="updatefindercheckstart"></a>updatefinder.check.start

Sự kiện này sẽ ghi lại bất cứ khi nào chúng tôi bắt đầu hoạt động kiểm tra bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện
    
- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa thông tin về các bản cập nhật đề xuất, các ứng dụng đã đăng ký và vị trí tạm thời để lưu các tệp tải xuống.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindercheckstatus"></a>updatefinder.check.status

Sự kiện này tổng hợp lại trạng thái của thao tác kiểm tra bản cập nhật (hình phễu từ bước tìm kiếm cho đến tải xuống). Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa thông tin về các bản cập nhật đề xuất, các ứng dụng đã đăng ký và vị trí tạm thời để lưu các tệp tải xuống.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindercheckupdatefound"></a>updatefinder.check.updatefound

Chúng tôi sẽ ghi lại bất cứ khi nào tìm thấy bản cập nhật sau thao tác kiểm tra bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindercheckupdatenotfound"></a>updatefinder.check.updatenotfound

Chúng tôi sẽ ghi lại bất cứ khi nào không tìm thấy bản cập nhật nào để đề xuất sau thao tác kiểm tra bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindercheckuptodate"></a>updatefinder.check.uptodate

Chúng tôi sẽ ghi lại bất cứ khi nào không tìm thấy bản cập nhật nào để đề xuất do tất cả các ứng dụng đều đã cập nhật, sau thao tác kiểm tra bản cập nhật. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefinderofferupdatesinvalidappid"></a>updatefinder.offerupdates.invalidappid

Sự kiện này báo cáo lỗi trong khi cố gắng đánh giá một bản cập nhật có áp dụng được hay không. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo.  

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **CatalogID** - Mã định danh cho danh mục đã truy nhập

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **IsNullID** - Cho biết ID là null hay không

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatefinderofferupdatesminoscheckfail"></a>updatefinder.offerupdates.minoscheckfail

Chúng tôi sẽ ghi lại bất cứ khi nào chúng tôi chặn bản cập nhật do không đạt các yêu cầu OS. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa phiên bản OS tối thiểu bắt buộc dựa trên cụ thể như trong tệp kê khai đã tải xuống.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatefinderofferupdatesmissingtrigger"></a>updatefinder.offerupdates.missingtrigger

Sự kiện này báo cáo lỗi trong khi cố gắng đánh giá yếu tố kích hoạt từ bản kê cập nhật ứng dụng đã tải xuống. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo.  

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **TriggerKey** - Khóa kích hoạt được tìm thấy trong bản kê

- **Triggers** - Từ điển yếu tố kích hoạt được tìm thấy trong bản kê

### <a name="updatefinderofferupdatesnullbundleforappid"></a>updatefinder.offerupdates.nullbundleforappid

Sự kiện này cho thấy Microsoft Autoupdate không thể tải thông tin gói của ID ứng dụng cụ thể như trong tệp kê khai đã tải xuống. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefinderofferupdatesupdaterulematched"></a>updatefinder.offerupdates.updaterulematched

Sự kiện này cho biết đã tìm thấy bản cập nhật cho một ứng dụng và đường cơ sở. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng và thông tin về phiên bản của gói.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="updatefinderregisteredapps"></a>updatefinder.registeredapps

Chúng tôi sẽ ghi lại các ứng dụng được MAU cài đặt/ đăng ký/ kiểm soát. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID ứng dụng và thông tin về phiên bản của gói.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatefindersuiteinvalidsuiteversion"></a>updatefinder.suite.invalidsuiteversion

Sự kiện này báo cáo lỗi phiên bản bộ trong khi đánh giá một bản cập nhật có áp dụng được hay không. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Suite** - Tên của bộ đang được xem xét

### <a name="updatefindersuitekeyvaluemissing"></a>updatefinder.suite.keyvaluemissing

Sự kiện này báo cáo lỗi trong khi cố gắng thêm một ứng dụng vào bộ. Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên 

- **Suite** - Tên của ứng dụng bộ được thêm vào

    
### <a name="updatefindersuitemissingcollateral"></a>updatefinder.suite.missingcollateral

Cập nhật theo bộ - Chúng tôi sẽ ghi lại bất cứ khi nào không thể áp dụng bản cập nhật theo bộ do thiếu tệp bổ sung. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Văn bản cho biết bản chất của sự kiện.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindersuitestaleversion"></a>updatefinder.suite.staleversion

Cập nhật theo bộ - Chúng tôi sẽ ghi lại bất cứ khi nào không thể áp dụng bản cập nhật theo bộ do phiên bản cơ sở đã quá lạc hậu. Chúng tôi sẽ ghi lại phiên bản cơ sở và ID ứng dụng Suite. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của bộ sản phẩm.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindersuiteupdateapplicable"></a>updatefinder.suite.updateapplicable

Cập nhật theo bộ - Chúng tôi sẽ ghi lại bất cứ khi nào có thể áp dụng bản cập nhật theo bộ. Chúng tôi sẽ ghi lại phiên bản cơ sở và ID ứng dụng Suite. Chúng tôi sẽ ghi lại phiên bản cơ sở và ID ứng dụng Suite. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên, đường cơ sở và phiên bản phiên bản của bộ sản phẩm.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindersuiteupdatenotapplicabledefaultpath"></a>updatefinder.suite.updatenotapplicabledefaultpath

Cập nhật theo bộ - Chúng tôi sẽ ghi lại bất cứ khi nào không đề xuất cập nhật theo bộ do tất cả các ứng dụng theo bộ đều được cài đặt bằng đường dẫn mặc định. Chúng tôi sẽ ghi lại phiên bản cơ sở và ID ứng dụng Suite. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên, đường cơ sở và phiên bản phiên bản của bộ sản phẩm.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="updatefindersuiteupdatenotapplicableversion"></a>updatefinder.suite.updatenotapplicableversion

Cập nhật theo bộ - Chúng tôi sẽ ghi lại bất cứ khi nào không đề xuất cập nhật theo bộ do tất cả các ứng dụng theo bộ đều có cùng phiên bản đường cơ sở. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên, đường cơ sở và phiên bản phiên bản của bộ sản phẩm.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindersuiteupdatenotoffered"></a>updatefinder.suite.updatenotoffered

Cập nhật theo bộ - Chúng tôi sẽ ghi lại bất cứ khi nào không đề xuất cập nhật theo bộ do kích thước của bộ lớn hơn các bản cập nhật riêng lẻ. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên của bộ sản phẩm.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatefindersuiteupdateoffered"></a>updatefinder.suite.updateoffered

Cập nhật theo bộ - Chúng tôi sẽ ghi lại bất cứ khi nào có đề xuất bản cập nhật theo bộ. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa tên, đường cơ sở và phiên bản phiên bản của bộ sản phẩm.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="updatemanagercheckupdate"></a>updatemanager.checkupdate

Sự kiện này ghi lại số lượng bản cập nhật do Microsoft Autoupdate tìm thấy trong khi kiểm tra bản cập nhật sẵn dùng. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa số lượng bản cập nhật sẵn dùng được tìm thấy.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="updatemanagerupdatespending"></a>updatemanager.updatespending

Sự kiện này cho biết đã tìm thấy các bản cập nhật và đang chờ để cài đặt. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa chỉ báo cho biết liệu tác vụ có đang chạy trên luồng chính hay không và số lượng bản cập nhật đang chờ xử lý.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="updatestatuscodesign"></a>UpdateStatus.Codesign

Sự kiện này báo cáo trạng thái từ xác minh chứng thực số mà Bộ trợ giúp Microsoft Update chạy sau khi cài đặt cản cập nhật ứng dụng máy khách. Chúng tôi sử dụng sự kiện này để đảm bảo cung cấp các gói hợp lệ và sẽ cập nhật ứng dụng đã cài đặt lên phiên bản mới nhất.

Các lĩnh vực sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppID** - Mã định danh cho ứng dụng đang được cập nhật

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Error** - Các lỗi thấy được trong quy trình xác minh chứng thực số

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh cho phiên

- **Success** - Cho biết xác minh chứng thực số có thành công hay không

- **UpdateID** - Chỉ ra duy nhất bản cập nhật được áp dụng 

- **UpdateName** - Tên của bản cập nhật được mô tả trong bản kê cập nhật

- **UpdatePkg** - Tên của gói cập nhật được áp dụng

### <a name="urlutilitiesgetmauinfo"></a>urlutilities.getmauinfo

Sự kiện này báo cáo lỗi gặp phải trong khi truy nhập gói ứng dụng Microsoft Auto Update (MAU). Sự kiện này rất quan trọng và được sử dụng để điều tra lỗi được báo cáo.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa thông tin về lỗi gặp phải

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên
   
### <a name="webservicescheckforsilentupdates"></a>webservices.checkforsilentupdates

Sự kiện này cho biết đã tìm thấy các đề xuất bản cập nhật tự hành này. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa số lượng các bản cập nhật được tìm thấy và ID ứng dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="webservicesdeltaupdater"></a>webservices.deltaupdater

Sự kiện này ghi lại các tương tác giữa mã máy khách và cổng tính năng có nhiệm vụ kiểm soát xem máy khách có nên cho phép cập nhật Delta hay không. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa phản hồi từ loại dịch vụ web và trình cập nhật để áp dụng.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="webservicesserviceaction"></a>webservices.serviceaction

Chúng tôi sẽ ghi lại bất kỳ lỗi nào do phản hồi dịch vụ web không mong muốn. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa thông tin chi tiết của hành động được đẩy từ dịch vụ web.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên


### <a name="webservicesserviceresponse"></a>webservices.serviceresponse

Sự kiện này ghi lại các yêu cầu đối với Dịch vụ MAU, thời gian phản hồi cũng như các lỗi. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID của yêu cầu, tên ứng dụng, thời gian phản hồi và/ hoặc mã trạng thái.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

    
### <a name="webservicessilentupdate"></a>webservices.silentupdate

Chúng tôi sẽ ghi lại các yêu cầu kiểm tra bất kỳ quy tắc áp dụng "cập nhật bắt buộc” nào, nghĩa là chúng tôi phải đưa người dùng đi từ bản dựng N sang bản dựng N + 1 do một số vấn đề lớn. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID của yêu cầu, tên ứng dụng, thời gian phản hồi và/ hoặc mã trạng thái.

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="webservicesupdatefiltering"></a>webservices.updatefiltering

Sự kiện này cho biết tính năng lọc đã được thực hiện trên danh sách bản cập nhật có thể áp dụng thông qua dịch vụ web. Chúng tôi sử dụng sự kiện này để đảm bảo tính năng chặn ứng dụng đang hoạt động chính xác nếu chúng tôi phải chặn một bản cập nhật.

Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, có dây, không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowToCheck** - Cách kiểm tra cài đặt

- **Payload** - Chứa thông tin về số lượng bản cập nhật bị chặn thông qua dịch vụ web

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - ba octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="webserviceswebcontent"></a>webservices.webcontent

Chúng tôi sẽ ghi lại các yêu cầu và phản hồi nhận được vào dịch vụ web. Chúng tôi dùng sự kiện này để đảm bảo quy trình cập nhật hoạt động như dự kiến cũng như trợ giúp khắc phục sự cố lỗi.
 
Các trường sau đây sẽ được thu thập:

- **App** - Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** - Loại ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** - Phiên bản ứng dụng

- **Channel** - Tùy chọn dành cho người xem

- **Device_NetworkCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **DeviceID** - Mã định danh thiết bị

- **DeviceInfo_Model** - Kiểu phần cứng của thiết bị

- **DeviceInfo_NetworkType** - Loại mạng (Wi-Fi, Có dây, Không xác định)

- **DeviceInfo_OsBuild** - Phiên bản của hệ điều hành

- **Event_ReceivedTime** - Thời điểm nhận được dữ liệu đo từ xa

- **EventInfo_Name** - Tên của sự kiện đo từ xa đang được ghi lại

- **EventInfo_Time** - Thời điểm ghi lại sự kiện 

- **HowTocheck** - Tùy chọn kiểm tra bản cập nhật

- **Payload** - Chứa ID người gọi dịch vụ web

- **PipelineInfo_ClientCountry** - Thiết bị thuộc quốc gia nào (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** - 3 octet đầu tiên của địa chỉ IP

- **SessionId** - Mã định danh của phiên

### <a name="webserviceswhatsnew"></a>webservices.whatsnew

Sự kiện này được kích hoạt khi Microsoft Auto Update (MAU) truy vấn dịch vụ web về tính năng “có gì mới” của các ứng dụng đã đăng ký. Sự kiện này được sử dụng để xác định tình trạng của tính năng “có gì mới”. 

Các trường sau đây sẽ được thu thập:

- **App** -Quy trình ứng dụng sử dụng để gửi sự kiện

- **AppInfo_Language** -Ngôn ngữ mà ứng dụng đang sử dụng

- **AppVersionLong** -Phiên bản ứng dụng

- **Channel** -Tùy chọn dành cho người xem

- **Device_NetworkCountry** -Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **DeviceID** -Mã định danh của thiết bị

- **DeviceInfo_Model** -Mô hình phần cứng của thiết bị

- **DeviceInfo_NetworkType** -Loại mạng (Wi-Fi, Có dây, không xác định)

- **DeviceInfo_OsBuild** -Phiên bản của hệ điều hành

- **Event_ReceivedTime** -Thời gian nhận được dữ liệu đo từ xa

- **EventInfo_Name** -Tên của sự kiện đo từ xa được ghi lại

- **EventInfo_Time** -Thời gian sự kiện được ghi lại xảy ra 

- **HowToCheck** -Cách kiểm tra cài đặt

- **Payload** -Chứa thông tin về số lượng ứng dụng được cập nhật

- **PipelineInfo_ClientCountry** -Quốc gia của thiết bị (dựa trên địa chỉ IP)

- **PipelineInfo_ClientIp** -Ba octet đầu tiên của địa chỉ IP

- **SessionId** -Mã định danh của phiên

## <a name="onenote-sync-events"></a>Sự kiện đồng bộ OneNote

### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Sự kiện này ghi lại kết quả đồng bộ sổ tay. Kết quả này dùng để tìm hiểu xem có bao nhiêu mục tiêu đồng bộ duy nhất khi tính điểm đồng bộ OneNote.
 
Các trường sau đây sẽ được thu thập

- **CachedError_Code** - một mã đánh số hoặc chữ số dùng để xác định bản chất của lỗi lưu bộ đệm ẩn và/ hoặc lý do lỗi xảy ra

- **CachedError_Description** – mô tả lỗi lưu bộ đệm ẩn

- **CachedError_Tag** – chỉ ra vị trị đưa ra lỗi lưu bộ đệm ẩn trong mã

- **CachedError_Type** – loại lỗi lưu bộ đệm ẩn, ví dụ: Win32Error, v.v.

- **ExecutionTime** – thời gian tính bằng mili giây để sao chép sổ tay

- **Gosid** – ID không gian đối tượng toàn cầu

- **IdentityType** – kiểu danh tính, ví dụ: Windows Live, ID tổ chức, v.v.

- **InitialReplicationInSession** – bản sao nhân bản này có phải là bản sao nhân bản sổ tay đầu tiên sau khi mở hay không

- **IsBackgroundSync** – đây có phải là đồng bộ nền hay không

- **IsCachedErrorSuppressed** - lỗi lưu bộ đệm ẩn có bị chặn hay không

- **IsCachedErrorUnexpected** – lỗi lưu bộ đệm ẩn có phải là lỗi không mong muốn hay không

- **IsNotebookErrorSuppressed** - lỗi đồng bộ cấp độ sổ tay có bị chặn hay không

- **IsNotebookErrorUnexpected** - lỗi đồng bộ cấp độ sổ tay có phải là lỗi không mong muốn hay không

- **IsSectionErrorSuppressed** - lỗi đồng bộ mục có bị chặn hay không

- **IsSectionErrorUnexpected** - lỗi đồng bộ mục có phải là lỗi không mong muốn hay không

- **IsUsingRealtimeSync** - thao tác đồng bộ hóa sổ tay có dùng đồng bộ nội dung trang hiện đại hay không

- **LastAttemptedSync** - dấu thời gian của thời điểm sổ tay thử đồng bộ lần cuối

- **LastBackgroundSync** - dấu thời gian của thời điểm thử đồng bộ nền gần nhất

- **LastNotebookViewedDate** - ngày xem sổ tay được gần nhất

- **LastSuccessfulSync** - dấu thời gian của thời điểm sổ tay được đồng bộ thành công trước đây

- **NeedToRestartBecauseOfInconsistencies** - thao tác đồng bộ có cần khởi động lại vì lý do không đồng nhất hay không

- **NotebookErrorCode** - mã lỗi đồng bộ hóa cấp độ sổ tay được lưu trên không gian biểu đồ sổ tay

- **NotebookId** – ID sổ tay

- **NotebookType** - loại sổ tay

- **ReplicatingAgainBecauseOfInconsistencies** - thao tác đồng bộ có khởi động lại vì lý do không đồng nhất hay không

- **SectionError_Code** - một mã đánh số hoặc chữ số dùng để xác định bản chất của lỗi đồng bộ mục và/ hoặc lý do lỗi xảy ra

- **SectionError_Description** - mô tả về lỗi đồng bộ mục

- **SectionError_Tag** - chỉ ra vị trí đưa ra lỗi đồng bộ mục trong mã

- **SectionError_Type** – loại lỗi đồng bộ mục, ví dụ: Win32Error, v.v.

- **Success** - thao tác đồng bộ sổ tay có thành công hay không

- **SyncDestinationType** – loại điểm đến của đồng bộ hóa, nghĩa là OneDrive hoặc SharePoint Online

- **SyncId** - một con số duy nhất cho mỗi đồng bộ sổ tay

- **SyncWasFirstInSession** – đây có phải là lần đồng bộ đầu tiên trong phiên hiện tại hay không

- **SyncWasUserInitiated** – đồng bộ này có phải được người dùng khởi tạo hay không

- **TenantId** – ID đối tượng thuê SharePoint

- **TimeSinceLastAttemptedSync** - thời gian kể từ lần thử đồng bộ sổ tay cuối cùng

- **TimeSinceLastSuccessfulSync** - thời gian kể từ lần đồng bộ sổ tay thành công cuối cùng

### <a name="officeonenotestoragerealtimewebsocketsessioninfo"></a>Office.OneNote.Storage.RealTime.WebSocketSessionInfo
 
Sự kiện này ghi lại kết quả đồng bộ hóa WebSocket cho cả đồng bộ hóa nội dung trang hiện đại và đồng bộ hóa phân cấp hiện đại của OneNote. Kết quả này dùng để tìm hiểu xem có bao nhiêu mục tiêu đồng bộ duy nhất khi tính điểm đồng bộ OneNote. Kết quả này cũng dùng cho bảng điều khiển hiệu suất đồng bộ hiện đại của OneNote.
 
Các trường sau đây sẽ được thu thập:
 
- **CloseReason** - lý do đóng WebSocket, ví dụ: Đóng bất thường, v.v.

- **DataIsFreshCount** - số lượng yêu cầu kéo thành công trong phiên WebSocket

- **DeviceSessionId** - ID phiên của thiết bị

- **DownloadCount** - số lượt tải xuống trong phiên WebSocket

- **Error** - là Exception_Type + Exception_Description + Exception_Code + Exception_Tag cơ bản

- **Exception_Code** - một mã đánh số hoặc chữ số dùng để xác định bản chất của lỗi và/ hoặc lý do lỗi xảy ra

- **Exception_Description** - mô tả về lỗi

- **Exception_Tag** - cho biết vị trí đưa ra lỗi trong mã

- **Exception_Type** - kiểu lỗi, ví dụ: Win32Error, v.v.

- **FirstUpdateSize** - độ dài của thông báo cập nhật đầu tiên

- **HasError** - có lỗi nào trong phiên WebSocket hay không 

- **IsEducationNotebook** - Sổ tay hiện tại có phải sổ tay giáo dục hay không

- **IsHierarchyResource** - Tài nguyên hiện tại là một trang hay một mục

- **NotebookId** - ID sổ tay OneNote

- **OperationWithError** - lỗi đã xảy ra trong thao tác nào, ví dụ: WebSocket.Close, WebSocket.Open, v.v.

- **ResourceId** - trang hoặc ID mục tài nguyên OneNote

- **SectionId** - ID mục OneNote

- **ServerSessionId** - ID phiên dùng để liên kết yêu cầu WebSocket đến onenote.com

- **SessionDurationInMs** - khoảng thời gian tính bằng mili giây của phiên WebSocket

- **TenantId** - ID đối tượng thuê SharePoint

- **TimeToFirstUpdateInMs** - thời gian tính bằng mili giây để nhận bản cập nhật đầu tiên từ phía máy chủ sau khi thiết lập phiên WebSocket

- **UploadAckCount** - số lượng xác nhận tải lên trong phiên WebSocket

- **WebUrl** - PII huỷ bỏ URL web 

### <a name="officeonenotestoragesectionsyncresult"></a>Office.OneNote.Storage.SectionSyncResult
 
Sự kiện này ghi lại kết quả đồng bộ mục. Kết quả này dùng để tìm hiểu xem có bao nhiêu mục tiêu đồng bộ duy nhất khi tính điểm đồng bộ OneNote. Kết quả này cũng dùng cho bảng điều khiển hiệu suất đồng bộ hiện đại của OneNote.
 
Các trường sau đây sẽ được thu thập

- **Error_Code** - một mã đánh số hoặc chữ số dùng để xác định bản chất của lỗi và/ hoặc lý do lỗi xảy ra

- **Error_Description** - mô tả về lỗi

- **Error_Tag** - cho biết vị trí đưa ra lỗi trong mã

- **Error_Type** - kiểu lỗi, ví dụ: Win32Error, v.v.

- **ErrorLast** - mã lỗi của lỗi được phát hiện gần nhất 

- **ExecutionTime** - thời gian tính bằng mili giây để sao chép mục

- **InitialReplicationInSession** - bản sao nhân bản này có phải là bản sao nhân bản sổ tay đầu tiên sau khi mở hay không

- **IsAttachedViaShortcut** - mục có được đính kèm thông qua phím tắt hay không

- **IsBackgroundSync** - đây có phải là đồng bộ nền hay không

- **IsEncrypted** - mục có được mã hóa hay không

- **IsErrorSuppressed** - lỗi có bị chặn hay không 

- **IsErrorTransient** - lỗi này có phải là lỗi nhất thời hay không

- **IsErrorUnexpected** - lỗi này có phải là lỗi không mong muốn hay không

- **IsUsingRealtimeSync** - thao tác đồng bộ mục có dùng đồng bộ nội dung trang hiện đại hay không

- **NotebookId** - ID sổ tay

- **NotebookPath** - PII huỷ bỏ URL sổ tay

- **SectionPath** - PII huỷ bỏ URL mục

- **SectionReplicatingIsOutbound** - bản sao nhân bản này có phải là bản sao nhân bên ngoài hay không

- **SectionReplicatingIsSameIdentity** - bản sao nhân bản này có dựa trên cùng một danh tính tệp hay không

- **SectionResourceId** - ID mục tài nguyên OneNote

- **Success** - thao tác đồng bộ hóa mục có thành công hay không

- **SyncDestinationType** - loại điểm đến của đồng bộ hóa, nghĩa là OneDrive hoặc SharePoint Online

- **SyncId** - một con số duy nhất cho mỗi đồng bộ mục

- **SyncWasFirstInSession** - đây có phải là lần đồng bộ đầu tiên trong phiên hiện tại hay không

- **SyncWasUserInitiated** - đồng bộ này có phải được người dùng khởi tạo hay không

- **TenantId** - ID đối tượng thuê SharePoint

- **UnmappedGosid** - ID mục trước khi áp dụng GUID ánh xạ


### <a name="officeonenotestoragesyncscore"></a>Office.OneNote.Storage.SyncScore
 
Sự kiện này ghi lại tất cả các yếu tố tiêu cực trong trải nghiệm đồng bộ sẽ hiển thị với người dùng. Sự kiện này được dùng để tính điểm đồng bộ OneNote, đây là một số liệu quan trọng để đánh giá trải nghiệm đồng bộ hóa của người dùng OneNote.
 
Các trường sau đây sẽ được thu thập

- **AutoShowSyncStatus** - trạng thái đồng bộ hóa có tự động hiển thị hay không

- **Cause** - nguyên nhân khiến cho các trang/ mục của OneNote chuyển đến các mục sai vị trí

- **Context** - bộ đếm phân loại những việc người dùng đang tìm cách thực hiện, ví dụ: đổi tên mục, mở lại sổ tay, v.v.

- **Error_Code** - một mã đánh số hoặc chữ số dùng để xác định bản chất của lỗi và/ hoặc lý do lỗi xảy ra

- **Error_Description** - mô tả về lỗi

- **Error_Tag** - cho biết vị trí đưa ra lỗi trong mã

- **Error_Type** - kiểu lỗi, ví dụ: Win32Error, v.v.

- **ErrorText** - lỗi hiển thị văn bản lỗi trong giao diện người dùng (UI)

- **Explanation** - giải thích loại thay đổi bên ngoài đang chờ xử lý nào cần được chuyển đến các mục sai vị trí

- **fishbowlType** - loại bể cá, ví dụ: trang bể cá, mục bể cá, v.v.

- **IDS** - mã định danh dạng nguyên cho văn bản hiển thị trong giao diện người dùng (UI)

- **idsFishbowl** - mã định danh dạng nguyên cho lỗi bể cá hiển thị trong giao diện người dùng (UI)

- **IsUsingRealtimeHierarchySync** - có đang sử dụng đồng bộ phân cấp hiện đại hay không

- **NotebookId** - Mã ID sổ tay

- **PageSyncUIState** - chuỗi trạng thái đồng bộ hoá trang, ví dụ: UpToDate, Syncing, SaveOffline, SyncError, v.v. 

- **ServerGosid** - Mã ID tài nguyên cho trang xung đột mới tạo

- **Source** - bộ đếm chỉ ra sự kiện nào kích hoạt giao diện người dùng (UI), nghĩa là tạo ra hình ảnh redx mới, đồng bộ lỗi trong giao diện đồng bộ, hiển thị hộp thoại lỗi, v.v.

### <a name="onenoteappprovisioningmovelocalnotebooktoonlinenotebookfailed"></a>OneNote.App.Provisioning.MoveLocalNotebookToOnlineNotebookFailed
 
Sự kiện này được ghi nhật ký khi di chuyển sổ tay cục bộ vào ổ đĩa không thành công.  Kịch bản này dành riêng cho người dùng đăng nhập trễ. Khi người dùng đăng nhập, sổ tay cục bộ của họ sẽ được chuyển vào dung lượng lưu trữ OneDrive của họ. 
 
Các trường sau đây sẽ được thu thập:
 
- **ErrorMsg** - Thông báo lỗi tương ứng với sự thất bại.

### <a name="onenotestorageconnectivitychanged"></a>OneNote.Storage.ConnectivityChanged

Sự kiện ghi nhận nếu người dùng có khả năng kết nối Internet hay không. Thao tác này được sử dụng để tương quan với sự đồng bộ hóa số liệu hiệu suất sức khỏe khác bằng cách cho phép chúng tôi bỏ qua các sự kiện xảy ra trong khi người dùng không có kết nối Internet vì chúng tôi không mong đợi độ trễ dịch vụ của chúng tôi để có thể chấp nhận được mà không cần kết nối Internet. Điều này cho phép chúng tôi tính toán số phiên chính xác cho các chỉ số về khách hàng (theo đối tượng thuê, theo mỗi ngành). Chúng tôi cũng sử dụng nó để lọc báo cáo bị lỗi vì có rất nhiều lỗi đồng bộ mà chúng tôi hy vọng sẽ xảy ra khi mà không có kết nối mạng thì việc điều tra vẫn có thể diễn ra. 

Nếu chúng tôi không nhận được dữ liệu này, chúng tôi sẽ không thể theo dõi chính xác hiệu suất sản phẩm của chúng tôi hoặc xác định xem lỗi mà người dùng gặp phải có nên được điều tra thêm hay không.

Các lĩnh vực sau đây sẽ được thu thập:

- **InternetConnectivityNowAvailable** -  Nếu trạng thái kết nối đã được thay đổi nên bây giờ nó là Internet

### <a name="onenotestoragelegacyinboundlatency"></a>OneNote.Storage.LegacyInboundLatency

Các tín hiệu quan trọng được sử dụng để theo dõi hiệu suất của các hoạt động đồng bộ hóa trong nước liên lạc trực tiếp với SharePoint bao gồm thông tin có liên quan cho phép chúng tôi giám sát và điều tra hiệu suất của việc tải dữ liệu lên dịch vụ của chúng tôi. Tín hiệu này chỉ được thu thập đối với các bản tải xuống hoạt động kém nhất trong 300 giây cuối (số giây đều được đặt cấu hình bởi Microsoft dựa theo hiệu suất và điều kiện dịch vụ).

Điều này được sử dụng để đảm bảo tình trạng của dịch vụ bằng cách cho phép chúng tôi xem những người thuê nào đang gặp phải tình trạng dữ liệu gửi đến dịch vụ của chúng tôi chậm đến mức không thể chấp nhận được, thông tin về dữ liệu họ đang tải lên khi họ gặp phải vấn đề về độ trễ đó và độ phổ biến về sự chậm trễ này đối với đối tượng thuê. Nó cũng được sử dụng để báo cáo tình trạng dịch vụ và hiệu suất cho các khách hàng của chúng tôi để đo lường xu hướng theo thời gian và tự động cảnh báo về các vấn đề nhằm giảm thiểu kỹ thuật. Nếu chúng tôi không có dữ liệu này, nó sẽ ngăn chúng tôi đảm bảo hiệu suất đầy đủ khi người dùng đồng bộ hóa các thay đổi từ SharePoint với máy tính của họ.

Các lĩnh vực sau đây sẽ được thu thập: 

- **IsEducationNotebook** - Một bool cho biết sổ ghi chép có phải là sổ ghi chép giáo dục hay không

- **NotebookId** - ID của sổ ghi chép mà tải lên này là một phần của

- **TimeToConfirmSyncedWithServerInMs** - Thời gian tính bằng mili giây để thực hiện tải lên

### <a name="onenotestoragelegacyoutboundlatency"></a>OneNote.Storage.LegacyOutboundLatency

Tín hiệu quan trọng được sử dụng để theo dõi hiệu suất của các hoạt động đồng bộ hóa gửi đi mà giao tiếp trực tiếp với SharePoint bao gồm thông tin tương quan cho phép chúng tôi theo dõi và điều tra hiệu suất của việc tải dữ liệu lên dịch vụ của mình. Tín hiệu này chỉ được thu thập đối với các bản tải xuống hoạt động kém nhất trong 300 giây cuối (số giây đều được đặt cấu hình bởi Microsoft dựa theo hiệu suất và điều kiện dịch vụ).

Điều này được sử dụng để đảm bảo sức khỏe của dịch vụ bằng cách cho phép chúng tôi xem những người thuê nào đang gặp phải tình trạng dữ liệu gửi đến dịch vụ của chúng tôi chậm đến mức không thể chấp nhận được, thông tin về dữ liệu mà họ đã tải lên khi họ gặp phải sự cố đi chậm và mức độ phổ biến của vấn đề độ trễ trong đối tượng thuê. Nó cũng được sử dụng để báo cáo tình trạng dịch vụ và hiệu suất cho các khách hàng của chúng tôi để đo lường xu hướng theo thời gian và tự động cảnh báo về các vấn đề nhằm giảm thiểu kỹ thuật. Nếu chúng tôi không có dữ liệu này, nó sẽ ngăn chúng tôi đảm bảo hiệu suất tải xuống đầy đủ khi người dùng đồng bộ hóa các thay đổi từ SharePoint với máy tính của họ. 

Các lĩnh vực sau đây sẽ được thu thập: 

- **IsEducationNotebook** - Một bool cho biết sổ ghi chép có phải là sổ ghi chép giáo dục hay không

- **NotebookId** - ID của sổ ghi chép mà tải lên này là một phần của

- **TimeToConfirmSyncedWithServerInMs** - Thời gian tính bằng mili giây để thực hiện tải lên

### <a name="onenotestoragerealtimefiledataobjectdownload"></a>OneNote.Storage.RealTime.FileDataObjectDownload 

Tín hiệu quan trọng được sử dụng để theo dõi hiệu suất khi người dùng truyền vào đối tượng dữ liệu tệp (tức là tệp hoặc hình ảnh được nhúng) được tải xuống trực tiếp từ dịch vụ của chúng tôi và không phải là một phần của hoạt động đồng bộ hóa trên một trang, phần hoặc sổ ghi chép. Tín hiệu này chỉ được thu thập đối với các bản tải xuống hoạt động kém nhất trong 300 giây cuối (số giây đều được đặt cấu hình bởi Microsoft dựa theo hiệu suất và điều kiện dịch vụ).

Điều này được sử dụng để đảm bảo tình trạng và hiệu suất của dịch vụ bằng cách cho phép chúng tôi xem những người thuê nào đang gặp phải tình trạng tải dữ liệu chậm đến mức không thể chấp nhận được từ dịch vụ của chúng tôi và mức độ phổ biến của vấn đề về độ trễ trong người thuê và báo cáo về hành vi của chúng tôi theo thời gian cho phép chúng tôi đo lường các xu hướng của hiệu suất dịch vụ. Nếu chúng tôi thấy độ trễ không thể chấp nhận được đối với đối tượng tệp, chúng tôi cũng sẽ sử dụng dữ liệu này để tương quan dữ liệu đó với các tín hiệu khác từ khách hàng và dịch vụ liên quan đến đối tượng đó để cải thiện quy trình tải xuống của chúng tôi. Chúng tôi cũng phân chia dữ liệu dựa trên phần mở rộng của đối tượng tệp được tải xuống vì chúng tôi có các kỳ vọng khác nhau dựa trên việc tệp được trình bày nội tuyến trong bức vẽ của chúng tôi (ví dụ: hình ảnh) hay là tệp không nội tuyến (chẳng hạn như tài liệu văn bản). Nếu chúng tôi không nhận được dữ liệu này, nó sẽ ngăn chúng tôi theo dõi hiệu suất của các nội dung tải xuống này

Các lĩnh vực sau đây sẽ được thu thập: 

- **FileSizeInBytes** - Kích thước của tệp được tải xuống tính bằng byte 

- **IsImage** - Một bool xác định xem tệp đang được tải xuống có phần mở rộng khớp với danh sách định dạng hình ảnh phổ biến được xác định trước (.bmp, .emf, .gif, .jpe, .jpeg, .jpg, .png) mà chúng tôi hiển thị nội tuyến trong bức vẽ

- **TimeToDownload** - Khoảng thời gian để tải xuống thành công FDO từ bộ nhớ blob của chúng tôi vào thiết bị 

### <a name="onenotestoragerealtimewebsocketdownload"></a>OneNote.Storage.RealTime.WebSocketDownload

Tín hiệu quan trọng được sử dụng để theo dõi hiệu suất của các hoạt động đồng bộ hóa trong nước bao gồm thông tin tương quan cho phép chúng tôi theo dõi và điều tra hiệu suất tải dữ liệu từ dịch vụ của chúng tôi (onenote.com). Tín hiệu này chỉ được thu thập đối với các bản tải xuống hoạt động kém nhất trong 300 giây cuối (số giây đều được đặt cấu hình bởi Microsoft dựa theo hiệu suất và điều kiện dịch vụ).

Điều này được sử dụng để đảm bảo tình trạng dịch vụ bằng cách cho phép chúng tôi xem những đối tượng thuê nào đang gặp phải tình trạng dữ liệu đến chậm đến mức không thể chấp nhận được từ dịch vụ của chúng tôi, thông tin về dữ liệu họ đã tải xuống khi họ gặp phải vấn đề về độ trễ đó, và độ phổ biến về sự chậm trễ này đối với đối tượng thuê. Nó cũng được sử dụng để báo cáo tình trạng dịch vụ và hiệu suất cho các khách hàng của chúng tôi để đo lường xu hướng theo thời gian và tự động cảnh báo về các vấn đề nhằm giảm thiểu kỹ thuật. 

Nếu thấy độ chậm trễ không chấp nhận được đối với một phần hoặc sổ tay, chúng tôi cũng sẽ sử dụng dữ liệu này để tương quan dữ liệu đó với các tín hiệu khác từ máy khách và dịch vụ liên quan đến cùng một tài liệu để xác định các hồi quy hiệu năng phía máy khách cho phép chúng tôi cung cấp dịch vụ hiệu quả hơn.

Nếu chúng tôi không nhận được dữ liệu này, chúng tôi sẽ không thể theo dõi hiệu suất của khía cạnh này trong dịch vụ của mình hoặc tác động của những thay đổi phía máy chủ mà chúng tôi có thể thấy cần thiết do việc sử dụng hoặc các yếu tố khác.

Các lĩnh vực sau đây sẽ được thu thập:

- **DeviceSessionId** -  ID của phiên thiết bị

- **IsEducationNotebook** - Một bool cho biết sổ ghi chép có phải là sổ ghi chép giáo dục hay không

- **IsHierarchyResource** - Một bool cho biết tài nguyên có phải là tài nguyên phân cấp hay không

- **NotebookId** - ID của sổ ghi chép mà tải lên này là một phần của

- **ResourceId** - ID của tài nguyên mà chúng tôi đang tải lên

- **SectionId** - ID của phần mà tải lên này là một phần của

- **ServerSessionId** - ID của phần mà tải lên này là một phần của

- **TimeToConfirmSyncedWithServerInMs** - Thời gian tính bằng mili giây giữa một người dùng điều hướng đến một trang và ngăn xếp bản sao xác nhận rằng trang đó đồng bộ với máy chủ.

- **TimeToFirstUpdateInMs** - Thời gian tính bằng mili giây giữa công cụ đồng bộ hóa bắt đầu sao chép nội bộ của một trang và hoạt động sao chép đó đạt đến trạng thái đồng bộ hóa với trạng thái máy chủ.

### <a name="onenotestoragerealtimewebsocketupload"></a>OneNote.Storage.RealTime.WebSocketUpload

Tín hiệu quan trọng được sử dụng để theo dõi hiệu suất của các hoạt động đồng bộ hóa bên ngoài bao gồm thông tin tương quan cho phép chúng tôi theo dõi và điều tra hiệu suất của việc tải dữ liệu lên dịch vụ của chúng tôi (onenote.com)

Điều này được sử dụng để đảm bảo sức khỏe của dịch vụ bằng cách cho phép chúng tôi xem những người thuê nào đang gặp phải tình trạng dữ liệu gửi đến dịch vụ của chúng tôi chậm đến mức không thể chấp nhận được, thông tin về dữ liệu mà họ đã tải lên khi họ gặp phải sự cố đi chậm và mức độ phổ biến của vấn đề độ trễ trong đối tượng thuê. Nó cũng được sử dụng để báo cáo tình trạng dịch vụ và hiệu suất cho các khách hàng của chúng tôi để đo lường xu hướng theo thời gian và tự động cảnh báo về các vấn đề nhằm giảm thiểu kỹ thuật. Chúng tôi cũng sẽ sử dụng dữ liệu này để theo dõi tác động và hiệu quả của những cải tiến mà chúng tôi thực hiện đối với khách hàng và dịch vụ của mình. 

Nếu chúng tôi thấy độ trễ không thể chấp nhận được cho một phần hoặc sổ ghi chép, chúng tôi cũng sẽ sử dụng dữ liệu này để tương quan dữ liệu đó với các tín hiệu khác từ khách hàng và dịch vụ liên quan đến cùng một tài liệu để xác định các hồi quy hiệu suất cho phép chúng tôi mang lại trải nghiệm hiệu quả hơn.

Nếu chúng tôi không nhận được dữ liệu này, chúng tôi sẽ không thể theo dõi hiệu suất của khía cạnh này trong dịch vụ của mình hoặc tác động của những thay đổi phía máy chủ mà chúng tôi có thể thấy cần thiết do việc sử dụng hoặc các yếu tố khác.

Các lĩnh vực sau đây sẽ được thu thập: 

- **DeviceSessionId** - ID của phiên thiết bị

- **IsEducationNotebook** - Một bool cho biết sổ ghi chép có phải là sổ ghi chép giáo dục hay không

- **IsHierarchyResource** - Một bool cho biết tài nguyên có phải là tài nguyên phân cấp hay không

- **IsWorstTime** - Một bool cho biết liệu thời gian là một kiện tải lên thông thường hay là thời gian tồi tệ nhất mà chúng tôi thấy trên máy khách này trong 300 giây vừa rồi (số giây có thể được cấu hình bởi Microsoft tùy thuộc vào hiệu suất và điều kiện dịch vụ).

- **NotebookId** - ID của sổ ghi chép mà tải lên này là một phần của

- **RecommendedPutIntervalInMs** - Thời gian mà dịch vụ đã giao tiếp với khách hàng như khoảng thời gian được đề xuất

- **ResourceId** - ID của tài nguyên mà chúng tôi đang tải lên

- **SectionId** - ID của phần mà tải lên này là một phần của

- **SenderRequestId** - ID của người gửi thực hiện tải lên

- **ServerSessionId** - ID của phần mà tải lên này là một phần của

- **UploadNonSuspendedTimeInMs** - Thời gian tính bằng mili giây để thực hiện tải lên không kể thời gian ứng dụng bị tạm ngưng

- **UploadTimeInMs** - Thời gian tính bằng mili giây để thực hiện tải lên

- **WaitTimeInMs** - Thời gian tính bằng mili giây từ khi có yêu cầu tải lên đến khi quá trình tải lên bắt đầu

- **WebUrl** - WebUrl của quá trình tải lên (Được đăng nhập dưới dạng PiiWz)

### <a name="onenotestoragesynchealth"></a>OneNote.Storage.SyncHealth

Tín hiệu quan trọng được sử dụng để theo dõi các lỗi và ngoại lệ đã xảy ra bên trong ngăn xếp đồng bộ trong OneNote của khách cho phép chúng tôi theo dõi và giảm thiểu các điều kiện không mong muốn này.

Điều này được sử dụng để đảm bảo trạng thái dịch vụ bằng cách cho phép chúng tôi xem các báo cáo lỗi từ khách hàng trong thời gian gần thực tế, cho phép chúng tôi phản hồi các sự cố về đồng bộ khi chúng phát sinh. Nó cũng được sử dụng để xác định mức độ phổ biến của một vấn đề và mức độ nghiêm trọng bằng cách tham chiếu chéo thẻ lỗi với mã của máy khách để xác định nguồn gốc của lỗi. Chúng tôi cũng tổng hợp dữ liệu này để có thông tin về hiệu suất của chúng tôi theo thời gian cũng như tác động và hiệu quả của những cải tiến mà chúng tôi thực hiện đối với khách hàng và dịch vụ của mình. Nếu chúng tôi không có dữ liệu này, chúng tôi sẽ không thể chủ động phản hồi các tình trạng lỗi trong dịch vụ đồng bộ hóa của mình mà không cần khách hàng báo cáo.

Các lĩnh vực sau đây sẽ được thu thập: 

- **Service** - Dịch vụ đồng bộ hóa mà khách hàng đang sử dụng khi xảy ra lỗi (Đồng bộ hóa kế thừa hoặc hiện đại)

- **Tag** - Thẻ (giá trị nhận dạng) đại diện cho lỗi khách hàng gặp phải trong quá trình đồng bộ hóa

### <a name="onenotesynccreatenotebookfailed"></a>OneNote.Sync.CreateNotebookFailed
 
Sự kiện này đã được ghi nhật ký khi tạo sổ tay không thành công.  
 
Các trường sau đây sẽ được thu thập:
 
- **NetworkConnection** - Ghi nhật ký loại kết nối mà thiết bị hiện đang bật ví dụ: Wi-Fi, ngoại tuyến, 3G 

- **ServerType** - Ghi loại máy chủ mà sổ tay đã được tạo.

### <a name="onenotesyncfirstrunerror"></a>OneNote.Sync.FirstRunError
 
Sự kiện này đã được ghi nhật ký khi đồng bộ các Ghi chú Nhanh không thành công cho người dùng trong Trải nghiệm Lần đầu trên thiết bị.  Đây là dành riêng cho kịch bản Trải nghiệm Lần đầu.
 
Các trường sau đây sẽ được thu thập:
 
- **NetworkConnection** - Ghi nhật ký loại kết nối mà thiết bị hiện đang bật ví dụ: Wi-Fi, ngoại tuyến, 3G

- **ServerType** - Ghi nhật ký loại máy chủ mà sổ tay Ghi chú Nhanh được tạo ra

## <a name="services-configuration-events"></a>Sự kiện Cấu hình dịch vụ

Không có sự kiện dữ liệu dịch vụ bắt buộc được thu thập bởi Cấu hình dịch vụ.

## <a name="telemetry-events"></a>Sự kiện phép đo từ xa

### <a name="officeandroiddocsuipaywallcontrolpaywalloperationmetrics"></a>Office.Android.DocsUI.PaywallControl.PaywallOperationMetrics

*[Sự kiện này trước đây có tên Office.Android.DocsUI.Views.PaywallOperationMetrics.]*

Microsoft sử dụng dữ liệu này để có được tình trạng của tính năng, tỷ lệ thành công hoặc lỗi cho người dùng khi mua hàng, nhằm đảm bảo các khoản đầu tư thích hợp nhằm cải thiện trải nghiệm mua hàng của khách hàng trên các nền tảng di động.

Các trường sau đây sẽ được thu thập:

- **OperationTimeInMs** - Thời gian cần thiết để hoạt động mua hàng hoàn tất (long - mili giây)

- **PaywallOperationResult** - Thành công/Mã lỗi/Người dùng bị hủy (Enum/int - hữu hạn)

- **PaywallOperationType** - Loại hoạt động Paywall (enum/ int - hữu hạn)

### <a name="officeandroiddocsuipaywallcontrolpaywallsessiondata"></a>Office.Android.DocsUI.PaywallControl.PaywallSessionData

*[Sự kiện này trước đây có tên Office.Android.DocsUI.Views.PaywallSessionData.]*

Siêu dữ liệu dựa trên phiên khi UI Paywall được hiển thị cho người dùng. Microsoft sử dụng điều này để có được hành trình của người dùng và hiểu được thiết bị cũng như phiên bản hệ điều hành mà người dùng đang sử dụng để giúp đưa ra quyết định về các khoản đầu tư trong việc cải thiện trải nghiệm trong những lĩnh vực này.

Các trường sau đây sẽ được thu thập:

- **App Version** - Mã phiên bản của ứng dụng đang sử dụng

- **ClientId** - Mã định danh thiết bị duy nhất PII không ẩn danh (guid / chuỗi)

- **Entry Point** - Mã định danh duy nhất cho điểm nhập ngữ cảnh hoặc mảng từ ứng dụng đang sử dụng

- **isTablet** - Thiết bị có đang hiển thị UX máy tính bảng hay không

- **OSVersion** - Phiên bản hệ điều hành Android trên thiết bị

- **SessionId** - Guid: Mã định danh phiên Paywall duy nhất


### <a name="officefirstrunappletelemetryoptin"></a>Office.FirstRun.Apple.TelemetryOptIn

Sự kiện này được thu thập đối với các ứng dụng Office chạy dưới nền tảng Apple. Sự kiện được sử dụng để giám sát trạng thái của dòng chọn tham gia phép đo từ xa của chúng tôi trong trải nghiệm chạy lần đầu tiên. Chúng tôi thu thập mã biểu thị loại tùy chọn thu thập dữ liệu chẩn đoán mà người dùng đã chọn.

Các trường sau đây sẽ được thu thập:

- **Data_EventId** – Mã cho biết tùy chọn thu thập dữ liệu chẩn đoán mà người dùng đã chọn.

### <a name="officeiospaywallprovisioningresponse"></a>Office.iOS.Paywall.Provisioning.Response

Phép đo từ xa của sản phẩm được sử dụng để đối chiếu thông tin giao dịch mua hàng với hệ thống thương mại của Microsoft nhằm hỗ trợ các lợi ích đăng ký liên quan. Được sử dụng để tạo điều kiện thuận lợi cho việc ghi nhật ký giao dịch và cấp phép đăng ký để tham khảo trong tương lai và đối chiếu nội bộ.

Các trường sau đây sẽ được thu thập:

- **entryPoint** - Chuỗi – Nút/Dòng hiển thị Paywall. Như “Nút nâng cấp lên cao cấp” hoặc "Dòng chạy lần đầu".

- **failureReason** - Chuỗi – Chỉ được thêm vào khi trạng thái là “failure” (không thành công). Chỉ ra phản hồi lỗi do phản hồi Cấp phép RFS đưa ra.

- **productId** - Chuỗi – ID cửa hàng ứng dụng của sản phẩm mà yêu cầu được thực hiện

- **status** - Chuỗi – Thành công hay thất bại, cho biết yêu cầu thành công hay thất bại


### <a name="officeiospaywallstorekitresponse"></a>Office.iOS.Paywall.StoreKit.Response

Dữ liệu được thu thập làm phép đo từ xa kỹ thuật quan trọng để ghi lại kết quả của nỗ lực mua hàng do người dùng kích hoạt thủ công. Phép đo từ xa của sản phẩm được sử dụng để đối chiếu thông tin giao dịch mua hàng với hệ thống thương mại của Microsoft nhằm hỗ trợ các lợi ích đăng ký liên quan.

Các trường sau đây sẽ được thu thập:

- **entryPoint** - Chuỗi – Nút/Dòng hiển thị Paywall. Như “Nút nâng cấp lên cao cấp” hoặc "Dòng chạy lần đầu".

- **failureReason** - Chuỗi – Chỉ được thêm vào khi trạng thái là “failure” (không thành công). Chỉ ra phản hồi lỗi do phản hồi Cửa hàng ứng dụng đưa ra.

- **productId** - Chuỗi – Chỉ dành cho “MakePurchase”, “PendingPurchase”, ID cửa hàng ứng dụng của sản phẩm mà yêu cầu được thực hiện.

- **productsCount** - Int – Chỉ dành cho “ProductsFetch”, số lượng sản phẩm được Cửa hàng trả về.

- **requestType** - Chuỗi – Loại yêu cầu StoreKit. Như “ProductsFetch”, “PendingPurchase”

- **status** - Chuỗi – Thành công hay thất bại, cho biết yêu cầu thành công hay thất bại

### <a name="officeonenotegetsharepointidsfordocument"></a>Office.OneNote.GetSharePointIdsForDocument

Dữ liệu được thu thập ghi lại sự thất bại và thành công khi tìm nạp ID SharePoint (SPO) cho URL tài liệu. Sự thành công và thất bại (bao gồm nguyên nhân thất bại) của cuộc gọi sẽ được ghi lại cho tất cả nền tảng. Điểm đánh dấu này sẽ được yêu cầu để theo dõi và chẩn đoán trạng thái cuộc gọi đã được thực hiện để lấy ID. Các ID cần có để dữ liệu trang OneNote (thuộc sổ ghi chép lưu trữ trên SharePoint) hiển thị trong nguồn cấp dữ liệu. 

Các trường sau đây sẽ được thu thập:

- **ErrorCode** - giá trị số nguyên của lỗi

- **ErrorMessage** - chuỗi mô tả lỗi

- **FailureType** - chuỗi xác định loại lỗi

- **HttpStatusCode** - Mã lỗi HTTP cho cuộc gọi mạng

- **InnerErrorCode** - mã số nguyên

- **InnerErrorMesage** - thông báo lỗi

- **IsSuccess** - giá trị Boolean cho tín hiệu thành công

### <a name="officeonenotegetsharepointidsfordocumentw32old"></a>Office.OneNote.GetSharePointIdsForDocumentW32Old

Dữ liệu đo từ xa ghi lại các kịch bản thất bại và thành công khi tìm nạp ID SharePoint (SPO) cho URL tài liệu. Sự thành công và thất bại (bao gồm nguyên nhân thất bại) của cuộc gọi sẽ được ghi lại. Dữ liệu này chỉ được ghi lại vào nền tảng win32 cũ. Điểm đánh dấu này sẽ được yêu cầu để theo dõi và chẩn đoán trạng thái cuộc gọi đã được thực hiện để lấy ID. Các ID cần có để dữ liệu trang OneNote (thuộc sổ ghi chép lưu trữ trên SharePoint) hiển thị trong nguồn cấp dữ liệu. 

Các trường sau đây sẽ được thu thập:

- **ErrorCode** - giá trị số nguyên của lỗi

- **ErrorMessage** - chuỗi mô tả lỗi

- **FailureType** - chuỗi xác định loại lỗi

- **HttpStatusCode** - Mã lỗi HTTP cho cuộc gọi mạng

- **InnerErrorCode** - mã số nguyên

- **InnerErrorMesage** - thông báo lỗi

- **IsSuccess** - giá trị Boolean cho tín hiệu thành công


### <a name="officesystemgracefulexitgracefulappexitdesktop"></a>Office.System.GracefulExit.GracefulAppExitDesktop

Sự kiện này được kích hoạt bằng cách chấm dứt ứng dụng duyên dáng cho các ứng dụng khách không giới hạn của Office như Word, Excel, PowerPoint và Outlook. Chúng tôi dùng Graceful Exit để đo lường tình trạng sức khoẻ của sản phẩm máy khách Office. Đây là một tín hiệu quan trọng trong kinh doanh được sử dụng bởi các kĩ sư Office để suy ra độ bền của sản phẩm.

Các trường sau đây sẽ được thu thập:

- **AppBuild** - Mã định danh phiên bản Build cho quá trình bị ảnh hưởng.
- **AppMajor** - Mã định danh phiên bản Major cho quá trình bị ảnh hưởng.
- **AppMinor** - Mã định danh phiên bản Minor cho quá trình bị ảnh hưởng.
- **AppRevision** - Mã định danh phiên bản Revision cho quá trình bị ảnh hưởng.
- **BootCompleted** – Là quá trình Office hoàn thành khởi động.
- **DetectionTime** - Thời điểm khi việc thoát ra không mong muốn được phát hiện.
- **ecsETag** - Mã định danh thử nghiệm cho quy trình.
- **HasEdit** – Là tài liệu đang chỉnh sửa đã xảy ra trong quá trình Office.
- **HasOpen** – Là tài liệu đã được mở trong quá trình Office.
- **InstallMethod** - Phiên bản dựng hiện tại của Office đã được nâng cấp từ, quay lại hay cài đặt mới.
- **OfficeUILang** – Ngôn ngữ của quá trình Office.
- **PreviousBuild** - Phiên bản xây dựng đã được cài đặt trước đó.
- **SafeMode** – Là quá trình Office ở chế độ an toàn.
- **SessionId-** - Một định danh duy nhất của quá trình.
- **SessionInitTime**- Thời gian khi quy trình bị ảnh hưởng bắt đầu. 

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Thông tin nhận dạng người dùng là cần thiết để thực hiện các yêu cầu chủ đề dữ liệu.

Các trường sau đây sẽ được thu thập:

  - **IdentityChanged** - Luôn đúng. Danh tính thay đổi.

  - **TimerDetectedChange** - Liệu thay đổi có được phát hiện bằng cách ping thường xuyên theo thời gian hay không.

### <a name="officesystemprivacyfallbacktosettingsstore"></a>Office.System.PrivacyFallbackToSettingsStore

Dùng để xác định xem có sự cố khi đọc các cài đặt quyền riêng tư của người dùng từ lưu trữ chuyển vùng hay không.

Các trường sau đây sẽ được thu thập:

  - **Tag-** Thẻ mã cho biết cài đặt nào đã quay lại vào lưu trữ cài đặt.

### <a name="officesystemsessiondatao365"></a>Office.System.SessionDataO365

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **AppId -** Mã định danh cho ứng dụng Office mà dữ liệu này tham chiếu tới.

  - **ApplicationArchitecture -** Kiến trúc bộ vi xử lý mà Office được thiết kế cho.

  - **AppVersionBuild -** Phiên bản bản dựng của ứng dụng Office.

  - **AppVersionBuild -** Phiên bản chính của ứng dụng Office.

  - **AppVersionBuild -** Phiên bản phụ của ứng dụng Office.

  - **AppVersionBuild -** Chỉnh sửa bản dựng của ứng dụng Office.

  - **CollectorVersion -** M định danh phiên bản cho lô-gic tuyển tập máy khách.

  - **DeviceHash -** Hash một chiều của mã định danh thiết bị của hệ điều hành.

  - **DeviceName -** Tên của thiết bị mà Office đang chạy trên đó

  - **Domain -** Tên miền của thiết bị mà Office đang chạy trên đó

  - **IsCeip -** Việc cài đặt Office có được đăng ký hay không trong Chương trình cải thiện trải nghiệm khách hàng không còn tồn tại.

  - **IsDebug -** Đây có phải là bản dựng gỡ lỗi của Office hay không.

  - **IsImmersive -** Liệu ứng dụng Office có phải là một ứng dụng Windows phổ quát hay là một ứng dụng chân thực.

  - **IsLaptop -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính xách tay hay không.

  - **IsMicrosoftInternal -** Liệu người dùng Windows mà Office đang chạy có phải nhân viên của Microsoft hay không.

  - **IsO365 -** Liệu việc cài đặt Office có phải là một phần của chương trình Outlook 365 không còn tồn tại hay không.

  - **IsTablet -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính bảng hay không.

  - **IsTerminalServer -** Đó là máy khách máy chủ đầu cuối là đúng hay sai

  - **MaxMemory -** Dung lượng bộ nhớ truy cập ngẫu nhiên tối đa có sẵn cho thiết bị chạy Office.

  - **OsArchitecture -** Kiến trúc CPU mà hệ điều hành đang chạy Office được xây dựng cho,

  - **OsVersionBuild -** Phiên bản bản dựng của hệ điều hành

  - **OsVersionMajor -** Phiên bản chính của hệ điều hành

  - **OsVersionMajor -** Phiên bản phụ của hệ điều hành

  - **OsVersionUpdate -** Bản chỉnh sửa bản dựng của hệ điều hành

  - **ProcessFileName -** Tên thực thi của ứng dụng đang chạy.

  - **ProcessorArchitecture -** Kiến trúc bộ vi xử lý Office đang chạy trên đó.

  - **ProcessorFrequency -** Tốc độ của bộ vi xử lý trên các thiết bị Office đang chạy trên Megahertz.

  - **SessionStart -** Thời gian mà tại đó quá trình Office đang chạy bắt đầu.

  - **UserName -** Tên tài khoản chạy Office.

### <a name="officesystemsystemhealthcoremetadata"></a>Office.System.SystemHealthCoreMetadata

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **AppBuild -** Phiên bản bản dựng của ứng dụng Office.

  - **AppBuildRevision -** Bản chỉnh sửa bản dựng của ứng dụng Office.

  - **AppMajorVer -** Phiên bản chính của ứng dụng Office.

  - **AppMinorVer -** Phiên bản phụ của ứng dụng Office.

  - **CID -** Danh tính người dùng giả danh

  - **CollectibleClassifications -** Tập hợp các phân loại dữ liệu có thể được thu thập.

  - **CollectionTime -** Thời gian mà tại đó siêu dữ liệu đã được thu thập.

  - **DeviceManufacturer -** Nhà sản xuất của thiết bị mà Office đang chạy trên đó.

  - **DeviceModel -** Model của thiết bị mà Office đang chạy trên đó.

  - **FirstRunTime -** Lần đầu tiên một ứng dụng Office được chạy.

  - **IsClickToRunInstall -** Ứng dụng Office đã được cài đặt bằng Click -To-Run hay chưa

  - **IsDebug -** Liệu đây có phải là bản dựng gỡ lỗi của Office hay không.

  - **IsLabMachine -** Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không.

  - **IsLaptop -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính xách tay hay không.

  - **IsMsftInternal -** Liệu người dùng Windows mà Office đang chạy có phải nhân viên của Microsoft hay không.

  - **IsSubscription -** Liệu ứng dụng Office có được cài đặt theo giấy phép đăng ký hay không.

  - **IsTablet -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính bảng hay không.

  - **IsTerminalServer -** Office có đang được chạy trên một máy chủ đầu cuối hay không.

  - **MsoAppId -** Mã định danh cho ứng dụng Office mà dữ liệu này tham chiếu tới.

  - **OfficeArchitectureText -** Kiến trúc bộ vi xử lý mà Office được thiết kế cho.

  - **OsBuild -** Phiên bản bản dựng của hệ điều hành

  - **OsBuildRevision -** Bản chỉnh sửa bản dựng của hệ điều hành

  - **OSEnvironment -** Mã định danh cho môi trường mà Office đang chạy.

  - **OsMajorVer -** Phiên bản chính của hệ điều hành.

  - **OsMinorVer -** Phiên bản phụ của hệ điều hành

  - **OSVersionString -** Phiên bản hệ điều hành dưới dạng một chuỗi.

  - **ProcessorArchitecture -** Kiến trúc bộ vi xử lý mà Office đang chạy trên.

  - **ProcessorCount -** Số lượng bộ vi xử lý trên thiết bị mà Office đang chạy.

  - **ProcSpeedMHz -** Tốc độ của bộ vi xử lý trên các thiết bị Office đang chạy trên Megahertz.

  - **RamMB -** Dung lượng RAM khả dụng trong thiết bị Office đang chạy trên đó.

  - **SqmUserId -** Mã định danh ngẫu nhiên cho bản cài đặt Office.

### <a name="officesystemsystemhealthdesktopsessionlifecycleandheartbeat"></a>Office.System.SystemHealthDesktopSessionLifecycleAndHeartbeat

Cung cấp thông tin về các số liệu trạng thái hệ thống.

Các trường sau đây sẽ được thu thập:

  - **InstallMethod** - Bản dựng hiện tại của Office đã được nâng cấp từ, quay lại hay cài đặt mới.

  - **OfficeArchitectureText** - Kiến trúc của sản phẩm Office dưới dạng chuỗi (ví dụ: x86, arm).

  - **PreviousBuild** - Phiên bản Office mà bản dựng này được nâng cấp lên hoặc quay lại từ đó.

  - **State** - Trạng thái mà phiên thay đổi thành.

  - **Time** - Thời gian khi trạng thái phiên thay đổi.

### <a name="officesystemsystemhealthessentialidentitycount"></a>Office.System.SystemHealthEssentialIdentityCount

Thu thập số lượng danh tính người dùng đã đăng nhập

Các trường sau đây sẽ được thu thập:

  - **AllIdentityCount** - Số lượng toàn bộ danh tính

  - **ValidIdentityCount** - Số lượng danh tính xác nhận

### <a name="officesystemsystemhealthessentialmetadataallidentities"></a>Office.System.SystemHealthEssentialMetadataAllIdentities

Theo dõi trạng thái của các tài khoản được Office công nhận trong phiên này. Được sử dụng để cô lập một lỗi cho loại đăng nhập tài khoản nếu lỗi đó là dành riêng cho một loại.

Các trường sau đây sẽ được thu thập:

  - **CollectionTime** - Thời gian mà thông tin danh tính được thu thập.

  - **IdentityType** - Loại xác thực hoặc tài khoản

  - **IdentityUniqueId** - Mã định danh tính giả mạo

  - **IdentityUniqueIdHashed** - Hash một chiều của ID danh tính duy nhất

### <a name="officesystemsystemhealthmetadataapplicationadditional"></a>Office.System.SystemHealthMetadataApplicationAdditional

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **Alias -** Nếu người dùng chạy Office là nhân viên Microsoft, biệt danh nội bộ công ty của họ.

  - **AppBuild -** Phiên bản bản dựng của ứng dụng Office.

  - **AppBuildRevision -** Bản chỉnh sửa bản dựng của ứng dụng Office.

  - **AppMajorVer -** Phiên bản chính của ứng dụng Office.

  - **AppMinorVer -** Phiên bản phụ của ứng dụng Office.

  - **CID -** Danh tính người dùng giả danh

  - **CollectibleClassifications -** Tập hợp các phân loại dữ liệu có thể được thu thập.

  - **DeviceManufacturer -** Nhà sản xuất của thiết bị mà Office đang chạy trên đó.

  - **DeviceModel -** Model của thiết bị mà Office đang chạy trên đó.

  - **DeviceProcessorModel -** Model bộ vi xử lý của thiết bị mà Office đang chạy trên đó.

  - **DigitizerInfo -** Thông tin về bộ số hóa được gắn vào thiết bị Office đang chạy trên đó

  - **DomainName -** Tên miền mà máy chạy Office đã kết nối với (nếu có).

  - **FirstRunTime -** Lần đầu tiên một ứng dụng Office được chạy.

  - **HorizontalResolution -** Độ phân giải màn hình theo chiều ngang

  - **IsDebug -** Liệu đây có phải là bản dựng gỡ lỗi của Office hay không.

  - **IsImmersive -** Liệu ứng dụng Office có phải là một ứng dụng Windows phổ quát hay là một ứng dụng chân thực.

  - **IsJoinedToDomain -** Thiết bị chạy Office có phải là miền tham gia hay không.

  - **IsLabMachine -** Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không.

  - **IsLaptop -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính xách tay hay không.

  - **IsMsftInternal -** Người dùng Windows mà Office đang chạy có phải nhân viên của Microsoft hay không.

  - **IsOEMInstalled -** Việc chạy ứng dụng Office có được cài đặt bằng một OEM hay không.

  - **IsRunAsAdmin -** Ứng dụng Office có đang chạy với tư cách người quản trị hay không.

  - **IsSubscription -** Liệu ứng dụng Office có được cài đặt theo giấy phép đăng ký hay không.

  - **MsoAppId -** Mã định danh cho ứng dụng Office mà dữ liệu này tham chiếu tới.

  - **NumProcPhysCores -** Số lượng lõi vật lý trong bộ vi xử lý.

  - **OfficeBuild -** Phiên bản bản dựng của thư viện chung Office.

  - **OfficeBuildRevision -** Phiên bản bản chỉnh sửa bản dựng của thư viện chung Office.

  - **OfficeMajorVer -** Phiên bản chính của thư viện chung Office.

  - **OfficeMinorVer -** Phiên bản phụ của thư viện chung Office.

  - **OsBuild -** Phiên bản bản dựng của hệ điều hành

  - **OsBuildRevision -** Bản chỉnh sửa bản dựng của hệ điều hành

  - **OsMajorVer -** Phiên bản chính của hệ điều hành.

  - **OsMinorVer -** Phiên bản phụ của hệ điều hành

  - **PowerPlatformRole -** Mã định danh về vai trò máy tính ưa thích OEM của thiết bị mà Office được chạy trên.

  - **ProcessFileName -** Tên thực thi của ứng dụng đang chạy.

  - **ProcessorCount -** Số lượng bộ vi xử lý trên thiết bị mà Office đang chạy trên đó.

  - **RamMB -** Dung lượng RAM khả dụng trong thiết bị Office đang chạy trên đó.

  - **SqmUserId -** Mã định danh ngẫu nhiên cho bản cài đặt Office.

  - **StudyId -** Mã định danh nghiên cứu Số liệu chất lượng phần mềm.

  - **VerticalResolution -** Độ phân giải màn hình theo chiều dọc

  - **WinUserActType -** Người dùng Windows chạy Office có phải là người quản trị viên, người dùng quyền lực hay người dùng bình thường.

### <a name="officesystemsystemhealthmetadataapplicationandlanguage"></a>Office.System.SystemHealthMetadataApplicationAndLanguage

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **AppBuild -** Phiên bản bản dựng của ứng dụng Office.

  - **AppBuildRevision -** Bản chỉnh sửa bản dựng của ứng dụng Office.

  - **AppMajorVer -** Phiên bản chính của ứng dụng Office.

  - **AppMinorVer -** Phiên bản phụ của ứng dụng Office.

  - **AppState -** Mã định danh cho trạng thái của ứng dụng Office.

  - **Click2RunPackageVersionBuild -** Phiên bản bản dựng của vào gói trình cài đặt click-to-run.

  - **Click2RunPackageVersionMajor -** Phiên bản chính của vào gói trình cài đặt click-to-run.

  - **Click2RunPackageVersionMinor -** Phiên bản phụ của vào gói trình cài đặt click-to-run.

  - **Click2RunPackageVersionRevision -** Phiên bản bản chỉnh sửa bản dựng của vào gói trình cài đặt click-to-run.

  - **DistributionChannel -** Kênh mà Office đã được phân phối.

  - **InstallType -** Mã định danh cho phương thức mà Office được cài đặt.

  - **IsClickToRunInstall -** Ứng dụng Office đã được cài đặt bằng cách sử dụng click-to-run hay không

  - **IsDebug -** Liệu đây có phải là bản dựng gỡ lỗi của Office hay không.

  - **IsImmersive -** Liệu ứng dụng Office có phải là một ứng dụng Windows phổ quát hay là một ứng dụng chân thực.

  - **IsMsftInternal -** Người dùng Windows mà Office đang chạy có phải nhân viên của Microsoft hay không.

  - **IsOEMInstalled -** Việc chạy ứng dụng Office có được cài đặt bằng một OEM hay không.

  - **IsRunAsAdmin -** Ứng dụng Office có đang chạy với tư cách người quản trị hay không.

  - **IsSubscription -** Liệu ứng dụng Office có được cài đặt theo giấy phép đăng ký hay không.

  - **MsoAppId -** Mã định danh cho ứng dụng Office mà dữ liệu này tham chiếu tới.

  - **OfficeArchitectureText -** Kiến trúc bộ vi xử lý mà Office được thiết kế cho.

  - **OfficeBuild -** Phiên bản bản dựng của thư viện chung Office.

  - **OfficeBuildRevision -** Phiên bản bản chỉnh sửa bản dựng của thư viện chung Office.

  - **OfficeMajorVer -** Phiên bản chính của thư viện chung Office.

  - **OfficeMinorVer -** Phiên bản phụ của thư viện chung Office.

  - **OfficeMuiCount -** Số lượng gói ngôn ngữ Office được cài đặt.

  - **OfficeSkuLanguage -** Ngôn ngữ SKU được cài đặt.

  - **OfficeSkuLanguageTag -** Ngôn ngữ SKU được cài đặt.

  - **OfficeUiLang -** Ngôn ngữ giao diện người dùng cho ứng dụng Office.

  - **OfficeUiLangTag -** Ngôn ngữ giao diện người dùng cho ứng dụng Office.

  - **ProcessFileName -** Tên thực thi của ứng dụng đang chạy.

  - **SqmAppId -** Mã định danh cho ứng dụng Office mà dữ liệu này tham chiếu tới.

### <a name="officesystemsystemhealthmetadatadelayedlogin"></a>Office.System.SystemHealthMetadataDelayedLogin

Thông tin nhận dạng người dùng là cần thiết để thực hiện các yêu cầu chủ đề dữ liệu.

Các trường sau đây sẽ được thu thập:

  - **CID** - Danh tính người dùng giả danh

### <a name="officesystemsystemhealthmetadatadevice"></a>Office.System.SystemHealthMetadataDevice

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **CollectionTime -** Thời gian mà tại đó siêu dữ liệu đã được thu thập.

  - **ComputerSystemProductUuidHash -** Hash một chiều của Bo mạch UUID.

  - **DeviceClass -** Mã định danh cho loại thiết bị mà Office đang chạy trên đó.

  - **DeviceMake -** Mã định danh gia đình hệ thống phần cứng của thiết bị mà Office đang chạy trên đó.

  - **DeviceManufacturer -** Nhà sản xuất của thiết bị mà Office đang chạy trên đó.

  - **DeviceModel -** Model của thiết bị mà Office đang chạy trên đó.

  - **DigitizerInfo -** Thông tin về bộ số hóa được gắn vào thiết bị Office đang chạy trên đó

  - **IsLaptop -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính xách tay hay không.

  - **IsTablet -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính bảng hay không.

  - **LicensingACID -** Mã định danh cấp phép cho bản cài đặt Office.

  - **DeviceModel -** Tên của thiết bị mà Office đang chạy trên đó.

  - **NumProcPhysCores -** Số lượng lõi vật lý trong bộ vi xử lý.

  - **NumProcShareSingleCache -** Số lượng bộ vi xử lý chia sẻ bộ đệm duy nhất trên thiết bị mà Office đang chạy trên đó.

  - **NumProcShareSingleCore -** Số lượng bộ vi xử lý trên mỗi lõi vật lý trên thiết bị mà Office đang chạy trên đó.

  - **OlsLicenseId -** Mã định danh cấp phép cho bản cài đặt Office.

  - **Platform -** Mã định danh cho môi trường mà Office đang chạy trên đó.

  - **PowerPlatformRole -** Mã định danh về vai trò máy tính ưu tiên OEM của thiết bị mà Office đang chạy trên đó.

  - **ProcessorCount -** Số lượng bộ vi xử lý trên thiết bị mà Office đang chạy trên đó.

  - **ProcSpeedMHz -** Tốc độ của bộ vi xử lý trên các thiết bị mà Office đang chạy trên Megahertz.

  - **ProcType -** Cấu trúc của bộ vi xử lý.

  - **ProcTypeText -** Loại bộ vi xử lý trên thiết bị mà Office đang chạy trên đó.

  - **RamMB -** Dung lượng RAM khả dụng trong thiết bị mà Office đang chạy trên đó.

  - **SusClientId -** ID bản cập nhật Windows của thiết bị mà Office đang chạy trên đó.

  - **SystemFamily -** Mã định danh gia đình hệ thống phần cứng của thiết bị mà Office đang chạy trên đó.

  - **SystemSKU -** Mã định danh SKU hệ thống phần cứng của thiết bị mà Office đang chạy trên đó.

  - **SysVolFreeSpaceMB -** Lượng dung lượng sẵn dùng trên dung lượng hệ thống tính bằng megabyte.

  - **SysVolSizeMB -** Lượng dung lượng cho dung lượng hệ thống tính bằng megabyte.

  - **WindowsErrorReportingMachineId -** Mã định danh máy được chỉ định cho báo cáo lỗi Windows của thiết bị mà Office đang chạy trên đó.

  - **WindowsSqmMachineId -** Mã định danh máy được chỉ định cho Windows của thiết bị mà Office đang chạy trên đó.

### <a name="officesystemsystemhealthmetadatadeviceconsolidated"></a>Office.System.SystemHealthMetadataDeviceConsolidated

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **BootDiskType -** Ổ đĩa hoặc ổ đĩa cứng

  - **ComputerSystemProductUuidHash -** Hash một chiều của Bo mạch UUID.

  - **DeviceClass -** Mã định danh cho loại thiết bị mà Office đang chạy trên đó.

  - **DeviceManufacturer -** Nhà sản xuất của thiết bị mà Office đang chạy trên đó.

  - **DeviceModel -** Model của thiết bị mà Office đang chạy trên đó.

  - **DeviceProcessorModel -** Model bộ vi xử lý của thiết bị mà Office đang chạy trên đó.

  - **DigitizerInfo -** Thông tin về bộ số hóa được gắn vào thiết bị Office đang chạy trên đó

  - **HasSpectreFix -** Liệu bộ vi xử lý của thiết bị mà Office chạy trên đó có sửa lỗi Spectre hay không.

  - **IsLaptop -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính xách tay hay không.

  - **IsTablet -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính bảng hay không.

  - **DeviceModel -** Tên của thiết bị mà Office đang chạy trên đó.

  - **NumProcPhysCores -** Số lượng lõi vật lý trong bộ vi xử lý.

  - **NumProcShareSingleCache -** Số lượng bộ vi xử lý chia sẻ bộ đệm duy nhất trên thiết bị mà Office đang chạy trên đó.

  - **NumProcShareSingleCore -** Số lượng bộ vi xử lý trên mỗi lõi vật lý trên thiết bị mà Office đang chạy trên đó.

  - **Platform -** Mã định danh cho môi trường mà Office đang chạy trên đó.

  - **PowerPlatformRole -** Mã định danh về vai trò máy tính ưa thích OEM của thiết bị mà Office đang chạy trên đó.

  - **PowerPlatformRole -** Mã định danh về vai trò máy tính ưa thích OEM của thiết bị mà Office đang chạy trên đó.

  - **ProcessorCount -** Số lượng bộ vi xử lý trên thiết bị mà Office đang chạy trên đó.

  - **ProcSpeedMHz -** Tốc độ của bộ vi xử lý trên các thiết bị mà Office đang chạy trên Megahertz.

  - **ProcType -** Cấu trúc của bộ vi xử lý.

  - **ProcTypeText -** Loại bộ vi xử lý trên thiết bị mà Office đang chạy trên đó.

  - **RamMB -** Dung lượng RAM khả dụng trong thiết bị mà Office đang chạy trên đó.

  - **SusClientId -** ID bản cập nhật Windows của thiết bị mà Office đang chạy trên đó.

  - **SysVolFreeSpaceMB -** Lượng dung lượng sẵn dùng trên dung lượng hệ thống tính bằng megabyte.

  - **SysVolSizeMB -** Lượng dung lượng cho dung lượng hệ thống tính bằng megabyte.

  - **SysVolSizeMB -** Lượng dung lượng cho dung lượng hệ thống tính bằng megabyte.

  - **WindowsErrorReportingMachineId -** Mã định danh máy được chỉ định cho báo cáo lỗi Windows của thiết bị mà Office đang chạy trên đó.

  - **WindowsSqmMachineId -** Mã định danh máy được chỉ định cho Windows của thiết bị mà Office đang chạy trên đó.

### <a name="officesystemsystemhealthmetadataoperatingsystem"></a>Office.System.SystemHealthMetadataOperatingSystem

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **CollectionTime** - Thời gian sự kiện này đã được xếp hàng đợi để tải lên

  - **IsTerminalServer -** Đó là máy khách máy chủ đầu cuối là đúng hay sai

  - **OsBuild -** Phiên bản bản dựng của hệ điều hành.

  - **OsBuildRevision -** Bản chỉnh sửa bản dựng của hệ điều hành

  - **OSEnvironment** -Windows, iOS, Mac, Android, v.v.

  - **OsMajorVer -** Phiên bản chính của hệ điều hành.

  - **OsMinorVer -** Phiên bản phụ của hệ điều hành.

  - **OSSDKVersionCode** - Mã định danh phiên bản cho SDK hệ điều hành.

  - **OsSku** - SKU hệ điều hành

  - **OsSuite2** - Mã định danh bộ sản phẩm hệ điều hành.

  - **OSVersionString -** Mã định danh phiên bản hệ điều hành.

  - **ServicePackMajorVer** - Phiên bản chính gói hệ điều hành

  - **ServicePackMinorVer** - Phiên bản phụ gói hệ điều hành

### <a name="officesystemsystemhealthmetadataoperatingsystemdevice"></a>Office.System.SystemHealthMetadataOperatingSystemDevice

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **CollectionTime** - Thời gian sự kiện này đã được xếp hàng đợi để tải lên

  - **DeviceClass -** Mã định danh cho loại thiết bị mà Office đang chạy trên đó.

  - **DeviceManufacturer -** Nhà sản xuất của thiết bị mà Office đang chạy trên đó.

  - **DeviceModel -** Model của thiết bị mà Office đang chạy trên đó.

  - **DigitizerInfo -** Thông tin về bộ số hóa được gắn vào thiết bị Office đang chạy trên đó

  - **IsLaptop -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính xách tay hay không.

  - **IsTablet -** Liệu thiết bị mà Office đang chạy trên đó có phải là máy tính bảng hay không.

  - **IsTerminalServer -** Đó là máy khách máy chủ đầu cuối là đúng hay sai

  - **DeviceModel -** Tên của thiết bị mà Office đang chạy trên đó.

  - **NumProcPhysCores -** Số lượng lõi vật lý trong bộ vi xử lý.

  - **NumProcShareSingleCache -** Số lượng bộ vi xử lý chia sẻ bộ đệm duy nhất trên thiết bị mà Office đang chạy trên đó.

  - **NumProcShareSingleCore -** Số lượng bộ vi xử lý trên mỗi lõi vật lý trên thiết bị mà Office đang chạy trên đó.

  - **OsBuild -** Phiên bản bản dựng của hệ điều hành.

  - **OsBuildRevision -** Bản chỉnh sửa bản dựng của hệ điều hành

  - **OSEnvironment** -Windows, iOS, Mac, Android, v.v.

  - **OsMajorVer -** Phiên bản chính của hệ điều hành.

  - **OsMinorVer -** Phiên bản phụ của hệ điều hành.

  - **OSSDKVersionCode** - Mã định danh phiên bản cho SDK hệ điều hành.

  - **OsSku** - SKU hệ điều hành

  - **OsSuite2** - Mã định danh bộ sản phẩm hệ điều hành.

  - **OSVersionString -** Mã định danh phiên bản hệ điều hành.

  - **Platform -** Mã định danh cho môi trường mà Office đang chạy trên đó.

  - **PowerPlatformRole -** Mã định danh về vai trò máy tính ưu tiên OEM của thiết bị mà Office đang chạy trên đó.

  - **ProcessorCount -** Số lượng bộ vi xử lý trên thiết bị mà Office đang chạy trên đó.

  - **ProcSpeedMHz -** Tốc độ của bộ vi xử lý trên các thiết bị mà Office đang chạy trên Megahertz.

  - **ProcTypeText -** Kiểu bộ vi xử lý

  - **RamMB -** Dung lượng RAM khả dụng trong thiết bị mà Office đang chạy trên đó.

  - **ServicePackMajorVer** - Phiên bản chính gói hệ điều hành

  - **ServicePackMinorVer** - Phiên bản phụ gói hệ điều hành

  - **SysVolFreeSpaceMB -** Lượng dung lượng sẵn dùng trên dung lượng hệ thống tính bằng megabyte.

  - **SysVolSizeMB -** Lượng dung lượng cho dung lượng hệ thống tính bằng megabyte.

### <a name="officesystemsystemhealthmetadataos"></a>Office.System.SystemHealthMetadataOS

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **CountryRegion -** Thiết đặt mã định danh của quốc gia/khu vực của hệ điều hành.

  - **HorizontalResolution -** Độ phân giải màn hình theo chiều ngang

  - **IsTerminalServer -** Đó là máy khách máy chủ đầu cuối là đúng hay sai

  - **KeyboardLanguage -** Mã định danh ngôn ngữ bàn phím thiết bị

  - **KeyboardLanguageTag -** Mã định danh ngôn ngữ bàn phím thiết bị

  - **OfficeWvd -** xác định trạng thái máy tính chạy Windows ảo.

  - **OsBuild -** Phiên bản bản dựng của hệ điều hành.

  - **OsBuildRevision -** Bản chỉnh sửa bản dựng của hệ điều hành

  - **OSEnvironment** -Windows, iOS, Mac, Android, v.v.

  - **OsLocale -** Mã định danh địa phương của hệ điều hành.

  - **OsLocaleTag -** Mã định danh địa phương của hệ điều hành.

  - **OsMajorVer -** Phiên bản chính của hệ điều hành.

  - **OsMinorVer -** Phiên bản phụ của hệ điều hành.

  - **OSSDKVersionCode** - Mã định danh SDK cho SDK hệ điều hành.

  - **OsSku -** Mã định danh SDK cho SDK hệ điều hành.

  - **OsSuite2** - Mã định danh bộ sản phẩm hệ điều hành.

  - **OsUiLang -** Ngôn ngữ giao diện người dùng của hệ điều hành.

  - **OSVersionString -** Mã định danh phiên bản hệ điều hành.

  - **ScreenDepth -** Độ sâu màn hình

  - **ScreenDpi -** Dpi màn hình 

  - **ServicePackMajorVer** - Phiên bản chính gói hệ điều hành

  - **ServicePackMinorVer** - Phiên bản phụ gói hệ điều hành

  - **SystemLocale -** Ngôn ngữ mặc định của hệ điều hành

  - **SystemLocaleTag -** Ngôn ngữ mặc định của hệ điều hành

  - **TimeZoneBiasInMinutes -** Sự khác biệt về số phút giữa giờ địa phương và giờ UTC.

  - **VerticalResolution -** Độ phân giải màn hình theo chiều dọc

### <a name="officesystemsystemhealthmetadatascreencultureusersqmid"></a>Office.System.SystemHealthMetadataScreenCultureUserSqmId

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **Biệt danh -** Nhân viên Microsoft hoặc biệt danh người dùng tự động

  - **CID -** Danh tính người dùng giả danh

  - **CollectibleClassifications -** Phân loại dữ liệu có thể được thu thập theo cài đặt quyền riêng tư của máy khách

  - **CollectionTime** - Thời gian sự kiện này đã được xếp hàng đợi để tải lên

  - **CountryRegion -** Thiết đặt mã định danh của quốc gia/khu vực của hệ điều hành.

  - **DomainName -** Tên miền Microsoft

  - **HorizontalResolution -** Độ phân giải màn hình theo chiều ngang

  - **IntegratedScreenSize -** Kích cỡ màn hình tích hợp.

  - **IsJoinedToDomain -** Tên miền máy khách được tham gia là đúng hay sai

  - **IsLabMachine -** là máy nghiệm thử nghiệm Microsoft

  - **IsMsftInternal -** Máy trong tên miền doanh nghiệp của Microsoft là đúng hay sai

  - **IsSubscription -** Liệu ứng dụng Office có được cài đặt theo giấy phép đăng ký hay không.

  - **KeyboardLanguage -** Mã định danh ngôn ngữ bàn phím thiết bị

  - **KeyboardLanguageTag -** Mã định danh ngôn ngữ bàn phím thiết bị

  - **OsLocale -** Mã định danh địa phương của hệ điều hành.

  - **OsLocaleTag -** Mã định danh địa phương của hệ điều hành.

  - **OsUiLang -** Ngôn ngữ giao diện người dùng của hệ điều hành.

  - **ScreenDepth -** Độ sâu màn hình

  - **ScreenDpi -** Dpi màn hình 

  - **ScreenXDpi -** DPI X màn hình

  - **ScreenYDpi -** DPI Y màn hình

  - **SqmUserId -** Mã định danh ngẫu nhiên cho bản cài đặt Office.

  - **StudyId -** Mã định danh nghiên cứu Số liệu chất lượng phần mềm.

  - **SystemLocale -** Ngôn ngữ mặc định của hệ điều hành

  - **SystemLocaleTag -** Ngôn ngữ mặc định của hệ điều hành

  - **TimeZoneBiasInMinutes -** Sự khác biệt về số phút giữa giờ địa phương và giờ UTC.

  - **VerticalResolution -** Độ phân giải màn hình theo chiều dọc

  - **WinUserActType -** Người dùng Windows chạy Office có phải là người quản trị viên, người dùng quyền lực hay người dùng bình thường.

### <a name="officesystemsystemhealthofficelensidentity"></a>Office.System.SystemHealthOfficeLensIdentity

Thông tin nhận dạng người dùng là cần thiết để thực hiện các yêu cầu chủ đề dữ liệu.

Các trường sau đây sẽ được thu thập:

  - **CID** - Danh tính người dùng giả danh

### <a name="officesystemsystemhealthrollbacksessionmetadata"></a>Office.System.SystemHealthRollbackSessionMetadata

Siêu dữ liệu cần thiết để cô lập một bản sao thất bại.

Các trường sau đây sẽ được thu thập:

  - **InstallMethod** - Cài đặt mới, cập nhật hoặc quay lui

  - **IsSubscription -** Liệu ứng dụng Office có được cài đặt theo giấy phép đăng ký hay không.

  - **PreviousBuild** - Phiên bản bản dựng đã được cài đặt trước đó

### <a name="officesystemsystemhealthsessionlifecycleandheartbeat"></a>Office.System.SystemHealthSessionLifecycleAndHeartbeat

Cung cấp thông tin về các số liệu trạng thái hệ thống.

Các trường sau đây sẽ được thu thập:

  - **InstallMethod** - Bản dựng hiện tại của Office đã được nâng cấp từ, quay lại hay cài đặt mới.

  - **InteractionSessionID** - Mã định danh phiên.

  - **PreviousBuild** - Phiên bản Office mà bản dựng này được nâng cấp lên hoặc quay lại từ đó.

  - **State** - Trạng thái mà phiên thay đổi thành.

  - **Thời gian** - Trỏ vào mà trạng thái phiên thay đổi.

### <a name="officesystemsystemhealthsessionstarttime"></a>Office.System.SystemHealthSessionStartTime

Được sử dụng với dữ liệu sự cố để phân tách các sự cố sớm và trễ (nghĩa là xác định xem người dùng có sử dụng ứng dụng này trong một khoảng thời gian trước khi xảy ra sự cố không

Các trường sau đây sẽ được thu thập:

  - **SessionStart** - Thời gian tại đó phép đo từ xa sẽ bắt đầu quy trình xử lý dữ liệu.

### <a name="officesystemsystemhealthungracefulappexitdesktop"></a>Office.System.SystemHealthUngracefulAppExitDesktop

Sự kiện được kích hoạt do hành động chấm dứt ứng dụng bất thường (Ví dụ: trình quản lý tác vụ bắt buộc thoát, ứng dụng bị treo, v.v.) đối với các ứng dụng máy khách Office như Word, Excel, PowerPoint và Outlook. Chúng tôi dùng các số liệu Thoát ứng dụng bất thường để đo lường trạng thái sản phẩm máy khách Office. Đây là một tín hiệu nghiệp vụ quan trọng do các kỹ sư Office sử dụng để kết luận tính ổn định của sản phẩm.

Các trường sau đây sẽ được thu thập:

  - **AffectedProcessAppBuild -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppBuildRevision -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppMajorVer** - Mã định danh phiên bản chính cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppMinorVer -** Mã định danh phiên bản phụ cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppName -** Tên của quy trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AffectedProcessExeBuildVersion -** Số phiên bản dựng của quy trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AffectedProcessExeMajorVersion -** Số phiên bản chính của quy trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AffectedProcessExeMinorVersion -** Số phiên bản phụ của quy trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AffectedProcessExeBuildVersion -** Số phiên bản của bản chỉnh sửa bản dựng của quy trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AffectedProcessIsDebug -** Quy trình bị ảnh hưởng có phải là bản dựng gỡ lỗi hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AffectedProcessIsLabMachine -** Quy trình bị ảnh hưởng có phải ở trong phòng thí nghiệm của Microsoft không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AffectedProcessOsEnvironment -** Mã định danh hệ điều hành cho quy trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AppName -** Tên ứng dụng bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **CrashedAssignedFlights -** Chuyến bay được gán cho quy trình gặp sự cố. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **CrashedConfigIds -** Cấu hình được gán cho quy trình gặp sự cố. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **CrashedEcsETag -** một mã định danh thử nghiệm cho quy trình rơi.

  - **CrashedImpressionId -** mã định danh ấn tượng của quy trình rơi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **CrashedModuleName** - Tên mô-đun lỗi

  - **CrashedProcessSessionID -** một mã định danh duy nhất của quy trình rơi. 

  - **CrashedProcessSessionInitTime -** thời gian khi bắt đầu quy trình bị ảnh hưởng. 

  - **CrashedProcessSessionUninitTime** - Thời gian khi kết thúc quy trình bị ảnh hưởng.

  - **CrashTag** - Mã định danh duy nhất cho mã của sự cố.

  - **CrashType -** Mã định danh bucketing cho loại gặp sự cố.

  - **DetectionTime -** thời gian khi việc thoát không mong muốn đã được phát hiện. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ErrorString -** Mô tả lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ExceptionAddress -** Địa chỉ trong chương trình nơi lỗi xảy ra. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ExceptionCode -** Mã định danh bucketing cho trường hợp ngoại lệ.

  - **FaultAppName -** tên của ứng dụng lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **InstallMethod** - Bản dựng hiện tại của Office đã được nâng cấp từ, quay lại hay cài đặt mới.

  - **InstallType -** Mã định danh cho phương thức mà Office được cài đặt. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **InstallTypeName -** Mã định danh cho phương thức mà Office được cài đặt. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **IsLabMachine -** Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **IsMsftInternal -** Người dùng Windows mà Office đang chạy có phải nhân viên của Microsoft hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleBaseAddress -** Địa chỉ cơ sở của mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleBuildVersion -** Số phiên bản dựng của mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleMajorVersion -** Số phiên bản chính của mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleMinorVersion -** Số phiên bản phụ của mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleName -** Tên mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleOffset -** Bù trừ tính theo byte (theo hệ thập lục phân) từ địa chỉ cơ sở nơi lỗi xảy ra.

  - **ModuleRevisionVersion -** Số phiên bản của bản chỉnh sửa bản dựng của mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleSize -** Kích cỡ mô-đun lỗi theo byte. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleVersion** - Phiên bản của mô-đun lỗi gây ra sự cố.

  - **OfficeArchitectureText** - Kiến trúc cài đặt: x64, x86, v.v.

  - **OfficeUILang** - Ngôn ngữ giao diện người dùng trong Bản dựng Office.

  - **OSEnvironment -** Mã định danh cho môi trường mà Office đang chạy.

  - **PreviousBuild** - Phiên bản bản dựng đã được cài đặt trước đó

  - **ProcessorArchitecture** - Kiến trúc bộ xử lý cho môi trường: x64, x86, v.v.

  - **SessionFlags** - Xác định các điều kiện của phiên như: tệp đã mở hay đã chỉnh sửa, tài liệu đám mây đã mở chưa, trình tự khởi động đã hoàn thành chưa, v.v. 

  - **UAETypeName -** Mã định danh bucketing cho cách ứng dụng cố ý thoát. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **UninitLibletId** - Mã định danh duy nhất cho cấu phần lỗi của sự cố.

  - **VerifyElseCrashTag -** Mã định danh duy nhất cho vị trí ứng dụng gặp sự cố. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

### <a name="officesystemsystemhealthungracefulappexitimmersive"></a>Office.System.SystemHealthUngracefulAppExitImmersive

Sử dụng để ghi lại số liệu gặp sự cố.

Các trường sau đây sẽ được thu thập:

  - **AffectedProcessAppBuild -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppBuildRevision -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppMajorVer -** Mã định danh phiên bản chính cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppMinorVer -** Mã định danh phiên bản phụ cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppName -** Tên của quy trình bị ảnh hưởng.

  - **AffectedProcessExeBuildVersion -** Số phiên bản bản dựng của quy trình bị ảnh hưởng.

  - **AffectedProcessExeMajorVersion -** Số phiên bản chính của quy trình bị ảnh hưởng.

  - **AffectedProcessExeMinorVersion -** Số phiên bản phụ của quy trình bị ảnh hưởng.

  - **AffectedProcessExeBuildVersion -** Số phiên bản bản chỉnh sửa bản dựng của quy trình bị ảnh hưởng.

  - **AffectedProcessIsDebug -** Quy trình bị ảnh hưởng có phải là một bản dựng gỡ lỗi hay không.

  - **AffectedProcessIsLabMachine -** Quy trình bị ảnh hưởng có phải ở trong phòng thí nghiệm của Microsoft không.

  - **AffectedProcessOsEnvironment -** Mã định danh hệ điều hành cho quy trình bị ảnh hưởng.

  - **AppName -** Tên ứng dụng bị ảnh hưởng.

  - **CrashedAssignedFlights -** Chuyến bay được gán cho quy trình bị rơi.

  - **CrashedConfigIds -** Cấu hình được gán cho quy trình bị rơi.

  - **CrashedImpressionId -** mã định danh ấn tượng của quy trình rơi.

  - **CrashedInteractionSessionID -** mã định danh phiên tương tác cho quá trình bị ảnh hưởng.

  - **CrashedInteractionSessionTime -** thời gian khi quy trình bị ảnh hưởng có thể tương tác.

  - **CrashedProcessSessionID -** một mã định danh duy nhất của quy trình rơi.

  - **CrashedProcessSessionInitTime -** thời gian khi bắt đầu quy trình bị ảnh hưởng.

  - **DetectionTime -** thời gian khi việc thoát không mong muốn đã được phát hiện.

  - **IsLabMachine -** Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không.

  - **IsMsftInternal -** Người dùng Windows mà Office đang chạy có phải nhân viên của Microsoft hay không.

  - **OSEnvironment -** Mã định danh cho môi trường mà Office đang chạy.

  - **PreviousLifecycleState -** Trạng thái của quá trình bị ảnh hưởng khi nó gặp sự cố.

  - **UAETypeName -** Mã định danh bucketing cho cách ứng dụng cố ý thoát.

### <a name="officesystemsystemhealthungracefulapplicationexitwin32"></a>Office.System.SystemHealthUngracefulApplicationExitWin32

Sự kiện được kích hoạt do hành động chấm dứt ứng dụng bất thường (chẳng hạn như trình quản lý tác vụ bắt buộc thoát, ứng dụng bị treo, v.v.) đối với các ứng dụng máy khách Office như Word, Excel, PowerPoint, Outlook và một số ứng dụng khác. Chúng tôi dùng các số liệu Thoát ứng dụng bất thường để đo lường trạng thái sức khoẻ của sản phẩm máy khách Office. Đây là một tín hiệu nghiệp vụ quan trọng do các kỹ sư Office sử dụng để kết luận tính ổn định của sản phẩm.

Các trường sau đây sẽ được thu thập:

  - **AddinExecution** - Cờ thông báo nếu phần bổ trợ đang thực thi và không hoàn thành trong quá trình thoát ứng dụng không đáng tin cậy. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **AppUsedVirtualMemory** - Bộ nhớ ảo được sử dụng bởi ứng dụng Office

  - **BootCompleted** - Khởi động Office đã hoàn tất tại thời điểm gặp sự cố chưa. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **BucketId** - Mã định danh bucket Watson cho sự cố
 
  - **CabGuid** - Mã định danh nhận dạng chung duy nhất (GUID) cho taxi Watson.

  - **CrashedAppBuild** - Mã định danh phiên bản dựng cho quá trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **CrashedAppMajor** - Mã định danh phiên bản chính cho quá trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*
 
  - **CrashedAppMinor** - Mã định danh phiên bản phụ cho quá trình bị ảnh hưởng. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **CrashedAppVersion** - Mã định danh phiên bản ứng dụng cho quá trình gặp sự cố.

  - **CrashedEcsETag** - Mã định danh thử nghiệm cho quá trình gặp sự cố.

  - **CrashedModuleName** - Tên mô-đun lỗi.

  - **CrashedProcessSessionId** - Mã định danh duy nhất của quá trình gặp sự cố.

  - **CrashedProcessSessionInitTime** - Thời gian khi bắt đầu quy trình bị ảnh hưởng.

  - **CrashedProcessSessionUninitTime** - Thời gian khi kết thúc quy trình bị ảnh hưởng.

  - **CrashTag** - Mã định danh duy nhất cho mã của sự cố.

  - **CrashTime** - Thời gian cho biết máy khách bị chấm dứt một cách không đáng tin cậy. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **CrashType** - Mã định danh bucketing cho loại sự cố.

  - **DetectionTime** - Thời điểm phát hiện thoát ra không mong muốn. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ExceptionAddress** - địa chỉ trong chương trình nơi lỗi xảy ra. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ExceptionCode** - Mã định danh bucketing cho trường hợp ngoại lệ.

  - **ExceptionInfo** - Thông tin hệ thống cho trường hợp ngoại lệ.

  - **HandOff** - Người dùng đã tạo và chuyển quy trình Office sang phiên mới hay chưa. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HangTypeCode** - Cho biết hình thức bị treo nếu quá trình bị treo trong khi thực thi.

  - **HasEdit** - Người dùng có đang chỉnh sửa tài liệu trong máy khách gặp sự cố hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HasOpen** - Có tài liệu đã mở trong máy khách gặp sự cố hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HexCrashTag** - Mã định danh duy nhất cho mã của sự cố. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HexExceptionAddress** - Địa chỉ theo hệ thập lục phân trong chương trình nơi xảy ra lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HexExceptionCode** - Mã định danh theo hệ thập lục phân cho trường hợp ngoại lệ. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HexModuleBaseAddress** - Địa chỉ cơ sở theo hệ thập lục phân của mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HexModuleOffset** - Bù trừ tính theo byte (theo hệ thập lục phân) từ địa chỉ cơ sở nơi lỗi xảy ra. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleSize** - Kích cỡ mô-đun lỗi theo byte theo hệ thập lục phân. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HexVerifyElseCrashTag** - Mã định danh duy nhất theo hệ thập lục phân cho vị trí ứng dụng gặp sự cố. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **InstallMethod** - Phiên bản dựng hiện tại của Office đã được nâng cấp, hạ cấp hay cài đặt mới.

  - **IsLabMachine** - Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleBaseAddress** - Địa chỉ cơ sở của mô-đun lỗi. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **HexModuleOffset** - Bù trừ tính theo byte (theo hệ thập lục phân) từ địa chỉ cơ sở nơi lỗi xảy ra.

  - **ModuleSize** - Kích cỡ mô-đun lỗi theo byte. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **ModuleStamp** - Dấu mô-đun lỗi.

  - **ModuleVersion** - Phiên bản của mô-đun lỗi gây ra sự cố.

  - **OfficeArchitectureText** - Kiến trúc sản phẩm Office dưới dạng chuỗi (ví dụ: x86, arm).

  - **OfficeUiLang** - Ngôn ngữ giao diện người dùng trong bản dựng Office.

  - **PreviousBuild** - Phiên bản dựng đã được cài đặt trước đó

  - **ProcessorArchitecture** - Kiến trúc bộ xử lý cho môi trường x64, x86, v.v.

  - **SafeMode** - Phiên có được khởi động ở chế độ an toàn hay không. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **SessionFlags** - Xác định các điều kiện của phiên như: tệp đã mở hay đã chỉnh sửa, tài liệu đám mây đã mở chưa, trình tự khởi động đã hoàn thành chưa, v.v. 

  - **StackHash** - Cung cấp ID dạng băm cho ngăn xếp lỗi trong Office.

  - **SystemAvailableMemory** - Bộ nhớ có sẵn trong hệ điều hành

  - **UAEOSEnvironment** - Mã định danh môi trường của hệ điều hành. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **UninitLibletId** - Mã định danh duy nhất cho cấu phần lỗi của sự cố.

  - **VerifyElseCrashTag** - Mã định danh duy nhất cho vị trí ứng dụng gặp sự cố. *[Trường này đã bị loại bỏ khỏi các bản dựng hiện tại của Office, nhưng vẫn có thể xuất hiện trong các bản dựng cũ hơn.]*

  - **WatsonReportId** - Mã định danh của báo cáo được gửi đến dịch vụ Windows Watson.

  - **WerEventCreatedTime** - Dấu thời gian cho sự kiện Báo cáo Lỗi Windows.


### <a name="officesystemungracefulapplicationexitdesktopappexit"></a>Office.System.UngracefulApplicationExit.DesktopAppExit

Sử dụng để ghi lại số liệu gặp sự cố.

Các trường sau đây sẽ được thu thập:

  - **AppBuildVersion -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

  - **AppMajorVersion -** Số phiên bản chính của quy trình bị ảnh hưởng.

  - **AppMinorVersion -** Mã định danh phiên bản phụ cho quá trình bị ảnh hưởng.

  - **AppName -** Tên ứng dụng bị ảnh hưởng.

  - **AppRevisionVersion -** Mã định danh phiên bản chỉnh sửa bản dựng cho quá trình bị ảnh hưởng.

  - **CrashedAssignedFlights -** Chuyến bay được gán cho quy trình bị rơi.

  - **CrashedConfigIds -** Cấu hình được gán cho quy trình bị rơi.

  - **CrashedImpressionId -** mã định danh ấn tượng của quy trình rơi.

  - **CrashedInteractionSessionId -** mã định danh phiên tương tác cho quá trình bị ảnh hưởng.

  - **CrashedProcessSessionId -** một mã định danh duy nhất của quy trình rơi.

  - **CrashType -** Mã định danh bucketing cho loại gặp sự cố.

  - **ErrorString -** mô tả lỗi.

  - **ExceptionAddress -** địa chỉ trong chương trình nơi lỗi xảy ra.

  - **ExceptionCode -** Mã định danh bucketing cho trường hợp ngoại lệ.

  - **FaultAppName -** tên của ứng dụng lỗi.

  - **InstallMethod** - Bản dựng hiện tại của Office đã được nâng cấp từ, quay lại hay cài đặt mới.

  - **InstallType -** Mã định danh cho phương thức mà Office được cài đặt.

  - **IsDebug -** Liệu đây có phải là bản dựng gỡ lỗi của Office hay không.

  - **IsHandledCrash -** Bộ xử lý gặp sự cố có được được thu hồi và bị rơi hay khôngo phiên.

  - **IsLabMachine -** Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không.

  - **ModuleBaseAddress -** các địa chỉ cơ sở của mô-đun lỗi.

  - **ModuleName -** Tên mô-đun lỗi.

  - **ModuleOffset -** Bù trừ theo byte từ địa chỉ cơ sở nơi lỗi xảy ra.

  - **ModuleSize -** Kích cỡ mô-đun lỗi theo byte.

  - **OSEnvironment -** Mã định danh cho môi trường mà Office đang chạy.

  - **PreviousBuild** - Phiên bản bản dựng đã được cài đặt trước đó

  - **PreviousInteractionSessionTime -** Thời gian bắt đầu phiên tương tác trước đó.

  - **PreviousLifecycleState -** Mã định danh trạng thái vòng đời phiên trước đó.

  - **PreviousSessionInitTime -** giờ khi bắt đầu phiên trước đó.

  - **StackHash -** một mã định danh cho biết vị trí trong mã mà quá trình bị ảnh hưởng gặp sự cố.

  - **VerifyElseCrashTag -** Mã định danh duy nhất cho vị trí ứng dụng gặp sự cố.

### <a name="officesystemuserchangeddiagnosticlevel"></a>Office.System.UserChangedDiagnosticLevel

Thông tin cần thiết để đảm bảo các lựa chọn chính sách bảo mật của người dùng đang được thi hành.

Các trường sau đây sẽ được thu thập:

  - **DiagnosticLevelChanged**: Cho biết rằng người dùng đã thay đổi mức độ chẩn đoán của họ.

  - **NewDiagnosticLevel**: cấp độ sau khi người dùng thay đổi.

  - **OldDiagnosticLevel**: cấp độ người dùng đã sử dụng trước khi thay đổi của họ.

### <a name="officetelemetryariaeventsinkhandlemsadevicetokenresponse"></a>Office.Telemetry.AriaEventSink.HandleMsaDeviceTokenResponse

Tín hiệu của sự cố nào trong dịch vụ Tài khoản Microsoft.

Các trường sau đây sẽ được thu thập:

  - **RetryCount** - Số lượng thử lại kết nối với dịch vụ MSA.

### <a name="officetelemetryariaeventsinkrequestmsadevicetoken"></a>Office.Telemetry.AriaEventSink.RequestMsaDeviceToken

Tín hiệu của sự cố nào trong dịch vụ Tài khoản Microsoft.

Các trường sau đây sẽ được thu thập:

  - **RetryCount** - Số lượng thử lại kết nối với dịch vụ tài khoản Microsoft.

### <a name="officetelemetryclientsamplingoverridden"></a>Office.Telemetry.ClientSamplingOverridden

Bắt buộc cần có tỷ lệ tái tạo phù hợp. Bình thường không áp dụng cho nhóm người xem Sản xuất.

Các trường sau đây sẽ được thu thập:

  - **OverriddenMeasureEnabled** - Máy khách có được đặt để gửi nhiều hơn các sự kiện không được lấy mẫu không

  - **OverriddenNumberlinePosition** - Vị trí số dòng mới để lấy mẫu

  - **OverriddenReportedSampleRate** - Tỷ lệ lấy mẫu được báo cáo mới

  - **OverriddenSampleRate** - Tỷ lệ lấy mẫu mới

  - **PreviousNumberlinePosition** - Vị trí lấy mẫu trên dòng số.

  - **PreviousSampleRate** - Tỷ lệ lấy mẫu trước khi bị ghi đè.

  - **WasMeasureEnabled** - Máy khách có được đặt để gửi nhiều hơn các sự kiện không được lấy mẫu không

### <a name="officetelemetrycomplianceeventnotinbasicallowlist"></a>Office.Telemetry.Compliance.EventNotInBasicAllowList

Báo cáo triển khai hoặc thực hiện phép đo từ xa không hợp lệ

Các trường sau đây sẽ được thu thập:

  - **EventName** - Tên sự kiện không có trong danh sách

### <a name="officetelemetrycompliancemissingdatacategory"></a>Office.Telemetry.Compliance.MissingDataCategory

Báo cáo triển khai hoặc thực hiện phép đo từ xa không hợp lệ

Các trường sau đây sẽ được thu thập:

  - **EventName** - Tên sự kiện thiếu một danh mục

  - **IsFromRule** - Sự kiện có bắt nguồn từ một quy tắc phép đo từ xa hay không

### <a name="officetelemetrycompliancemissingdatacategoryinrule"></a>Office.Telemetry.Compliance.MissingDataCategoryInRule

Báo cáo triển khai hoặc thực hiện phép đo từ xa không hợp lệ

Các trường sau đây sẽ được thu thập:

  - **RuleId** - ID quy tắc thiếu một danh mục dữ liệu

  - **RuleVersion** - Phiên bản quy tắc thiếu một danh mục dữ liệu

### <a name="officetelemetrydiagnosticdataviewerstatechanged"></a>Office.Telemetry.DiagnosticDataViewerStateChanged

Xác thực rằng người tiêu dùng có thể xem dữ liệu khi nó rời khỏi máy của họ bằng Trình xem dữ liệu chẩn đoán.

Các trường sau đây sẽ được thu thập:

  - **Dialogcanceled** - Hộp thoại Trình xem dữ liệu chẩn đoán có bị hủy bỏ hay không

  - **NewState** - Trạng thái Trình xem dữ liệu chẩn đoán mới

  - **DialogCancelled** - Hộp thoại Trình xem dữ liệu chẩn đoán có được sử dụng hay không

### <a name="officetelemetrydynamicconfigfetchconfigs"></a>Office.Telemetry.DynamicConfig.FetchConfigs

Dữ liệu cần để đánh giá tình trạng Dịch vụ cấu hình phép đo từ xa.

Các trường sau đây sẽ được thu thập:

  - **ParsedConfigCount** - Số lượng cấu hình động được phân tích

  - **ParsedConfigs** - Số lượng cấu hình động được phân tích

  - **RejectedConfigCount** - Số lượng cấu hình động bị từ chối

  - **RejectedConfigs** - Số lượng cấu hình động bị từ chối

  - **RejectedConfigsList** - Danh sách các cấu hình bị từ chối được phân tách bằng dấu phẩy.

### <a name="officetelemetrydynamicconfigparsejsonconfig"></a>Office.Telemetry.DynamicConfig.ParseJsonConfig

Dữ liệu cần để đánh giá tình trạng Dịch vụ cấu hình phép đo từ xa

Các trường sau đây sẽ được thu thập:

  - **ErrorMessage** - Phân tích thông báo lỗi

  - **NodeName** - Nút mà quá trình phân tích không thành công

### <a name="officetelemetrydynamicconfigpopulatedrequestignored"></a>Office.Telemetry.DynamicConfig.PopulatedRequestIgnored

Sự kiện này được tạo ra khi chúng tôi không thể thiết lập đường ống dẫn cấu hình đo từ xa.

Sự kiện này không thu thập trường nào.

### <a name="officetelemetrydynamicconfigpopulatetreecalledagain"></a>Office.Telemetry.DynamicConfig.PopulateTreeCalledAgain

Dữ liệu cần để đánh giá tình trạng Dịch vụ cấu hình phép đo từ xa.

Sự kiện này không thu thập trường nào.

### <a name="officetelemetryeventquarantined"></a>Office.Telemetry.EventQuarantined

Sử dụng để xác minh các sự kiện NSD khác đang hoạt động đúng cách.

Các trường sau đây sẽ được thu thập:

  - **EventName** - Tên sự kiện đã cách ly

  - **Reason** - Lý do cách ly

### <a name="officetelemetryflusheventbuffer"></a>Office.Telemetry.FlushEventBuffer 

Báo cáo kích thước bộ đệm sự kiện và có thể chỉ ra lỗi phép đo từ xa liên quan đến việc sử dụng bộ đệm lớn.

Các trường sau đây sẽ được thu thập:

  - **EventCount** - Số lượng sự kiện trong bộ đệm

  - **FirstPassCount** - Số lần vượt qua đầu tiên của sự kiện

  - **SecondPassCount** - Số lần vượt qua thứ hai của sự kiện

### <a name="officetelemetrygetfilteredpayloadsfromdisk"></a>Office.Telemetry.GetFilteredPayloadsFromDisk

Xác nhận một số phần nhất định của quy trình phép đo từ xa kế thừa đang hoạt động trên các nền tảng vẫn sử dụng nó.

Sự kiện này không thu thập trường nào.

### <a name="officetelemetryinvaliddatacontractname"></a>Office.Telemetry.InvalidDataContractName

Báo cáo triển khai hoặc thực hiện phép đo từ xa không hợp lệ

Các trường sau đây sẽ được thu thập:

  - **DataContractName** - Tên của hợp đồng dữ liệu phép đo từ xa

  - **EventName** - Tên của sự kiện có hợp đồng dữ liệu không hợp lệ

  - **IsRuleEvent** - Việc sự kiện này được thực hiện bằng một quy tắc phép đo từ xa là đúng hay sai

### <a name="officetelemetryinvaliddatafieldname"></a>Office.Telemetry.InvalidDataFieldName 

Báo cáo triển khai hoặc thực hiện phép đo từ xa không hợp lệ

Các trường sau đây sẽ được thu thập:

  - **DataFieldName** - Tên của trường dữ liệu phép đo từ xa

  - **EventName** - Tên của sự kiện có trường không hợp lệ

  - **IsRuleEvent** - Việc sự kiện này được thực hiện bằng một quy tắc phép đo từ xa là đúng hay sai.

### <a name="officetelemetryinvalideventcontractname"></a>Office.Telemetry.InvalidEventContractName 

Báo cáo triển khai hoặc thực hiện phép đo từ xa không hợp lệ

Các trường sau đây sẽ được thu thập:

  - **EventContractName** - Tên hợp đồng phép đo từ xa không hợp lệ

  - **EventName** - Tên của sự kiện có tên hợp đồng dữ liệu không hợp lệ

  - **IsRuleEvent** - Việc sự kiện này được thực hiện bằng một quy tắc phép đo từ xa là đúng hay sai

### <a name="officetelemetryloadxmlrules"></a>Office.Telemetry.LoadXmlRules

Báo cáo liệu quá trình phân tích quy tắc phép đo từ xa đã thành công hay chưa

Các trường sau đây sẽ được thu thập:

  - **DetachedDuration** - Khoảng thời lượng được tách ra tính bằng micrô giây

### <a name="officetelemetrymissingfielddetails"></a>Office.Telemetry.MissingFieldDetails

Báo cáo thông tin trường bị thiếu để chẩn đoán lỗi chính tả trong cấu hình phép đo từ xa.

Các trường sau đây sẽ được thu thập:

  - **ErrorRuleId** - ID quy tắc phép đo từ xa yêu cầu trường bị thiếu

  - **ErrorRuleVersion** - Phiên bản quy tắc phép đo từ xa yêu cầu trường bị thiếu

  - **EtwEventGuid** - ETW GUID của trường được yêu cầu

  - **EtwEventGuid** - ID sự kiện ETW của trường được yêu cầu

  - **MissingFieldName** - Tên trường được yêu cầu

  - **UlsTagId** - Thẻ mã của trường bị thiếu

### <a name="officetelemetryprocessidlequeuejob"></a>Office.Telemetry.ProcessIdleQueueJob

Báo cáo rằng việc xử lý phép đo từ xa không hoạt động đã bắt đầu như mong đợi.

Các trường sau đây sẽ được thu thập:

  - **DetachedDuration** - Khoảng thời lượng được tách ra tính bằng micrô giây

  - **FailureDiagnostic** - Các thao tác không thành công

### <a name="officetelemetryredstoneinboxsampling"></a>Office.Telemetry.RedstoneInboxSampling

Trạng thái lấy mẫu của máy khách được yêu cầu để giải thích chính xác các số liệu khác.

Các trường sau đây sẽ được thu thập:

  - **MeasuresEnabled** - Các biện pháp có được kích hoạt trong phiên này hay không?

  - **SamplingClientIdValue** - Giá trị lấy mẫu cho máy khách này

  - **SamplingKey** - Khóa lấy mẫu cho máy khách này

  - **SamplingMethod** - Phương pháp lấy mẫu cho máy khách này

### <a name="officetelemetryredstoneinboxsamplingcritical"></a>Office.Telemetry.RedstoneInboxSamplingCritical

Trạng thái lấy mẫu của máy khách được yêu cầu để giải thích chính xác các số liệu khác.

Các trường sau đây sẽ được thu thập:

  - **MeasuresEnabled** - Các biện pháp có được kích hoạt trong phiên này hay không?

  - **SamplingClientIdValue** - Giá trị lấy mẫu cho máy khách này

  - **SamplingKey** - Khóa lấy mẫu cho máy khách này

  - **SamplingMethod** - Phương pháp lấy mẫu cho máy khách này

### <a name="officetelemetryruleerrorsaggregated"></a>Office.Telemetry.RuleErrorsAggregated

Báo cáo lỗi trạng thái phép đo từ xa. Bắt buộc để xác thực dữ liệu khác (bao gồm NSD).

Các trường sau đây sẽ được thu thập:

  - **ErrorCount** - Số lượng lỗi này trong cửa sổ thời gian tổng hợp

  - **ErrorInfo** - Số thông tin chẩn đoán lỗi

  - **ErrorRuleId** - ID quy tắc phép đo từ xa gây ra lỗi

  - **ErrorRuleVersion** - Phiên bản quy tắc phép đo từ xa gây ra lỗi

  - **WarningInfo** - Số thông tin chẩn đoán cảnh báo

  - **QueueFlushCount** - Số lượng lần xóa hàng đợi

  - **QueueFlushDueToSizeLimit** - Kích cỡ tại nơi mà phép đo từ xa xóa hàng đợi

  - **QueueFlushesDueToSize** - Số lượng lần xóa hàng đợi xảy ra do kích cỡ bộ đệm

  - **QueueHardLimit** - Giới hạn tắt phép đo từ xa

  - **QueueLimitHitTime** - Thời điểm đạt giới hạn tắt

  - **ResultTime** - Thời gian của sự kiện này

### <a name="officetelemetryrulesenginediskthrottled"></a>Office.Telemetry.RulesEngineDiskThrottled

Điều chỉnh số liệu DQ. Bắt buộc để có được độ chính xác trong tất cả các dữ liệu khác.

Các trường sau đây sẽ được thu thập:

  - **DiskWriteLimit** - Giới hạn kích cỡ ổ đĩa cho dữ liệu phép đo từ xa

  - **DiskWriteTotal** -Tổng số đĩa ghi cho dữ liệu phép đo từ xa

  - **SessionDiskWriteTotal** - Tổng số phiên ghi đĩa cho dữ liệu phép đo từ xa

  - **ThrottlingTimestamp** - Thời gian phiên được tiết lưu

### <a name="officetelemetryrulesenginemediumcostthrottled"></a>Office.Telemetry.RulesEngineMediumCostThrottled

Điều chỉnh số liệu DQ. Bắt buộc để có được độ chính xác trong tất cả các dữ liệu khác.

Sự kiện này không thu thập trường nào.

### <a name="officetelemetryrulesenginespikethrottled"></a>Office.Telemetry.RulesEngineSpikeThrottled

Điều chỉnh số liệu DQ. Bắt buộc để có được độ chính xác trong tất cả các dữ liệu khác.

Các trường sau đây sẽ được thu thập:

  - **CurrentLimit** - Giới hạn lưu trữ tạm văn bản theo nhóm hiện tại

  - **Duration** - Khoảng thời gian lưu trữ tạm văn bản theo nhóm

  - **Factor** - Yếu tố lưu trữ tạm văn bản theo nhóm

  - **HighestImpactingRuleBytes** - Số lượng byte nhiều nhất được ghi lại bằng một quy tắc phép đo từ xa

  - **HighestImpactingRuleId** - ID quy tắc ghi lại số lượng byte nhiều nhất

  - **HighestImpactingRuleVersion** - Phiên bản quy tắc ghi lại số lượng byte nhiều nhất

  - **MaxLimit** - Giới hạn tối đa

  - **ThrottlingTimestamp** - Khi phép đo từ xa được tiết lưu

### <a name="officetelemetryrulesenginethrottled"></a>Office.Telemetry.RulesEngineThrottled

Điều chỉnh số liệu DQ. Bắt buộc để có được độ chính xác trong tất cả các dữ liệu khác.

Các trường sau đây sẽ được thu thập:

  - **ThrottlingTimestamp** - Thời điểm phép đo từ xa được tiết lưu

### <a name="officetelemetryrulesengineulsqueuesizebackgroundprocessinglevelreached"></a>Office.Telemetry.RulesEngineUlsQueueSizeBackgroundProcessingLevelReached

Báo cáo rằng hiện đang có quá nhiều sự kiện trong hàng đợi để xử lý trong thời gian ứng dụng không hoạt động.

Các trường sau đây sẽ được thu thập:

  - **BackgroundProcessingLevelInBytes** - Kích cỡ hàng đợi để bắt đầu xử lý trong nền.

  - **CurrentQueueSize** - Số lượng sự kiện trong hàng đợi nULS.

  - **CurrentQueueSizeInBytes** - Kích cỡ hàng đợi nULS bằng byte.

  - **ReachedTimestamp** - Thời điểm bắt đầu xử lý nền.

### <a name="officetelemetryrulesresultuploadlatencyrule"></a>Office.Telemetry.RulesResultUploadLatencyRule

Độ trễ tải lên trung bình, tối thiểu và tối đa của tải trọng kết quả quy tắc tải lên mỗi giờ

Các trường sau đây sẽ được thu thập:

  - **AverageLatency** - Độ trễ tải lên trung bình.

  - **CollectionTime** - Thời gian khi dữ liệu tải lên quy tắc được thu thập.

  - **LatencyGE201LE400** - Số lượng tải lên có độ trễ lớn hơn hoặc bằng 201ms và nhỏ hơn hoặc bằng 400ms

  - **LatencyGE3001** - Số lượng tải lên có độ trễ lớn hơn hoặc bằng 3001ms.

  - **LatencyGE401LE600** - Số lượng tải lên có độ trễ lớn hơn hoặc bằng 401ms và nhỏ hơn hoặc bằng 600ms.

  - **LatencyGE601LE800** - Số lượng tải lên có độ trễ lớn hơn hoặc bằng 601ms và nhỏ hơn hoặc bằng 800ms.

  - **LatencyLE200** - Số lượng tải lên có độ trễ nhỏ hơn 200 mili giây.

  - **MaxLatency** - Độ trễ cao nhất được quan sát.

  - **MaxLatency** - Độ trễ thấp nhất được quan sát.

### <a name="officetelemetrysamplingpolicy"></a>Office.Telemetry.SamplingPolicy

Trạng thái lấy mẫu của máy khách được yêu cầu để giải thích chính xác các số liệu khác.

Các trường sau đây sẽ được thu thập:

  - **MeasuresEnabled** - Các biện pháp có được kích hoạt trong phiên này hay không?

  - **SamplingClientIdValue** - Giá trị lấy mẫu cho máy khách này

  - **SamplingKey** - Khóa lấy mẫu cho máy khách này

  - **SamplingMethod** - Phương pháp lấy mẫu cho máy khách này

### <a name="officetelemetrysamplingpolicyeventtrigger"></a>Office.Telemetry.SamplingPolicyEventTrigger

Trạng thái lấy mẫu của máy khách được yêu cầu để giải thích chính xác các số liệu khác.

Các trường sau đây sẽ được thu thập:

  - **MeasuresEnabled** - Các biện pháp có được kích hoạt trong phiên này hay không?

  - **SamplingKey** - Khóa lấy mẫu cho máy khách này

  - **SamplingMethod** - Phương pháp lấy mẫu cho máy khách này

### <a name="officetelemetrysessiontelemetryruleschanged"></a>Office.Telemetry.SessionTelemetryRulesChanged

Báo cáo về tập hợp các quy tắc phép đo từ xa đã thay đổi

Các trường sau đây sẽ được thu thập:

  - **ChangedRuleId** - ID quy tắc phép đo từ xa đã thay đổi trong bản cập nhật hiện tại

  - **ChangedRuleVersion** - Phiên bản quy tắc phép đo từ xa đã thay đổi trong bản cập nhật hiện tại

  - **OperationType** - Thêm hoặc loại bỏ thẻ thao tác

### <a name="officetelemetrysessiontelemetryrulescount"></a>Office.Telemetry.SessionTelemetryRulesCount

Báo cáo số lượng quy tắc phép đo từ xa được tải

Các trường sau đây sẽ được thu thập:

  - **CountOfLoadedRules** - Số lượng quy tắc phép đo từ xa được tải

  - **HadRuleFileAtBoot** - Có một tệp quy tắc phép đo từ xa khi khởi động ứng dụng không

### <a name="officetelemetrysessiontelemetryrulesinitialstate"></a>Office.Telemetry.SessionTelemetryRulesInitialState

Báo cáo quy tắc phép đo từ xa đã được tải khi bắt đầu phiên

Các trường sau đây sẽ được thu thập:

  - **HadRuleFileAtBoot** - Có một tệp quy tắc phép đo từ xa khi khởi động ứng dụng không

  - **LoadedRulesCount** - Số lượng quy tắc phép đo từ xa được tải

  - **LoadedRulesList** - Danh sách các quy tắc phép đo từ xa được tải

### <a name="officetelemetrysystemhealthmetadatanetworkcost"></a>Office.Telemetry.SystemHealthMetadataNetworkCost

Chi phí mạng cho thấy khả năng chúng tôi có nhận được dữ liệu hay không.

Các trường sau đây sẽ được thu thập:

  - **NetworkCost** - Chi phí gói dữ liệu theo lưu lượng sử dụng hoặc không theo lưu lượng sử dụng của mạng mới

  - **OldNetworkCost** - Chi phí gói dữ liệu theo lưu lượng sử dụng hoặc không theo lưu lượng sử dụng của mạng trước đó

  - **Tag** - Thẻ mã nguồn đã phát hiện sự thay đổi

### <a name="officetelemetrysystemhealthmetadatanetworkcostchange"></a>Office.Telemetry.SystemHealthMetadataNetworkCostChange

Chi phí mạng cho thấy khả năng chúng tôi có nhận được dữ liệu hay không.

Các trường sau đây sẽ được thu thập:

  - **NewNetworkCost** - Chi phí gói dữ liệu theo lưu lượng sử dụng hoặc không theo lưu lượng sử dụng của mạng mới

  - **OldNetworkCost** - Chi phí gói dữ liệu theo lưu lượng sử dụng hoặc không theo lưu lượng sử dụng của mạng trước đó

  - **Tag** - Thẻ mã nguồn đã phát hiện sự thay đổi

### <a name="officetelemetrytelemetryactivityaggregationwindowstatistics"></a>Office.Telemetry.TelemetryActivityAggregationWindowStatistics

Báo cáo số lượng nhóm hoạt động tổng hợp và phiên bản trong mỗi hoạt động được tải lên.

Các trường sau đây sẽ được thu thập:

  - **GroupCount** - Số lượng các hoạt động tổng hợp gửi dữ liệu.

  - **InstancesToSend** - Số lượng các phiên bản hoạt động tổng hợp gửi dữ liệu.

### <a name="officetelemetrytelemetryulsqueueusage"></a>Office.Telemetry.TelemetryUlsQueueUsage

Báo cáo lỗi trạng thái phép đo từ xa. Bắt buộc để xác thực dữ liệu khác (bao gồm NSD).

Các trường sau đây sẽ được thu thập:

  - **AverageEventCount** - Số lượng sự kiện trung bình trong hàng đợi

  - **AverageQueueCB** - Kích cỡ bộ nhớ trung bình của hàng đợi

  - **PeakEventCount** - Số lượng sự kiện cao nhất của hàng đợi

  - **PeakQueueCB** - Kích cỡ bộ nhớ cao nhất của hàng đợi

  - **QueueDisableRuleLimit** - Giới hạn mà tại đó các quy tắc phép đo từ xa bị vô hiệu hóa

### <a name="officetelemetryulsqueuetopthrottlingtags"></a>Office.Telemetry.UlsQueueTopThrottlingTags

Báo cáo các thẻ hàng đầu đã đóng góp cho hàng đợi ULS bị tắt.

Các trường sau đây sẽ được thu thập:

  - **Tag0 -** Thẻ tiêu thụ nhiều hàng đợi nhất

  - **Tag0Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag0

  - **Tag1 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ hai

  - **Tag10 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 11

  - **Tag10Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag10

  - **Tag11 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 12

  - **Tag11Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag11

  - **Tag12 -** Thẻ tiêu thụ nhiều hàng đợi cao thứ 13

  - **Tag12Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag12

  - **Tag13 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 14

  - **Tag13Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag13

  - **Tag14 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 15

  - **Tag14Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag14

  - **Tag1Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag1

  - **Tag2 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ hai

  - **Tag2Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag2

  - **Tag3 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 4

  - **Tag3Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag3

  - **Tag4 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 5

  - **Tag4Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag4

  - **Tag5 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 6

  - **Tag5Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag5

  - **Tag6 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 7

  - **Tag6Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag6

  - **Tag7 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 8

  - **Tag7Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag7

  - **Tag8 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 9

  - **Tag8Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag8

  - **Tag9 -** Thẻ tiêu thụ số lượng hàng đợi cao thứ 10

  - **Tag9Percent -** Tỷ lệ phần trăm hàng đợi được sử dụng bởi tag9

### <a name="officetelemetryvolumetrackingdata"></a>Office.Telemetry.VolumeTrackingData

Số liệu theo dõi số lượng sự kiện cho các sự kiện phép đo từ xa

Các trường sau đây sẽ được thu thập:

  - **EventThreshold** - Số lượng phiên bản tối đa của một sự kiện có thể được gửi trong một cửa sổ thời gian.

  - **HighestEventCount** - Số lượng phiên bản cao nhất của một sự kiện đã gửi cửa sổ này.

  - **HighestEventName** - Tên của sự kiện có số lượng phiên bản cao nhất trong cửa sổ này.

  - **TimeWindowInSeconds** - Khoảng thời gian của cửa sổ tính bằng giây.

  - **TotalEvents** - Tổng số sự kiện được gửi trong cửa sổ.

  - **UniqueEvents** - Số lượng các sự kiện duy nhất được gửi trong một cửa sổ.

### <a name="officetelemetrywritepayloadstodisk"></a>Office.Telemetry.WritePayloadsToDisk

Xác nhận một số phần nhất định của quy trình kế thừa đang hoạt động trên các nền tảng vẫn sử dụng nó.

Các trường sau đây sẽ được thu thập:

  - **DetachedDuration** - Khoảng thời lượng được tách ra tính bằng micrô giây
