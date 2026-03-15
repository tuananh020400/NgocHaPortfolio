# Portfolio - Nguyễn Thị Ngọc Hà

## Thông tin cá nhân

**Tên:** Nguyễn Thị Ngọc Hà  
**Nghề nghiệp:** Sinh viên năm 2 chuyên ngành Tài chính Ngân hàng  
**Trường:** Đại học Ngoại thương Hà Nội  
**Ngoại ngữ:** IELTS 7.0 (Academic)

## Giới thiệu

Mình là sinh viên năm 2 chuyên ngành Tài chính Ngân hàng tại Đại học Ngoại thương. Yêu thích nghiên cứu về chính sách tiền tệ và muốn phát triển các giải pháp tài chính sáng tạo.

## Học vấn

**Trường:** Đại học Ngoại thương Hà Nội  
**Chuyên ngành:** Tài chính Ngân hàng  
**Năm học:** Năm 2  
**Mối quan tâm:** Chính sách tiền tệ và sự hội nhập kinh tế quốc tế

## Hoạt động

- Thành viên câu lạc bộ Future Bankers (FBN)
- Tham gia nghiên cứu khoa học cấp trường
- Vào vòng 2 cuộc thi Business Plan
- Các dự án phân tích tài chính cá nhân

## Khát vọng

Muốn trở thành chuyên gia tài chính kết nối lý thuyết và thực tiễn, đóng góp vào sự phát triển của hệ thống ngân hàng Việt Nam.

## Nghiên cứu khoa học

### Đề tài: Ảnh hưởng của chính sách tiền tệ thắt chặt đến tăng trưởng tín dụng và lạm phát tại Việt Nam (2020-2024)

**Thời gian:** Tháng 3 - Tháng 11/2024  
**Nhóm nghiên cứu:** 4 sinh viên  
**Giảng viên hướng dẫn:** TS. Nguyễn Văn Minh - Khoa Tài chính Ngân hàng

**Mô tả:** Nghiên cứu tác động của các công cụ chính sách tiền tệ thắt chặt của NHNN đến nền kinh tế Việt Nam giai đoạn 2020-2024, sử dụng mô hình VAR với dữ liệu chuỗi thời gian.

**Kết quả:** Điểm B+ cho môn Nghiên cứu khoa học

## Dự án cá nhân

### 1. Dashboard Phân tích Cổ phiếu Ngân hàng
**Thời gian:** Tháng 8 - Tháng 10/2024  
**Công nghệ:** Excel, Power BI  
**Mô tả:** Tạo dashboard phân tích 8 ngân hàng lớn nhất Việt Nam với các chỉ số P/E, P/B, ROE, ROA, NIM. Sử dụng VietStock API và Power Query để thu thập, xử lý dữ liệu.  
**Kết quả:** Điểm A-, được thầy khen ngợi

### 2. Mô hình Đánh giá Tín dụng SME
**Thời gian:** Tháng 12/2024 - Tháng 2/2025  
**Công nghệ:** Python, Jupyter Notebook  
**Mô tả:** Xây dựng mô hình Machine Learning đánh giá rủi ro tín dụng cho doanh nghiệp SME, sử dụng Logistic Regression và Random Forest.  
**Kết quả:** Điểm B+, accuracy 73%

**Bối cảnh:**  
Cô giáo dạy môn Quản trị rủi ro tín dụng là người từng làm việc ở VietinBank 15 năm. Cô nói rằng đây là lĩnh vực "hát cơm" của ngành ngân hàng, quyết định sự sống còn của ngân hàng. Vì thế mình muốn tìm hiểu sâu hơn về cách đánh giá rủi ro tín dụng.

**Vấn đề đặt ra:**  
Doanh nghiệp nhỏ và vừa (SME) chiếm 97% tổng số doanh nghiệp ở Việt Nam nhưng chỉ tiếp cận được 30% nguồn vốn tín dụng ngân hàng. Một trong những lý do chính là khó khăn trong đánh giá rủi ro do thiếu thông tin tài chính minh bạch.

