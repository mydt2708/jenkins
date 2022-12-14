## Lesson 1: Introduction & getting started
- Jenkins
  - Jenkins là ứng dụng Java
  - dùng để tự động thực hiện chức năng tích hợp liên tục (CI – Continuous Integration) và xây dựng các tác vụ tự động hóa
  - được sử dụng để tích hợp liên tục và phân phối liên tục
  - Jenkins giúp giám sát thực hiện việc thực thi các jobs như build project hay chạy các jobs.
- Cách thức hoạt động của Jenkins:
  - pull code từ repo về branch để thực hiện code
  - sau đó thưc hiện commit lên repo
  - Thưc hiện build code
  - Report sau khi build nếu có
  
### Cài đặt Jenkins bằng docker link hướng dẫn: [link](https://techmaster.vn/posts/35964/jenkins-tutorial-phan-1-cai-dat-jenkins-bang-docker)

- Step 1:  sử dụng lệnh:
"docker run -d --name jenkins -p 8080:8080 -p 50000:50000 -v /Users/hirosume/Desktop/jenkins:/var/jenkins_home jenkins/jenkins:lts"     

<img width="800" alt="image" src="https://user-images.githubusercontent.com/106597077/207627821-d2c1ee49-d84d-479f-809f-7205f4bc9f85.png">

- Step 2: Truy cập : http://localhost:8080/ 

<img width="1274" alt="image" src="https://user-images.githubusercontent.com/106597077/207628711-82137233-2ce5-445c-bf6b-9165e3fc2101.png">

- Step 3: Tại cmd, gõ lệnh `docker logs ${CONTAINER ID}` để lấy pass 
 + Sau khi nhập pass > click Continues: 

<img width="1277" alt="image" src="https://user-images.githubusercontent.com/106597077/207629585-261d4b02-6c83-4858-b00c-3eccb1276f57.png">


- Step 4: Chọn cài đặt plugins

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/106597077/207630475-c7d24345-d472-4c84-9520-b230c5ffd1eb.png">

