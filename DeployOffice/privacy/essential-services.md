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
ms.openlocfilehash: 14b2426d021e5c559cabd3c969f80df9131cc9b9
ms.sourcegitcommit: 22ae0005d3106ff02949fb613b82e0245abfa49f
ms.translationtype: HT
ms.contentlocale: vi-VN
ms.lasthandoff: 07/22/2019
ms.locfileid: "35817992"
---
# <a name="essential-services-for-office"></a>Dịch vụ cần thiết cho Office

> [!IMPORTANT]
> Thông tin trong bài viết này áp dụng cho Phiên bản 1904 trở lên của phần mềm máy khách Office sau được cài đặt trên máy tính chạy Windows:
> - Office 365 Business và Office 365 ProPlus.
> - Office 365 Personal, Office 365 Home hoặc các phiên bản Office khác là một phần của đăng ký Office 365.
> - Project và Visio đi kèm với một số gói đăng ký, chẳng hạn như gói Project Online Professional hoặc Visio Online Plan 2.


Office bao gồm các ứng dụng phần mềm máy khách và các trải nghiệm được kết nối được thiết kế để cho phép bạn tạo, giao tiếp và cộng tác hiệu quả hơn. Mặc dù bạn có thể kiểm soát nhiều trải nghiệm được kết nối có sẵn cho bạn hoặc cho người dùng của bạn nếu bạn là người quản trị trong tổ chức của mình, nhưng vẫn có một bộ dịch vụ rất cần thiết cho cách thức Office làm việc và do đó nó không thể bị vô hiệu hóa. Ví dụ: dịch vụ cấp phép xác nhận bạn được cấp phép sử dụng Office đúng cách. Dữ liệu dịch vụ bắt buộc về các dịch vụ này sẽ được thu thập và gửi đến Microsoft mà không phụ thuộc vào bất cứ thiết đặt chính sách liên quan nào khác mà bạn đã đặt cấu hình. Bạn có thể xem dữ liệu này bằng cách sử dụng Trình xem dữ liệu chẩn đoán.

Để biết thêm thông tin, hãy xem các nguồn sau:

- [Dữ liệu dịch vụ bắt buộc cho Office](required-service-data.md)
- [Sử dụng Trình xem chẩn đoán dữ liệu với Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)
- [Các trải nghiệm kết nối trong Office](connected-experiences.md)

Nếu bạn là người quản trị cho tổ chức của bạn, bạn cũng có thể quan tâm đến những điều sau:

- [Tổng quan về kiểm soát quyền riêng tư cho Office 365 ProPlus](overview-privacy-controls.md)
- [Sử dụng thiết đặt chính sách để quản lý kiểm soát quyền riêng tư cho Office 365 ProPlus](manage-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Danh sách các dịch vụ cần thiết cho Office 

Bảng sau đây cung cấp danh sách các dịch vụ cần thiết cho Office và mô tả của từng dịch vụ.

| **Service**  | **Mô tả**  |
| ------ | ---- |
| [Xác thực](#authentication-events) | Xác thực là một dịch vụ đa nền tảng xác thực danh tính người dùng Office của bạn. Nó là điều bắt buộc để cho phép bạn đăng nhập vào Office, kích hoạt giấy phép Office, truy nhập các tệp được lưu trữ trên đám mây và cung cấp trải nghiệm nhất quán trên các phiên Office và thiết bị của bạn.    |
| [Click-to-Run](#click-to-run-events) | Click-to-Run là công nghệ cài đặt được sử dụng để cài đặt và cập nhật Office trên Windows. Công nghệ này kiểm tra các phiên bản mới của Office và tải xuống và cài đặt khi có phiên bản mới.Click-to-Run sẽ phát hiện nhu cầu, thực hiện tải xuống và cài đặt các bản cập nhật Office, bao gồm các bản cập nhật bảo mật.     |
| [Dịch vụ cấu hình nâng cao (ECS)](#enhanced-configuration-service-ecs-events) | ECS cung cấp cho Microsoft khả năng cấu hình lại các bản cài đặt Office mà không cần bạn phải triển khai lại Office. Dịch vụ này được sử dụng để kiểm soát việc triển khai dần các tính năng hoặc bản cập nhật, trong khi ảnh hưởng của việc triển khai được theo dõi từ dữ liệu chẩn đoán được thu thập. Nó cũng được sử dụng để giảm thiểu các vấn đề về bảo mật hoặc hiệu suất với một tính năng hoặc bản cập nhật. Ngoài ra, ECS còn hỗ trợ thay đổi cấu hình liên quan đến dữ liệu chẩn đoán để giúp đảm bảo rằng các sự kiện thích hợp sẽ được thu thập. |
| [Cấp phép](#licensing-events)     | Cấp phép là dịch vụ dựa trên nền điện toán đám mây hỗ trợ kích hoạt Office của bạn để cài đặt mới và duy trì giấy phép trên thiết bị của bạn sau khi Office được kích hoạt. Dịch vụ này đăng ký từng thiết bị của bạn và kích hoạt Office, kiểm tra trạng thái đăng ký Office và quản lý các khóa sản phẩm của bạn.    |
| [Cấu hình dịch vụ](#services-configuration-events)  | Cấu hình dịch vụ cung cấp khả năng cập nhật các cài đặt cấu hình Office để bật hoặc tắt các tính năng của máy khách. Nó được gọi mỗi khi ứng dụng Office được khởi động và cung cấp chi tiết về các cấu hình và dịch vụ khác của Office. Cấu hình dịch vụ cũng kiểm soát các dịch vụ được chỉ định là dịch vụ cần thiết.  |
| [Phép đo từ xa](#telemetry-events)  | Dịch vụ phép đo từ xa được dùng để thu thập dữ liệu chẩn đoán từ ứng dụng Office. Dịch vụ này cho phép thu thập dữ liệu chẩn đoán do Office tạo ra, gồm cả dữ liệu chẩn đoán bắt buộc lẫn tùy chọn. Nó cũng chịu trách nhiệm thu thập phần dữ liệu chẩn đoán dịch vụ của dữ liệu dịch vụ bắt buộc cho Office.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Các sự kiện và trường dữ liệu cho các dịch vụ cần thiết cho Office

Phần tiếp theo sẽ cung cấp các thông tin sau đây:

- Danh sách các sự kiện cho từng dịch vụ cần thiết
- Mô tả về từng sự kiện
- Danh sách các trường dữ liệu trong mỗi sự kiện
- Mô tả về từng trường dữ liệu

Bạn có thể xem các sự kiện này bằng cách sử dụng Trình xem dữ liệu chẩn đoán.



## <a name="authentication-events"></a>Sự kiện xác thực

Các sự kiện dữ liệu chẩn đoán này được thu thập khi Office cố gắng lấy mã thông báo xác thực, bằng cách âm thầm hoặc thông qua nhắc nhở.

### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Được thu thập khi Office hiển thị cho người dùng lời nhắc đăng nhập xác thực dựa trên biểu mẫu.

Cùng với việc tiếp nhận mã thông báo tĩnh, lời nhắc xác thực được sử dụng để xác định xem người dùng có ở trạng thái xác thực bị lỗi hay không, đối với người dùng, điều này dẫn đến trạng thái Máy khách ngoại tuyến hoặc trong trường hợp xấu nhất, xác thực bị lỗi có thể ngăn chặn việc mua lại giấy phép và dẫn đến việc máy khách hoàn toàn không sử dụng được.

Lời nhắc đăng nhập dựa trên biểu mẫu (FBA) được sử dụng cho một số tình huống xác thực tại chỗ và thông thường chúng tôi muốn đảm bảo điều này không xảy ra, vì mọi người sẽ sử dụng Xác thực hiện đại do các lỗ hổng bảo mật liên quan đến FBA.

**Các trường sau đây sẽ được thu thập:**

  - **AuthScheme** - lược đồ xác thực được sử dụng

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

Việc biết được rằng người dùng đã đăng xuất giúp phân loại các sự kiện khác, ví dụ: lời nhắc, như ý muốn, vì vậy những sự kiện đó có thể được tính toán chính xác trong các số liệu về độ tin cậy/tính sẵn sàng và ngăn ngừa cảnh báo hoặc quay lại bản dựng dựa trên cơ sở bị lỗi mà người dùng sẽ gặp phải lời nhắc đăng nhập không mong muốn.

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

4\) Các tín hiệu này cung cấp tính sẵn sàng và trạng thái màn hình khởi chạy cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi chặn người dùng quan trọng

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

4\) Các tín hiệu này cung cấp tính sẵn sàng và trạng thái màn hình khởi chạy cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi chặn người dùng quan trọng.

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

4\) Các tín hiệu này cung cấp tính sẵn sàng và trạng thái màn hình khởi chạy cảnh báo để các kỹ sư của chúng tôi có thể nhanh chóng can thiệp và giảm thời gian nhằm giảm thiểu các lỗi quan trọng.

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

  - **Microsoft\_ADAL\_http\_sự kiện\_coun**t - Số lượngcuộc gọi HTTP được thực hiện bởi ADAL.

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

  - **Microsoft\_ADAL\_user\_cancel** - Cho biết việc cửa sổ giao diện người dùng đã được hủy bỏ là đúng hay sai.

  - **Microsoft\_ADAL\_x\_ms\_request\_id** – ID yêu cầu bổ sung được cung cấp trong tiêu đề HTTP cho dịch vụ của ADAL.

  - **Platform** - Win32/WinRT/Android/iOS/Mac

  - **Scenarioid** – GUID. Nhiều sự kiện có thể thuộc về một kịch bản duy nhất, ví dụ: kịch bản có thể được thêm một tài khoản mới nhưng có nhiều lời nhắc xảy ra như một phần của kịch bản đó. ID này cho phépsự tương quan xảy ra.

  - **SessionId** - GUID xác định phiên khởi động

  - **Skdver** - Phiên bản SDK máy khách MATS được sử dụng để tạo dữ liệu này

  - **StartTime** - Thời gian tại đó bắt đầu\*thao tác MATS API đã được gọi

  - **Tenantid** - GUID xác định đối tượng thuê mà người dùng được xác thực thuộc về (trong trường hợp không phải là ADAL).

  - **Uploadid** - GUID duy nhất cho sự kiện này, được sử dụng để khấu trừ

  - **Wamapi** - Xác định WAM API được gọi

  - **Wamtelemetrybatch** - Hiện chưa sử dụng. Trong tương lai, cho phép cấu phần WAM gửi thông tin bổ sung về sự kiện xác thực.

## <a name="click-to-run-events"></a>Sự kiện Click-to-Run

### <a name="officeclicktorunbootstrapper"></a>Office.ClickToRun.Bootstrapper 

Thiết lập Office và dữ liệu kiểm kê được thu thập khi người dùng đang chạy Office setup.exe để sửa đổi các sản phẩm Office đã cài đặt của họ. Được sử dụng để đo lường mức độ thành công/thất bại của cài đặt Office do người dùng khởi tạo đầy đủ bao gồm cả kiểm tra điều kiện tiên quyết.

Các trường sau đây sẽ được thu thập:

  - **Data\_BootStrapperStateFailure\_ErrorCode** – Mã lỗi chúng tôi không thành công

  - **Data\_BootStrapperStateFailure\_ErrorSource** – Hàm mà chúng tôi không thành công

  - **Data\_BootStrapperStateFailure\_FailingState** – Phần mà chúng tôi không thành công trong boostrapperbootstrapper

  - **Data\_BootStrapperStateFailure\_OExceptionType** – Kiểu ngoại lệ mà chúng tôi không thành công

  - **Data\_Culture** - Văn hóa mà chúng tôi đang chạy exe này, ví dụ: en-us

  - **Data\_HashedOLSToken** - Hàm băm sha-256 của mã thông báo dịch vụ OLS cung cấp cho chúng tôi

  - **Data\_Platform** - Cài đặt x64 hoặc x86

  - **Data\_PrereqFailure\_Type** – Lỗi điều kiện tiên quyết mà chúng tôi gặp phải, ví dụ: hệ điều hành không được hỗ trợ

  - **Data\_ProductReleaseId** - Sản phẩm chúng tôi đang cài đặt, ví dụ: Office 365 ProPlus

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang chạy kiểm tra lỗi hỏng để đảm bảo rằng các nhị phân Office là chính xác. Sử dụng để đo lường lỗi hỏng của nhị phân Office và các nhị phân bị hỏng.

Các trường sau đây sẽ được thu thập:

  - **Data\_Active -** Tệp kê khai luồng hiện tại mà chúng tôi đang kiểm tra trên ổ đĩa

  - **Data\_ActivePackages -** Những điều có trong tệp kê khai

  - **Data\_ActiveVersion -** Phiên bản của tệp kê khai

  - **Data\_AddFileCount -** Số tệp chúng tôi đang thêm

  - **Data\_AddFileFiles -** Mẫu tệp mà chúng tôi đang thêm

  - **Data\_CompressionLevel -** Cách các tệp được nén

  - **Data\_CorruptionCheckLevel -** Cách chúng tôi đang kiểm tra cho lỗi hỏng, giai đoạn một cách kỹ lưỡng

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

  - **Dữ liệu\_KeepIncompleteFileCount -** Số lượng tệp chúng tôi đang không thay đổi dù chúng đang không đầy đủ

  - **Data\_KeepIncompleteFileFiles -** Mẫu của các tệp mà chúng tôi đang giữ không đầy đủ

  - **Dữ liệu\_MismatchSizeCount -** Số lượng tệp có kích cỡ không khớp với tệp kê khai của chúng tôi

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

  - **Data\_Sku** - SKU đã được cài đặt, ví dụ: Office 365 ProPlus.en-us

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

  - **Data\_ProductReleaseId** - Sản phẩm chúng tôi đang cài đặt, ví dụ: Office 365 ProPlus

### <a name="officeclicktorunscenarioinstalltaskconfigure"></a>Office.ClickToRun.Scenario.InstallTaskConfigure

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang đặt các tệp mới tải xuống. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-** Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - ****Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskconfigurelight"></a>Office.ClickToRun.Scenario.InstallTaskConfigurelight

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office quyết định tệp cần được tải xuống. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskfinalintegrate"></a>Office.ClickToRun.Scenario.InstallTaskFinalintegrate

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang cài đặt giấy phép và thiết đặt đăng ký. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts -** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskfonts"></a>Office.ClickToRun.Scenario.InstallTaskFonts

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang cài đặt phông chữ. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskinitupdates"></a>Office.ClickToRun.Scenario.InstallTaskInitupdates

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang tạo thiết đặt để cập nhật hoạt động đúng. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office tạo mục nhập đăng ký cho ứng dụng Office Được sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltasklastrun"></a>Office.ClickToRun.Scenario.InstallTaskLastrun

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office hoàn tất cài đặt, ghim các phím tắt và tạo thiết đặt đăng ký cuối cùng. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**  ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-** Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskmigrate"></a>Office.ClickToRun.Scenario.InstallTaskMigrate

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang di chuyển cài đặt từ các phiên bản cũ hơn của Office. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskpublishrsod"></a>Office.ClickToRun.Scenario.InstallTaskPublishrsod

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang xuất bản đăng ký ảo cho lớp ảo hóa AppV. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy, ví dụ: cài đặt. 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**  ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskremoveinstallation"></a>Office.ClickToRun.Scenario.InstallTaskRemoveinstallation

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang loại bỏ các phần của Office khỏi thiết bị. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -**   Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang tải xuống các tệp mới cho Office. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -**  Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

Thiết lập Office và dữ liệu kiểm kê được thu thập khi trình cài đặt Office đang gỡ cài đặt phiên bản Office trước đó được cài đặt từ Cửa hàng. Sử dụng để đo lường mức độ thành công/thất bại của bản cài đặt Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskfinalintegrate"></a>Office.ClickToRun.Scenario.RepairTaskFinalintegrate

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách sửa chữa Office xuất bản lại các tệp .msi và tiện ích mở rộng Office. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -**   Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails-** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskfullrepair"></a>Office.ClickToRun.Scenario.RepairTaskFullrepair

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách sửa chữa Office tải xuống phiên bản mới nhất của ứng dụng khách Click-to-Run để chuẩn bị máy tính gỡ cài đặt và cài đặt lại. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskintegraterepair"></a>Office.ClickToRun.Scenario.RepairTaskIntegraterepair

Office thiết lập và kiểm kê dữ liệu được thu thập khi máy khách sửa chữa Office cố gắng sửa chữa một số mục nhập đăng ký sự cố đã biết. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails-** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi 

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenariorepairtaskremoveinstallation"></a>Office.ClickToRun.Scenario.RepairTaskRemoveinstallation

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách sửa chữa Office xóa Office khỏi thiết bị để chuẩn bị cài đặt lại khi sửa chữa. Sử dụng để đo lường mức độ thành công/thất bại của việc sửa chữa Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskintegrateupdate"></a>Office.ClickToRun.Scenario.UpdateTaskIntegrateupdate 

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run cập nhật giấy phép nếu cần. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskpublishrsod"></a>Office.ClickToRun.Scenario.UpdateTaskPublishrsod

Office được thiết lập và kiểm kê được thu thập khi máy khách Click-to-Run cập nhật thiết đặt đăng ký cho các nhị phân mới. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdateapply"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateapply

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run tắt các ứng dụng đang chạy nếu cần và cài đặt các tệp mới đã được tải xuống. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_AvailableVersion to-** Phiên bản Office có sẵn để cập nhật

  - **Data\_CompletedWithoutActionInfo -** Lý do tại sao chúng tôi chưa hoàn tất kịch bản, ví dụ: ứng dụng đã được mở

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_CorruptionChecksOnly –-** Nếu chúng tôi chỉ kiểm tra lỗi hỏng và không cập nhật

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails-** Chi tiết bổ sung về lỗi 

  - **Data\_ErrorMessage -** Thông báo lỗi về vấn đề đã xảy ra 

  - **Data\_ErrorSource -** Nơi xảy ra lỗi

  - **Data\_ExceptionType -** Trường hợp ngoại lệ chúng tôi không thành công 

  - **Data\_HardlinkingException -** Trường hợp ngoại lệ chúng tôi gặp phải khi tìm cách tạo liên kết cứng

  - **Data\_IsErrorCodeIgnorable -** Nếu mã lỗi mà chúng tôi không thành công có thể bỏ qua 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth -** Nếu chúng tôi tin rằng mã lỗi là có thể bỏ qua 

  - **Data\_NewestPackageVersion -** Phiên bản mới nhất của Office trên máy 

  - **Data\_OldestPackageVersion -** Phiên bản cũ nhất của Office trên máy 

  - **Data\_PackageOperationSuccessful -** Việc chúng tôi hoàn thành thành công tác vụ của chúng tôi trên gói chương trình Office có đúng hay không

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

  - Data\_WorkstationLockState -** Việc chúng tôi cho rằng máy tính bị khóa có đúng hay không

### <a name="officeclicktorunscenarioupdatetaskupdateclientdownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateclientdownload

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run tải xuống phiên bản mới hơn của chính nó. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -** ID máy duy nhất được sử dụng bởi Windows SQM

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdatedetection"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedetection

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run kiểm tra nếu có bản cập nhật mới. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_AvailableVersion to-** Phiên bản Office có sẵn để cập nhật

  - **Data\_ComAction -** Một số nguyên đại diện cho một thao tác com chúng tôi thực hiện

  - **Data\_CompletedWithoutActionInfo -** Lý do tại sao chúng tôi chưa hoàn tất kịch bản, ví dụ: ứng dụng đã được mở

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

  - **Data\_PackageUpdateAvailable -** Việc chúng tôi có sẵn phiên bản Office mới có đúng hay không

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdatedownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedownload

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang tải bản cập nhật mới. Sử dụng để đánh giá thành công / thất bại của việc Office Cập Nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -** Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

  - **Data\_AddingProducts -** Những sản phẩm chúng tôi đang yêu cầu thêm vào 

  - **Data\_AvailableVersion to-** Phiên bản Office có sẵn để cập nhật

  - **Data\_CompletedWithoutActionInfo -** Lý do tại sao chúng tôi chưa hoàn tất kịch bản, ví dụ: ứng dụng đã được mở

  - **Data\_CompletionState -** Cho biết chúng tôi đã hoàn thành tác vụ hay chưa

  - **Data\_CorruptionChecksOnly –-** Nếu chúng tôi chỉ kiểm tra lỗi hỏng và không cập nhật

  - **Data\_ErrorCode -** Mã lỗi mà chúng tôi đã thất bại 

  - **Data\_ErrorDetails-** Chi tiết bổ sung về lỗi 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**  ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktorunscenarioupdatetaskupdatefinalize"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatefinalize

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang dọn dẹp từ bản cập nhật và khôi phục các ứng dụng đã mở trước đó. Sử dụng để đánh giá thành công/thất bại của bản cập nhật Office.

Các trường sau đây sẽ được thu thập:

  - **Data\_15\_SourceType -** Nơi đặt nguồn Office 15, ví dụ CDN hoặc cục bộ 

  - **Data\_15\_UpdatesEnabled -** Cho biết bản cập nhật Office 15 có được bật hay không 

  - **Data\_15\_UpdateVersion -**   Phiên bản Office 15 chúng tôi đang cập nhật 

  - **Data\_15\_Version -** Phiên bản Office 15 

  - **Data\_16\_SourceType -** Nơi đặt nguồn Office 16, ví dụ CDN hoặc cục bộ 

  - **Data\_16\_UpdatesEnabled-** Cho biết bản cập nhật Office 16 có được bật hay không 

  - **Data\_16\_UpdateVersion -** Phiên bản Office 16 chúng tôi đang cập nhật 

  - **Data\_16\_Version -** Phiên bản Office 16 

  - **Data\_AddingFixedProducts-** Những sản phẩm chúng tôi đang thêm vào 

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

  - **Data\_ProductsToAdd -** Sản phẩm Office chúng tôi đang thêm 

  - **Data\_ProductsToRemove-**  Sản phẩm Office chúng tôi đang loại bỏ 

  - **Data\_RemovingFixedProducts-** Những sản phẩm chúng tôi đang loại bỏ 

  - **Data\_RemovingProducts -** Những sản phẩm chúng tôi được yêu cầu loại bỏ 

  - **Data\_ScenarioInstanceID -** Một GUID duy nhất cho kịch bản đang chạy 

  - **Data\_ScenarioName -** Kịch bản đang chạy. Ví dụ: cài đặt 

  - **Data\_ScenarioSubType -** Loại kịch bản chúng tôi đang chạy, ví dụ: gỡ cài đặt, cài đặt lại 

  - **Data\_SourceType -** Vị trí nguồn của chúng tôi, ví dụ: CDN 

  - **Data\_SqmMachineID -**   ID máy duy nhất được sử dụng bởi Windows SQM 

  - **Data\_SusClientID-**  Mã định danh cập nhật Office trên máy 

  - **Data\_TaskState -** Trạng thái tác vụ, ví dụ: đang chạy hoặc bị hủy bỏ 

  - **Data\_TotalClientCabSize -** Kích cỡ cab máy khách của chúng tôi 

  - **Data\_TriggeringUI -** Những gì kích hoạt giao diện người dùng 

  - **Data\_UpdatesEnabled -** Cho biết bản cập nhật Office có được bật hay không 

  - **Data\_Version -** Phiên bản Office 

### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang tạo một luồng truyền dẫn để tải xuống các tệp Office. Được sử dụng để xác định trang thái của các công nghệ truyền dẫn khác nhau (ví dụ: HTTP, BITS, DO), điều này rất quan trọng để tải xuống Office đúng cách để cài đặt và cập nhật.

Các trường sau đây sẽ được thu thập:

  - **Data\_IsForeGroundStreaming** – Nếu chúng tôi đang phát trực tuyến trong mặt trước hoặc nền

  - **Data\_IsInstallMode** – 1 nếu chúng tôi đang cài đặt và tải xuống tệp, 0 nếu chúng tôi không làm điều đó

  - **Data\_SourceProtocol –** Nếu chúng tôi tải xuống từ mạng dữ liệu nội dung, CDN, máy chúng tôi cài đặt trên đó, cục bộ hoặc từ một tài nguyên trên mạng cục bộ,

  - **Data\_Status** – Thành công hay thất bại 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Thiết lập Office và dữ liệu kiểm kê được thu thập khi máy khách Click-to-Run đang hoàn thành trạng thái cập nhật

Các trường sau đây sẽ được thu thập:

  - **Data\_build** - Phiên bản Office hiện đang được cài đặt

  - **Data\_channel** – Kênh mà người dùng đang sử dụng

  - **Data\_errorCode** – Một mã số nguyên, xác định loại lỗi đã xảy ra, nếu có

  - **Data\_errorMessage** – Một chuỗi cung cấp mô tả về lỗi đã xảy ra, nếu có

  - **Data\_status** – Một trạng thái ngắn về những gì đã xảy ra trong quá trình cập nhật, chẳng hạn như thành công hoặc đã tải xuống

  - **Data\_targetBuild -** - Phiên bản Office mà chúng tôi đang cố gắng cập nhật


## <a name="enhanced-configuration-service-ecs-events"></a>Sự kện Dịch vụ cấu hình nâng cao (ECS)

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

  - **UnmergedConfigs** - Danh sách các cấu hình không được phối


## <a name="licensing-events"></a>Sự kiện cấp phép

### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Điều này được thu thập khi người dùng được cấp phép và chấp nhận EULA cho giấy phép hiện tại

Nó được sử dụng để phát hiện người dùng có ở trạng thái tốt hay không, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **ACID** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **DwEulaId** – Mã định danh dạng số của loại EULA vừa được người dùng chấp nhận

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Đăng thiết đặt giấy phép trên máy, chúng tôi cố gắng kích hoạt giấy phép bằng cách gọi điện cho dịch vụ AVS. Điều này báo cáo kết quả của cuộc gọi kích hoạt

Quan trọng là phát hiện số người dùng đang phải đối mặt với các vấn đề về kích hoạt. Chúng tôi có bất thường phát hiện để phát hiện bất kỳ hồi quy. Điều này là rất quan trọng vì chúng tôi có sự phụ thuộc bên ngoài vào AVS và tín hiệu này cho biết tình tạng của các đối tác bên ngoài của chúng tôi có tốt hay không. Nó cũng được sử dụng cho mục đích chẩn đoán và trạng thái hệ thống nếu người dùng báo cáo sự cố với các máy tính của họ

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **ReferralData** – Mã định danh của OEM đã cài đặt Office trên máy

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Nếu chúng tôi không thể tự động kích hoạt giấy phép vì một số lý do, chúng tôi sẽ hiển thị trình hướng dẫn kích hoạt cho người dùng. Điều này báo cáo rằng trình hướng dẫn được đang được hiển thị cho người dùng. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Sự kiện này không thu thập trường nào.

### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

Đây là tín hiệu cho chúng tôi biết nếu thử nghiệm mà chúng tôi đang chạy để thực thi đăng nhập người dùng như một phần của việc cấp phép có thành công hay không. Điều này rất quan trọng trong việc phát hiện thành công hay thất bại của thử nghiệm buộc người dùng phải đăng nhập, đây là bước bắt buộc đối với ngăn xếp cấp phép hiện đại. Lỗi đăng nhập sẽ cho kết quả rằng người dùng không còn sử dụng ứng dụng.

Các trường sau đây sẽ được thu thập:

  - **Đủ điều kiện** – Xác định xem người dùng đủ điều kiện đối với việc thực hiện đăng nhập hay không

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Điều này được thu thập khi chúng tôi hiển thị hộp thoại hết hạn cho người dùng thông báo rằng giấy phép của họ đã hết hạn. Đây là điều quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **LicNotificationState** – Bộ liệt kê cho chúng ta biết loại thông báo nào đang được hiển thị cho người dùng

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Điều này được thu thập trên mỗi phiên báo cáo trạng thái cấp phép của máy và báo cáo các lỗi mà người dùng đang gặp phải do họ không thể sử dụng ứng dụng. Sự kiện này cho biết nếu máy của người dùng có trạng thái tốt hay không. Chúng tôi có phát hiện bất thường được thiết lập cho sự kiện này để cho biết liệu hồi quy có gây ra hành vi xấu của người dùng hay không. Điều này cũng rất quan trọng khi chẩn đoán các vấn đề của người dùng và theo dõi trạng thái hệ thống

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép 

  - **IsSessionLicensing** – Chúng tôi hiện có đang chạy dưới chế độ kích hoạt máy tính dùng chung hay không 

  - **LicenseCategory** – Danh mục giấy phép Office mà người dùng đang sử dụng 

  - **Licenses** – Danh sách tên của tất cả các giấy phép Office có trên máy 

  - **LicenseStatuses** – Trạng thái của tất cả các giấy phép Office có trên máy 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Chúng tôi thu thập điều này khi người dùng đang thiết lập một thiết bị và chúng tôi gọi dịch vụ cấp phép của chúng tôi để phát hiện xem người dùng đã đăng nhập có quyền Office hay không. Điều này báo cáo kết quả của cuộc gọi đó. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Sự kiện này không thu thập trường nào.

### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Trên mỗi phiên, chúng tôi kiểm tra xem đã qua 72 giờ kể từ khi gia hạn giấy phép cuối cùng hay chưa và tìm cách mở rộng hết giấy phép hiện tại. Sự kiện này báo cáo sự thành công hay thất bại của cuộc gọi mà chúng tôi thực hiện để đảm bảo chúng tôi có thể gia hạn hết hạn giấy phép và giữ cho chức năng cài đặt Office của người dùng. Nó rất quan trọng trong việc chẩn đoán các vấn đề liên quan đến đăng ký và các vấn đề dịch vụ cho người dùng và rất quan trọng trong việc phát hiện hồi quy cho người dùng đăng ký đã kích hoạt.

Các trường sau đây sẽ được thu thập:

  - **Mode** – Một đại diện bộ liệt kê của ngăn xếp cấp phép Office đang được sử dụng trên máy này

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Nếu thiết bị chuyển về chế độ giảm chức năng, chúng tôi sẽ gửi tín hiệu này để cho biết rằng máy không ở trạng thái khỏe. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **ACID** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **DaysRemaining** - Số ngày còn lại trước khi giấy phép Office hiện tại hết hạn

  - **Mode** – Một đại diện bộ liệt kê của ngăn xếp cấp phép Office đang được sử dụng trên máy này

  - **ProductName** – Tên sản phẩm mà người dùng hiện đang sử dụng

  - **Reason** – Mã lỗi cho biết lý do cho tình trạng hiện tại của giấy phép

### <a name="officelicensinginstallkey"></a>Office.Licensing.InstallKey

Điều này được thu thập khi chúng tôi cố gắng cài đặt một khóa trên thiết bị để cấp phép máy. Nó báo cáo việc cài đặt có thành công hay không và nếu không thì là mã lỗi. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **Prid** – Tên của nhóm sản phẩm mà một khóa đang được cài đặt

  - **SkuId** - Mã định danh GUID đại diện cho sản phẩm Office mà một khóa đang được cài đặt 

### <a name="officelicensinginvokelicensewizard"></a>Office.Licensing.InvokeLicenseWizard

Trong trường hợp chúng tôi thấy có vấn đề với quy trình kích hoạt, chúng tôi sẽ kích hoạt trình hướng dẫn giấy phép và gửi tín hiệu này để chỉ ra điều tương tự. Đây là điều quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **LicenseCategory** – Trạng thái giấy phép Ofice mà người dùng đang sử dụng

  - **MachineKey** - Mã định danh chữ và số của khóa giấy phép đã được phát hành cho người dùng

### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Nếu thiết bị đang phải đối mặt với vấn đề cấp phép và cuối cùng chúng tôi hiển thị thanh cái cho người dùng, chúng tôi sẽ gửi tín hiệu này cũng báo cáo loại thanh cái được hiển thị cho người dùng. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **SuppressNotification** – Cho biết nếu chúng tôi ngăn thanh cái cấp phép

  - **Title** – Tiêu đề của thanh cái cấp phép được hiển thị cho người dùng

  - **Type** – Loại thanh cái cấp phép được hiển thị cho người dùng

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Nếu chúng tôi đóng hoặc gặp sự cố với Office do vấn đề cấp phép, chúng tôi sẽ gửi tín hiệu này để cho biết điều tương tự. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **ExitCode** – Mã nội bộ khiến ứng dụng bị thoát

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

Trong quá trình tìm cách giấy phép của thiết bị, ứng dụng sẽ thử tải danh tính của người dùng để xem người dùng có quyền Office hay không. Sự kiện này báo cáo sự thành công hay thất bại cùng với mã lỗi. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **FederationProvider** – Chuỗi xác định nhà cung cấp liên kết cho người dùng hiện đang đăng nhập

  - **IdentityProvider** – Chuỗi xác định nhà cung cấp danh tính cho người dùng hiện đang đăng nhập

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Điều này được thu thập nếu chúng tôi hiển thị EULA cho người dùng và người dùng đã chọn không chấp nhận nó do chúng tôi gặp sự cố/đóng ứng dụng. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **Acid** - Mã định danh GUID đại diện cho sản phẩm Office mà người dùng được cấp phép

  - **OptInShown** – Cho biết liệu hộp thoại opt in có được hiển thị trong lần khởi động đầu tiên của ứng dụng đã được hiển thị chưa

  - **Office.Licensing.NextUserLicensingEligible -** Tín hiệu này cho chúng tôi biết nếu người dùng đủ điều kiện chuyển sang ngăn xếp cấp phép mới của chúng tôi. Điều này rất quan trọng để định lượng tác động đối với người dùng hiện tại khi chúng tôi triển khai ngăn xếp cấp phép mới của mình và đảm bảo rằng người dùng không bị mất chức năng

Sự kiện này không thu thập trường nào.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Khi thiết bị nằm trong ngăn cấp phép hiện đại, chúng tôi sẽ cố gắng lấy tệp giấy phép trực tiếp từ dịch vụ. Sự kiện này báo cáo sự thành công hay thất bại cùng với mã lỗi cuộc gọi của dịch vụ đó. Điều quan trọng là phát hiện xem người dùng có ở trạng thái tốt trong ngăn xếp cấp phép hiện đại, được sử dụng cho sức khỏe hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **MetadataValidationResult** – Kết quả xác thực siêu dữ liệu của giấy phép để xác minh rằng nó không bị giả mạo

  - **MetadataValidationResult** – Kết quả xác thực chữ ký của giấy phép để xác minh rằng nó đã không bị giả mạo

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Điều này được thu thập trên mỗi phiên một thiết bị đang chạy trên theo ngăn xếp cấp phép hiện đại. Nó báo cáo trạng thái cấp phép của máy và báo cáo các lỗi mà người dùng đang gặp do họ không thể sử dụng ứng dụng. Sự kiện này cho biết máy của người dùng có đang ở trạng thái tốt trong ngăn xếp cấp phép hiện đại hay không. Chúng tôi có phát hiện bất thường được thiết lập cho sự kiện này để cho biết liệu hồi quy có gây ra hành vi xấu của người dùng hay không. Điều này cũng rất quan trọng khi chẩn đoán các vấn đề của người dùng và theo dõi trạng thái hệ thống.

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

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

Chúng tôi có một thử nghiệm cung cấp cho người dùng tùy chọn để thử và thiết lập tự động phát trực tiếp cho Office từ một ứng dụng mà không bao giờ rời khỏi bối cảnh của ứng dụng. Điều này báo cáo sự thành công hay thất bại cùng với mã lỗi. Đây là điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

Các trường sau đây sẽ được thu thập:

  - **StorePurchaseStatus** – Đại diện cho mã lỗi/mã thành công của cuộc gọi mua hàng được thực hiện thông qua Windows Store

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Nếu người dùng đang chạy trong chế độ kích hoạt máy tính được chia sẻ, chúng tôi sẽ cố gắng tìm kiếm mã thông báo phiên trên máy cho phép người dùng sử dụng ứng dụng. Sự kiện này báo cáo sự thành công hay thất bại cùng với mã lỗi. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ.

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

  - **PendingAcid** – ID sản phẩm mà một chuyển đổi SKU đang chờ xử lý

  - **SourceSku** – Tên của SKU ban đầu đã được cài đặt trên máy

  - **UninstallProduct** – Cho biết liệu sản phẩm cũ sẽ được gỡ cài đặt như một phần của việc chuyển đổi hay không

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Vì một số lý do nếu chúng tôi không thể cấp phép cho người dùng, chúng tôi sẽ cài đặt khóa gia hạn và gửi tín hiệu này để nhận biết. Điều rất quan trọng trong việc phát hiện nếu người dùng ở trạng thái tốt và không thiếu chức năng, được sử dụng cho trạng thái hệ thống và được sử dụng cho mục đích chẩn đoán nếu người dùng báo cáo sự cố với máy của họ

Các trường sau đây sẽ được thu thập:

  - **OpportunisticTokenRenewalAttempted** – Cho biết nếu chúng tôi đã thử gia hạn cho người dùng ở chế độ kích hoạt máy tính được chia sẻ hay chưa

  - **ReArmResult** – Cho biết kết quả của việc sắp xếp lại khóa đã cài đặt có thể kéo dài thời hạn của giấy phép hiện tại

## <a name="services-configuration-events"></a>Sự kiện Cấu hình dịch vụ

Không có sự kiện dữ liệu chẩn đoán dịch vụ bắt buộc được thu thập bởi Cấu hình dịch vụ.

## <a name="telemetry-events"></a>Sự kiện phép đo từ xa

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

  - **ProcessorArchitecture -** Kiến trúc bộ vi xử lý mà Office đang chạy trên.

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

  - **ProcessorCount -** Số lượng bộ vi xử lý trên thiết bị mà Office đang chạy.

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

  - **PowerPlatformRole -** Mã định danh về vai trò máy tính ưa thích OEM của thiết bị mà Office đang chạy trên đó.

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

<!-- end list -->

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

  - **PowerPlatformRole -** Mã định danh về vai trò máy tính ưa thích OEM của thiết bị mà Office đang chạy trên đó.

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

Sử dụng để ghi lại số liệu gặp sự cố.

Các trường sau đây sẽ được thu thập:

  - **AffectedProcessAppBuild -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

  - **AffectedProcessAppBuildRevision -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

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

  - **CrashedEcsETag -** một mã định danh thử nghiệm cho quy trình rơi.

  - **CrashedImpressionId -** mã định danh ấn tượng của quy trình rơi.

  - **CrashedProcessSessionID -** một mã định danh duy nhất của quy trình rơi.

  - **CrashedProcessSessionInitTime -** thời gian khi bắt đầu quy trình bị ảnh hưởng.

  - **CrashType -** Mã định danh bucketing cho loại gặp sự cố.

  - **DetectionTime -** thời gian khi việc thoát không mong muốn đã được phát hiện.

  - **ErrorString -** mô tả lỗi.

  - **ExceptionAddress -** địa chỉ trong chương trình nơi lỗi xảy ra.

  - **ExceptionCode -** Mã định danh bucketing cho trường hợp ngoại lệ.

  - **FaultAppName -** tên của ứng dụng lỗi.

  - **InstallMethod** - Bản dựng hiện tại của Office đã được nâng cấp từ, quay lại hay cài đặt mới.

  - **InstallType -** Mã định danh cho phương thức mà Office được cài đặt.

  - **InstallTypeName -** Mã định danh cho phương thức mà Office được cài đặt.

  - **IsLabMachine -** Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không.

  - **IsMsftInternal -** Người dùng Windows mà Office đang chạy có phải nhân viên của Microsoft hay không.

  - **ModuleBaseAddress -** các địa chỉ cơ sở của mô-đun lỗi.

  - **ModuleBuildVersion -** Số phiên bản bản dựng của mô-đun lỗi.

  - **ModuleMajorVersion -** Số phiên bản chính của mô-đun lỗi.

  - **ModuleMinorVersion -** Số phiên bản phụ của mô-đun lỗi.

  - **ModuleName -** Tên mô-đun lỗi.

  - **ModuleOffset -** Bù trừ theo byte từ địa chỉ cơ sở nơi lỗi xảy ra.

  - **ModuleRevisionVersion -** Số phiên bản bản chỉnh sửa bản dựng của mô-đun lỗi.

  - **ModuleSize -** Kích cỡ mô-đun lỗi theo byte.

  - **OSEnvironment -** Mã định danh cho môi trường mà Office đang chạy.

  - **PreviousBuild** - Phiên bản bản dựng đã được cài đặt trước đó

  - **UAETypeName -** Mã định danh bucketing cho cách ứng dụng cố ý thoát.

  - **VerifyElseCrashTag -** Mã định danh duy nhất cho vị trí ứng dụng gặp sự cố.

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

Sử dụng để ghi lại số liệu gặp sự cố.

Các trường sau đây sẽ được thu thập:

  - **CrashedAppBuild -** Mã định danh phiên bản bản dựng cho quá trình bị ảnh hưởng.

  - **CrashedAppMajor -** Mã định danh phiên bản chính cho quá trình bị ảnh hưởng.

  - **CrashedAppMinor -** Mã định danh phiên bản phụ cho quá trình bị ảnh hưởng.

  - **CrashedAppRevision -** Mã định danh phiên bản chỉnh sửa bản dựng cho quá trình bị ảnh hưởng.

  - **CrashedConfigIds -** Cấu hình được gán cho quy trình bị rơi.

  - **CrashedEcsETag -** một mã định danh thử nghiệm cho quy trình rơi.

  - **CrashedImpressionId -** mã định danh ấn tượng của quy trình rơi.

  - **CrashedModuleName -** Tên mô-đun lỗi.

  - **CrashedSessionId -** một mã định danh duy nhất của quy trình rơi.

  - **CrashedSessionInitTime -** thời gian khi bắt đầu quy trình bị ảnh hưởng.

  - **CrashType -** Mã định danh bucketing cho loại gặp sự cố.

  - **DetectionTime -** thời gian khi việc thoát không mong muốn đã được phát hiện.

  - **ExceptionAddress -** địa chỉ trong chương trình nơi lỗi xảy ra.

  - **ExceptionCode -** Mã định danh bucketing cho trường hợp ngoại lệ.

  - **HexExceptionAddress -** Địa chỉ theo hệ thập lục phân trong chương trình nơi xảy ra lỗi.

  - **HexExceptionCode -** Mã định danh theo hệ thập lục phân cho trường hợp ngoại lệ.

  - **HexModuleBaseAddress -** các địa chỉ cơ sở theo hệ thập lục phân của mô-đun lỗi.

  - **HexModuleOffset -** Bù trừ theo byte (theo hệ thập lục phân) từ địa chỉ cơ sở nơi lỗi xảy ra.

  - **ModuleSize -** Kích cỡ mô-đun lỗi theo byte theo hệ thập lục phân.

  - **HexVerifyElseCrashTag -** Mã định danh duy nhất theo hệ thập lục phân cho vị trí ứng dụng gặp sự cố.

  - **InstallMethod** - Bản dựng hiện tại của Office đã được nâng cấp từ, quay lại hay cài đặt mới.

  - **IsLabMachine -** Office có đang được chạy trong phòng thí nghiệm của Microsoft hay không.

  - **ModuleBaseAddress -** các địa chỉ cơ sở của mô-đun lỗi.

  - **ModuleOffset -** Bù trừ theo byte từ địa chỉ cơ sở nơi lỗi xảy ra.

  - **ModuleSize -** Kích cỡ mô-đun lỗi theo byte.

  - **PreviousBuild** - Phiên bản bản dựng đã được cài đặt trước đó

  - **UAEOSEnvironment -** Mã định danh môi trường hệ điều hành môi trường.

  - **VerifyElseCrashTag -** Mã định danh duy nhất cho vị trí ứng dụng gặp sự cố.

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

  - **DialogCancelled** - Hộp thoại Trình xem dữ liệu chẩn đoán có bị hủy bỏ hay không

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

<!-- end list -->

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

  - **ThrottlingTimestamp** - Khi phép đo từ xa được tiết lưu

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