**Mục tiêu dự án:**
1. Xây dựng mô hình đơn giản để đánh giá rủi ro SME
2. Sử dụng cả yếu tố tài chính và phi tài chính
3. Tạo công cụ hỗ trợ ra quyết định cho nhân viên tín dụng

**Dữ liệu sử dụng:**
- **Nguồn:** Tổng hợp từ 150 hồ sơ vay SME thực tế (cô giáo cung cấp, đã được anonymize)
- **Thời gian:** Giai đoạn 2020-2023
- **Kết quả:** 45 trường hợp default, 105 trường hợp performing

**Biến số đầu vào:**

*Biến tài chính:*
- Tỉ lệ thanh toán hiện hành (Current Ratio)
- Tỉ lệ thanh toán nhanh (Quick Ratio) 
- Tỉ lệ nợ trên tổng tài sản (Debt-to-Assets)
- Rôa tài sản (ROA)
- Tốc độ luay chuyển hàng tồn kho
- Tốc độ thu tiền khách hàng

*Biến phi tài chính:*
- Tuổi của doanh nghiệp (năm hoạt động)
- Quy mô doanh nghiệp (số nhân viên)
- Ngành nghề kinh doanh
- Vị trí địa lý (tỉnh thành)
- Lịch sử quan hệ với ngân hàng
- Trình độ học vấn của giám đốc

**Phương pháp phân tích:**

*Bước 1: Khám phá và làm sạch dữ liệu*
```python
# Xử lý missing values
# Phát hiện outliers
# Chuẩn hóa dữ liệu
```

*Bước 2: Phân tích tương quan và lựa chọn biến*
- Sử dụng correlation matrix để loại bỏ biến có multicollinearity
- Chi-square test cho biến category
- Feature importance từ Random Forest

*Bước 3: Xây dựng mô hình*
- Logistic Regression (mô hình chính)
- Random Forest (so sánh)
- Decision Tree (để hiểu business logic)

*Bước 4: Đánh giá mô hình*
- Train/Test split: 70/30
- Cross-validation 5-fold
- Metrics: Accuracy, Precision, Recall, F1-score, AUC-ROC

**Kết quả chính:**

*Hiệu suất mô hình:*
- Accuracy: 73% (chấp nhận đưức cho mô hình đầu tiên)
- Precision: 68% 
- Recall: 71%
- AUC-ROC: 0.78

*Biến quan trọng nhất:*
1. Tỉ lệ nợ trên tổng tài sản (hệ số -2.34)
2. ROA (hệ số -1.87)
3. Tuổi doanh nghiệp (hệ số -1.23)
4. Tỉ lệ thanh toán hiện hành (hệ số -0.95)

*Hàm điểm tín dụng:*
```
Credit Score = 100 - (2.34*Debt_Ratio + 1.87*ROA + 1.23*Age + 0.95*Current_Ratio + ...)
```
Từ 0-100, điểm càng cao rủi ro càng thấp.

**Thử nghiệm với dữ liệu mới:**
Mình đã test mô hình với 20 case studies mà cô giáo đưa thêm. Kết quả dự đoán đúng 15/20 trường hợp.

**Ứng dụng thực tiễn:**
- Tạo Excel template để nhân viên tín dụng nhập thông tin
- Kết quả hiển thị điểm tín dụng và khuyến nghị (Chấp thuận/ Từ chối/ Cần thêm thông tin)

**Hạn chế và hướng phát triển:**
- Mẫu dữ liệu còn nhỏ, chưa đại diện
- Chưa tích hợp dữ liệu macro kinh tế
- Cần cập nhật mô hình định kỳ theo thị trường
- Có thể phát triển thành web app với Flask

**Bài học rút ra:**
- Kỹ năng sử dụng Python cho Machine Learning cơ bản
- Hiểu biết về rủi ro tín dụng trong thực tế
- Quan trọng của việc kết hợp yếu tố định tính và định lượng
- Machine Learning không phải "đạn bạc thần kỳ" - cần hiểu business để giải thích kết quả

