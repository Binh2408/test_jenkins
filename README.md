# test_jenkins


-Tạo Jenkins trên Docker bằng lệnh:
docker run -d ^ -p 8080:8080 -p 50000:50000 ^ -v E:\jenkins_home ^ --name jenkins ^ jenkins/jenkins:lts
-Sau đó chạy localhost để vào jenkins
-Tạo thông tin
-Tạo dự án trong jenkins
-Tạo file JENKINSFILE trong SpringBoot
-Tiếp theo Build Now trong URL jenkins