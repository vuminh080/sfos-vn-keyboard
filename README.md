# sfos-vn-keyboard
Sailfish OS Vietnam Keyboard [MOD]

Hưỡng dẫn cài đặt:

**1.** Cài đặt sẵn Multi Keyboard Language: https://openrepos.net/content/adel/multi-keyboard-layouts 

**2.** Tải các file về, copy vào thư mục /home trên điện thoại 

**3.** Mở chế độ dành cho nhà phát triển, đặt mật khẩu truy cập SSH 

**4.** Dùng Terminal có sẵn: 

**5.** Gõ lệnh ```kt_devel-su ```để truy cập quyền root, mật khẩu là mật khẩu bạn vừa đặt 

**6.** Gõ các lệnh sau: 
   ```kt
   cd /home

   cp sobek_vn.qml /usr/share/maliit/plugins/com/jolla/layouts

   cp layouts_sobek_vn.conf /usr/share/maliit/plugins/com/jolla/layouts
   ```

**7.** Khởi động lại thiết bị, chọn Vietnamese trong phần cài đặt bàn phím