**Kết quả:** Được điểm B+ cho dự án cuối kỳ

---

### 3. Báo cáo Vĩ mô Việt Nam Q3/2024

**Thời gian thực hiện:** Tháng 9 - Tháng 11/2024  
**Nhóm thực hiện:** 3 người (FBN Club)  
**Mục đích:** Hoạt động nghiên cứu của câu lạc bộ Future Bankers

**Bối cảnh:**  
Cuối năm 2024, kinh tế Việt Nam gặp nhiều thách thức: lạm phát tăng, USD mạnh lên, FDI giảm. Câu lạc bộ Future Bankers muốn thực hiện một báo cáo để hỗ trợ sinh viên có cái nhìn toàn diện về tình hình kinh tế.

**Phạm vi báo cáo:**

*1. Tình hình vĩ mô:*
- Tăng trưởng GDP và các thành phần
- Lạm phát và chỉ số giá cả tiêu dùng (CPI)
- Thương mại quốc tế (xuất khẩu, nhập khẩu)
- Đầu tư trực tiếp nước ngoài (FDI)

*2. Thị trường tài chính:*
- Tỷ giá VND/USD và các đồng tiền khu vực
- Lãi suất tiền gửi và cho vay
- Tăng trưởng tín dụng ngân hàng
- Tiền tệ và thanh khoản thị trường

*3. Chính sách kinh tế:*
- Chính sách tiền tệ của NHNN
- Chính sách tài khóa của Chính phủ
- Các gói hỗ trợ doanh nghiệp và người dân

**Quá trình nghiên cứu:**

*Giai đoạn 1: Thu thập dữ liệu (tháng 9)*
- Tổng cục Thống kê: GDP, CPI, thương mại
- Ngân hàng Nhà nước: Lãi suất, tỷ giá, tín dụng
- Bộ Kế hoạch Đầu tư: FDI, đầu tư công
- Nghiên cứu của các tổ chức quốc tế: WB, ADB, IMF

*Giai đoạn 2: Phân tích và đánh giá (tháng 10)*
Mình phụ trách phần phân tích thị trường ngoại hối và chính sách tiền tệ:

- Ảnh hưởng của Fed tăng lãi suất đến VND
- So sánh chính sách NHNN với các nước ASEAN
- Dự báo tỷ giá và lạm phát 6 tháng cuối năm

*Thách thức gặp phải:*
- Dữ liệu của NHNN thường cập nhật chậm 1-2 tháng
- Khó khăn trong việc dự báo do tình hình quốc tế biến động nhanh
- Thiếu dữ liệu high-frequency (hàng ngày/tuần) cho một số chỉ tiêu

*Giai đoạn 3: Viết báo cáo (tháng 11)*
- Tổng hợp và so sánh với dự báo của các tổ chức khác
- Tạo biểu đồ và infographic minh họa
- Review và edit bởi thầy cô của FBN

**Những phát hiện chính:**

*Về tỷ giá:*
- VND mất giá 7.8% so với đầu năm (thấp hơn dự kiến 10%)
- Áp lực từ USD mạnh và dòng vốn rời khỏi các nước đang phát triển
- NHNN can thiệp tích cực, bán USD để ổn định thị trường

*Về lạm phát:*
- CPI điều chỉnh tăng 4.1% so với cùng kỳ 2023 (vượt mục tiêu 3-4%)
- Yếu tố chính: Tăng giá xăng dầu, điện, nước và giá lương thực thức phẩm
- NHNN đã tăng lãi suất điều hành 2 lần trong Q3

*Về tăng trưởng:*
- GDP Q3 tăng 5.3% (thấp hơn mục tiêu 6-6.5%)
- Khu vực công nghiệp phục hồi chậm do đơn hàng xuất khẩu giảm
- Dịch vụ và du lịch phục hồi tốt

**Dự báo và khuyến nghị:**

*2 kịch bản cho Q4/2024:*

