            ****** Mục đích của từng tệp là gì? ******
           app.py: Tạo giao diện người dùng cho ứng dụng và chạy chương trình
           statics_tyles.css: Hỗ trợ, làm cho giao diện đẹp và dễ nhìn
           templates_history.html: Tạo giao diện hiển thị lịch sử cảnh báo
           templates_index.html: Tạo giao diện web chính, hiển thị bao gồm tất cả nội dung
           ****** Hướng dẫn cách cài đặt và chạy phần mềm. *******
           Đầu tiên tải xuống 4 tệp trên Github:
           https://github.com/VoMinhHau789/BaoCaoMangCamBien
           ****** CÁCH CHẠY "ỨNG DỤNG HỆ THỐNG GIÁM SÁT NHIỆT ĐỘ VÀ ĐỘ PH" ******
           Đầu tiên, máy của chúng ta cần có hệ điều hành linux
           Tạo 1 file temperature_ph_nonitoring
           Trong file temperature_ph_nonitoring tạo các file con bao gồm file static (styles.css), templates (history.html và index.html), app.py, database.db, alerts.txt 
           Mở terminal, khai báo môi trường ảo bằng lệnh python3 -m venv venv và source venv/bin/activate để kích hoạt môi trường ảo
           Sau đó nhập lệnh cd temperature_ph_nonitoring để trỏ đến thư mục 
           Cuối cùng nhập lệnh python app.py để lấy địa chỉ IP: http://127.0.0.1.5000
           Copy địa chỉ trên, truy cập web, dán địa chỉ này vào và chạy app.
