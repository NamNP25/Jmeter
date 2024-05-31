KIỂM TRA HIỆU NĂNG TRANG WEB
1. Mục tiêu
   * Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web:  https://www.simplilearn.com/
   * Chạy kịch bản kiểm tra và ghi lại kết quả.
   * Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
   * Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.
2. Kịch bản kiểm tra
   * Thread Group:
     - Số lượng thread: 100
     - Thời gian chạy: 60 giây
     - Ramp-up period: 10 giây
   * HTTP Request:
     - URL: https://www.coursera.org/learn/machine-learning
     - Method: GET
     - Content encoding: UTF-8
   * Listeners:
     - View Results Tree
     - Aggregate Report
 3. Kết quả kiểm tra
![image](https://github.com/NamNP25/Jmeter/assets/96900033/f1fb9b27-fbdb-43ce-824a-0a271ce5fb0f)
![image](https://github.com/NamNP25/Jmeter/assets/96900033/946778f9-f7f3-43a2-b150-17963dfbf2e2)
![image](https://github.com/NamNP25/Jmeter/assets/96900033/3bebd42d-ac46-48df-8959-661609b0d6fc)






    

4. Phân tích kết quả kiểm tra
   * Số lượng yêu cầu thành công: 990/990 = 100%
   * Số lượng yêu cầu thất bại: 0/1000 = 0,00%
   * Thời gian phản hồi trung bình: 32, ms
   * Thời gian phản hồi trung vị: 17,95 ms
   * Thời gian phản hồi percentil 90: 77,26 ms
   * Chuyển tải: 28 yêu cầu/giây

5. Kết luận
Trang web https://www.simplilearn.com/ có hiệu năng tốt. Số lượng yêu cầu thành công trung bình (100%), số lượng yêu cầu thất bại thấp (0%). Thời gian phản hồi trung bình, trung vị đều ở mức thấp (dưới 100 ms). Chuyển tải của trang web trung bình(28 yêu cầu/giây).