1. **Kịch bản cơ sở (xác suất 60%):**
   - Tỷ giá VND/USD hồi phục nhẹ xuống 24.800-25.000
   - Lạm phát giảm xuống 3.5-3.8% 
   - GDP cả năm đạt 5.8-6.0%

2. **Kịch bản tiêu cực (xác suất 40%):**
   - Áp lực tỷ giá tiếp diễn, VND/USD vượt ngưỡng 25.500
   - Lạm phát duy trì trên 4% do giá nhập khẩu tăng
   - GDP cả năm chỉ đạt 5.5%

*Khuyến nghị cho nhà đầu tư cá nhân:*
- Đa dạng hóa danh mục đầu tư, tăng tỉ trọng USD và vàng
- Thận trọng với đầu tư bất động sản do thị trường khó dự đoán
- Tận dụng lãi suất tiết kiệm cao hiện tại

**Feedback và kết quả:**
- Báo cáo 35 trang được đăng trên fanpage FBN
- Nhận được 200+ like và 20+ comment tích cực
- Có 3 bạn sinh viên khác nhắn tin hỏi thêm về phương pháp dự báo tỷ giá
- Một anh làm trướng phòng ở VietcomBank comment khen nhóm phân tích khéo léo
- Được chọn làm 1 trong 3 báo cáo hay nhất của FBN năm 2024

**Bài học rút ra:**
- Hiểu sâu về cơ chế hoạt động của kinh tế vĩ mô
- Kỹ năng thu thập và phân tích dữ liệu nhiều nguồn
- Tầm quan trọng của context quốc tế trong phân tích kinh tế trong nước
- Khả năng viết báo cáo chuyên nghiệp và trình bày rõ ràng
- Làm việc nhóm và phân chia công việc hiệu quả

**Hướng phát triển:**
- FBN kế hoạch làm báo cáo hàng quý, mình được chọn làm trưởng nhóm cho báo cáo Q1/2025
- Dự định thêm phần phân tích sentiment từ tin tức và mạng xã hội
- Muốn hợp tác với các FBN chapter ở trường khác để có góc nhìn đa chiều hơn

## Cuộc thi

### FTU Innovation Challenge - Business Plan Competition 2024

**Thời gian thi:** Tháng 4 - Tháng 6/2024  
**Số đội tham gia:** 47 đội  
**Nhóm:** 4 người (2 Tài chính, 1 IT, 1 Marketing)  
**Vai trò:** Thành viên nhóm (phụ trách phân tích tài chính và mô hình kinh doanh)

**Đề tài:** "GreenCredit: Nền tảng kết nối tín dụng xanh cho startup bền vững"

**Bối cảnh hình thành ý tưởng:**  
Khi học về ESG (Environmental, Social, Governance) trong môn Tài chính Bền vững, nhóm phát hiện rằng nhiều startup có ý tưởng tốt về kinh tế tuần hoàn nhưng khó tiếp cận vốn vì:
- Ngân hàng truyền thống chưa có khung đánh giá phù hợp cho mô hình mới
- Startup thiếu kiến thức về các tiêu chí ESG
- Nhà đầu tư khó đánh giá tác động môi trường thực tế

**Mô tả giải pháp:**

*1. Nền tảng kết nối:*
- Website/app để startup đăng ký và trình bày dự án
- Ngân hàng và nhà đầu tư có thể tìm kiếm và đánh giá dự án
- Hệ thống matching tự động dựa trên métɹc ESG

*2. Khung đánh giá GreenScore:*

Nhóm đã nghiên cứu và đề xuất một hệ thống điểm 100 dựa trên 5 tiêu chí:
- **Tác động môi trường (30%):** Giảm phát thải carbon, tái sử dụng nước, giảm rác thải
- **Khả thi tài chính (25%):** Dự đoán doanh thu, chi phí, thời gian hòa vốn
- **Đội ngũ và quản trị (20%):** Kinh nghiệm founder, cơ cấu tổ chức, quản lý rủi ro
- **Thị trường và khách hàng (15%):** Quy mô thị trường, độ phủ khách hàng tiềm năng
- **Độ sáng tạo (10%):** Công nghệ mới, mô hình kinh doanh khác biệt

