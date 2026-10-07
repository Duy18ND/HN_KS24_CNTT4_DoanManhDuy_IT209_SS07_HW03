# Báo cáo Bài 3: Cấu hình dịch vụ Systemd cho Spring Boot

## 1. Kết quả kiểm tra trạng thái dịch vụ
Thực thi lệnh: `sudo systemctl status spring-app.service`

**Đầu ra:**
```text
● spring-app.service - Spring Boot Application Service
     Loaded: loaded (/etc/systemd/system/spring-app.service; enabled; vendor preset: enabled)
     Active: active (running) since Wed 2026-10-07 17:20:00 +07; 1min ago
   Main PID: 14052 (java)
      Tasks: 35 (limit: 4614)
     Memory: 250.5M
     CGroup: /system.slice/spring-app.service
             └─14052 /usr/bin/java -jar /opt/spring-app/app.jar
