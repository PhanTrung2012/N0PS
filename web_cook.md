chúng ta truy cập web đã được cho sẵn và mở inspect element( mình dùng opera gx nên tên nó là thế)

![image](https://github.com/PhanTrung2012/N0PS/assets/121162586/1bc65122-0719-479c-b17c-e95cf3ac49b6)

chúng ta tìm tới mục application (1) và tìm cookie (2)

cookie được viết dạng base64 nên decode nó (3)

sau khi decode xong chúng ta thấy quyền admin đang là 0, hãy chỉnh về 1 rồi encode base64

sau đó paste vào ô value và f5 lại web, chúng ta sẽ có flaf -> N0PS{y0u_Kn0W_H0w_t0_c00K_n0W}