*3. Dịch vụ hỗ trợ:*
- Tu vấn ESG cho startup
- Đào tạo kỹ năng pitch cho startup
- Hỗ trợ làm hồ sơ vay vốn/gọi vốn
- Báo cáo tác động môi trường định kỳ

**Phân tích thị trường:**  
Mình được phân công làm phần này, dựa trên:
- Báo cáo của VCCI về startup Việt Nam
- Dữ liệu FDI vào lĩnh vực công nghệ sạch
- Khảo sát 50 startup tại Hanoi và HCMC

*Kết quả phân tích:*
- Thị trường startup Việt Nam: 3.000+ doanh nghiệp
- Startup có yếu tố bền vững: khoảng 12-15%
- Tổng nhu cầu vốn: 2,5 tỉ USD/năm
- Tỉ lệ startup thành công tiếp cận vốn ngân hàng: chỉ 8%

**Mô hình kinh doanh và dự đoán tài chính:**

*Nguồn thu:*
1. Phí dịch vụ từ startup: 2-5% giá trị khoản vay/đầu tư
2. Phí thành viên từ ngân hàng/quỹ: 50-200 triệu VND/năm
3. Phí tu vấn ESG: 20-50 triệu VND/dự án
4. Phí quảng cáo và sự kiện: 500 triệu VND/năm

*Dự đoán 3 năm đầu:*
- Năm 1: Lỗ 50 triệu (phát triển sản phẩm)
- Năm 2: Lãi 200 triệu 
- Năm 3: Lãi 1,2 tỉ VND

**Quá trình chuẩn bị cuộc thi:**

*Giai đoạn 1 (tháng 4):* Brainstorming và nghiên cứu
- Mỗi người đưa 3-5 ý tưởng, vote chọn ra 2 ý tưởng hay nhất
- Phân công: Mình + 1 bạn làm phần tài chính, 1 bạn IT làm sản phẩm, 1 bạn Marketing làm chiến lược
- Survey online 200 sinh viên và 50 startup để validate ý tưởng

*Giai đoạn 2 (tháng 5):* Làm kế hoạch kinh doanh chi tiết
- Tạo prototype trên Figma (bạn IT làm, mình hỗ trợ)
- Phân tích đối thủ cạnh tranh (không có startup nào tương tự ở Việt Nam)
- Interview 5 ngân hàng và 3 quỹ đầu tư để hiểu nhu cầu thực tế

*Giai đoạn 3 (tháng 6):* Chuẩn bị pitch và thi
- Làm slide thuyết trình (80% của điểm số)
- Luyện pitch trước bạn bè và thầy cô 5 lần
- Chuẩn bị câu hỏi Q&A từ ban giám khảo

**Ngày thi (20/6/2024):**

*Vòng sơ loại (47 đội → 15 đội):*
- Nộp báo cáo business plan 20 trang
- Thuyết trình 10 phút + 5 phút Q&A
- Được chọn vào vòng 15 (nhóm đứng thứ 11)

*Vòng chung kết (15 đội → 5 đội):*
- Thuyết trình lại trước 150+ khán giả và 3 giám khảo là CEO ngân hàng
- 15 phút thuyết trình + 10 phút Q&A gay gắt
- Kết quả: vào Top 5 (giải Khấn khích)

**Câu hỏi khó từ ban giám khảo:**

1. *"Làm sao đảm bảo startup không fake ESG metrics?"*
   - Trả lời: Hệ thống kiểm tra độc lập, hợp tác với các tổ chức xác thực ESG quốc tế

2. *"Tại sao ngân hàng không tự làm mà phải qua platform của bạn?"*
   - Trả lời: Ngân hàng thiếu chuyên môn ESG, platform giúp giảm chi phí đánh giá và tăng hiệu quả

3. *"Revenue model có sustainable không khi cạnh tranh gia tăng?"*
   - Trả lời: First-mover advantage, xây dựng network effect mạnh, mở rộng sang các nước ASEAN

