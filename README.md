1.Cài đặt chương trình trên local.
  - Cài đặt môi trường để chạy ứng dụng (https://o7planning.org/vi/10377/huong-dan-cai-dat-va-cau-hinh-java)
  - Cài đặt Eclipse.
  - Clone project.
  - Thêm project vừa clone vào Eclipse.
  - Tiến hành chạy chương trình bằng Maven
    + Chuột phải vào project -> Run as -> Run configurations
    + Mục base directory : (Chọn đường dẫn đến project) ${workspace_loc:/study_program_languages}
    + Goals : tomcat7:run -X
    + Sau đó Apply và tiến hành Run.
  - Nếu trong quá trình build có lỗi, thì xóa thư mục target và tiến hành refesh project và chạy lại.