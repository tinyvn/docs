# Lỗi bị mất mạng khi bật Tiny

## Trường hợp 1 : Máy bạn có card mạng Incoming Conection

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Thì bạn cần phải xoá Card mạng này đi, bằng cách :

Đầu tiên bạn vào Control Panel, chọn View network status and task

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

Sau đó Bạn chọn mục Change adapter settings

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Trong mục này bạn sẽ thấy danh sách driver mạng của mình, nếu có driver tên là "incoming connection" thì bạn chuột phải vào sau đó chọn xoá.

## Trường hợp 2 : Bạn đang kết nối cùng lúc với mạng dây và wifi

Bạn phải kiểm tra xem mình có đang kết nối cùng lúc với WI-FI và mạng dây không. Nếu có, tắt/ngắt kết nối 1 trong 2 loại mạng là được.

## Trường hợp 3 : Máy bạn chưa tắt IPv6

Nếu đã thử 2 cách trên mà vẫn bị mất mạng khi bật ứng dụng Tiny, bạn có thể thử tắt IPv6

&#x20;Cách tắt IPv6 bạn có thể tham khảo tại[ ĐÂY](loi-core-may-nha.md#cach-1-tat-ipv6)



## Trường hợp 4 : Máy bạn sử dụng card mạng killer

### Bước 1 : Kiểm tra xem máy bạn có sử dụng card mạng Killer không&#x20;

Các bạn nhấn Windows, sau đó gõ "device manager" rồi nhấn Enter, trong cửa sổ mới mở ra các bạn chọn mục "network adapter", trong mục này nếu các bạn thấy có dòng Killer tương tự như hình thì tức là máy bạn đang sử dụng card mạng Killer

<figure><img src="../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

### Bước 2 : Sau khi đã xác định được là máy bạn sử dụng card mạng Killer, thì các bạn vào app killer intelligence center để tắt các mục như hình bên dưới, nếu máy bạn chưa có app thì bạn có thể tải trên trang chủ của Intel

<figure><img src="../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>



#### _Nếu sau khi tắt IPv6 mà máy vẫn không có mạng lại thì vui lòng liên hệ với cskh của Tiny tại_ [_đây_](../lien-he-voi-chung-toi.md)_._

####