**Kết quả và phần thưởng:**
- **Thứ hạng:** Vào vòng 2 (Top 15/47 đội), sau đó vào Top 5 chung kết
- **Giải thưởng:** Giải Khấn khích + 5 triệu VND tiền mặt
- **Giải đặc biệt:** "Best ESG Integration" từ đối tác Ngân hàng BIDV
- **Cơ hội:** Được mời tham gia hackathon của Techcombank tháng 10/2024

**Feedback từ ban giám khảo:**

*Điểm mạnh:*
- Ý tưởng sáng tạo và phù hợp xu hướng phát triển bền vững
- Phân tích thị trường chi tiết và có cụ thể
- Prototype sản phẩm rõ ràng, dễ hiểu
- Team có chemistry tốt, trả lời sắp sắp

*Điểm cần cải thiện:*
- Dự đoán tài chính hơi lạc quan, cần conservative hơn
- Chưa phân tích sâu rủi ro pháp lý và quy định của NHNN
- Marketing strategy chưa đủ cụ thể cho giai đoạn launch

**Bài học cá nhân:**
- Kỹ năng làm việc nhóm và điều phối công việc
- Hiểu sâu hơn về startup ecosystem và fintech
- Kỹ năng thuyết trình trước đông người và trả lời câu hỏi khó
- Tầm quan trọng của market research thật kỹ càng
- ESG không chỉ là "xu hướng" mà là yêu cầu thực sự của thị trường

**Hướng phát triển tiếp theo:**
- 2 ngân hàng đã liên hệ hỏi về khả năng hợp tác pilot
- Đăng ký tham gia cuộc thi FPT Digital Transformation Awards 2025
- Tìm kiếm mentor và angel investor để thực sự xây dựng sản phẩm

**Trải nghiệm đáng nhớný:**
- Lần đầu tiên đứng trước 150+ người thuyết trình - run rẩy đôi chân!
- Giám đốc BIDV hỏi thẳng thông tin contact của nhóm sau cuộc thi
- Được phỏng vấn của báo Đại học FTU và đăng ký ảnh đáng yêu đứng cùng cúp trên Facebook trường

## Chứng chỉ & Giải thưởng

### Chứng chỉ hoàn thành khóa học
**Financial Data Analysis and Decision Making in the advent of AI**  
**Thời gian:** Tháng 2/2026  
**Tổ chức:** [Tên tổ chức phát hành]  
**Nội dung:** Phân tích dữ liệu tài chính và ra quyết định trong bối cảnh phát triển của trí tuệ nhân tạo

### Thành tích cuộc thi
**Vũ trụ đồng tiền 2026 - Vòng casting cấp trường**  
**Kết quả:** Top 6 thí sinh xuất sắc  
**Thời gian:** Tháng 3/2026  
**Đơn vị tổ chức:** Đại học Ngoại thương Hà Nội

## Kỹ năng

### Kỹ năng chuyên môn
- **Phân tích Tài chính:** Cơ bản (65%)
- **Excel & Power BI:** Trung bình (70%)
- **Python:** Mới học (45%)
- **Nghiên cứu:** Trung bình (60%)
- **Kế hoạch Kinh doanh:** Cơ bản (55%)

### Kỹ năng mềm
- **Tiếng Anh:** IELTS 6.5 (75%)
- **Thuyết trình:** Trung bình (65%)
- **Làm nhóm:** Khá (80%)

## Liên hệ

**Email:** ngocha250706@gmail.com  
**Facebook:** [ngoc.ha.250706](https://www.facebook.com/ngoc.ha.250706)  
**Instagram:** [@ntngcha](https://www.instagram.com/ntngcha/)  

---

*Mình sẵn sàng kết nối cho các cơ hội thực tập và hợp tác nghiên cứu*

---

**Bản quyền:** © 2024 Nguyen Thi Ngoc Ha. Sinh viên Đại học Ngoại thương - Tài chính Ngân hàng.