# create_ipv6
## Lưu Ý: 
  Click vào file README.md => Chuyển sang chế độ từ Preview => Code  để xem đúng format hơn.
## Tạo proxy:
- Bước 1: Tạo máy ảo Centos 7	
- Bước 2: ssh đến máy server
- Bước 3:
  + 3.1 Public repo: https://github.com/ATech-MMO-Projects/create_ipv6 và lấy link raw của file https://github.com/ATech-MMO-Projects/create_ipv6/blob/main/install-proxy-ipv6-user.sh
  + 3.2 Chạy lệnh:
~~~
wget {link raw vừa lấy ở trên} && chmod +x install-proxy-ipv6-user.sh && bash install-proxy-ipv6-user.sh
~~~
