# 🌳 SKILL TREE: Machine Learning Engineer
### Lộ trình cá nhân hóa — Từ học sinh lớp 12 đến ML Engineer | CN20 UET

> **Cách dùng file này:** Mỗi node có 4 phần — *Vì sao quan trọng*, *Cần học gì*, *Link miễn phí*, *Definition of Done* (tiêu chí coi như "qua node"). Tick `[x]` khi hoàn thành để track tiến độ. Đừng cố học tuyến tính 100% — nhiều node ở Giai đoạn 2 học **song song** vì chúng bổ trợ lẫn nhau.

---

## 📍 GIAI ĐOẠN 1 — PRE-UET (Hè 2026, ~10-12 tuần)
**Mục tiêu:** Có tư duy lập trình vững, trực giác Toán cho ML, và một mini-project hoàn chỉnh để tự tin bước vào năm nhất.

### 1.1. Python tinh gọn cho Data/ML (không học Python "kiểu web dev")
- **Vì sao:** Python là ngôn ngữ "giao tiếp" với mọi thư viện ML sau này. Học đúng trọng tâm (list/dict comprehension, OOP cơ bản, xử lý file) thay vì lan man.
- **Cần học gì:** Cú pháp cơ bản, list/tuple/dict, comprehension, function, class cơ bản, exception handling, làm việc với file CSV/JSON.
- **Link miễn phí:**
  - [CS50P – Harvard's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — chuẩn nhất cho người mới, có bài tập chấm tự động
  - [Python Official Tutorial](https://docs.python.org/3/tutorial/) — tra cứu chính thống
  - [freeCodeCamp – Python for Everybody](https://www.freecodecamp.org/learn/scientific-computing-with-python/) — thực hành nhiều
- **Definition of Done:** Viết được script đọc 1 file CSV, lọc/biến đổi dữ liệu, xuất kết quả ra file mới — không tra Google quá 3 lần.
- [ ] Hoàn thành

### 1.2. Tư duy thuật toán nền tảng (Algorithmic Thinking)
- **Vì sao:** ML Engineer không chỉ gọi `.fit()` — phải hiểu *Time/Space Complexity* để biết tại sao model chậm, tại sao OOM (out of memory). Đây là nền cho Cấu trúc dữ liệu & Giải thuật năm nhất.
- **Cần học gì:** Big-O notation, mảng, chuỗi, đệ quy, sắp xếp/tìm kiếm cơ bản.
- **Link miễn phí:**
  - [NeetCode 150 (free roadmap + giải thích trực quan)](https://neetcode.io/roadmap)
  - [Visualgo – trực quan hóa thuật toán](https://visualgo.net/) — cực hợp với "Nguyên lý Tảng băng trôi"
  - [MIT 6.006 Introduction to Algorithms (OCW)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)
- **Definition of Done:** Giải được 20-30 bài Easy/Medium trên LeetCode hoặc NeetCode, tự giải thích được Big-O của code mình viết.
- [ ] Hoàn thành

### 1.3. Trực giác Đại số tuyến tính cho ML (không phải Đại số tuyến tính hàn lâm)
- **Vì sao:** Mọi dữ liệu trong ML (ảnh, văn bản, bảng số) đều là **vector/matrix**. Hiểu hình học của phép nhân ma trận = hiểu được Neural Network đang "làm gì" về mặt không gian.
- **Cần học gì:** Vector, ma trận, phép nhân ma trận (góc nhìn hình học: xoay/scale không gian), eigenvector/eigenvalue (trực giác, chưa cần chứng minh).
- **Link miễn phí:**
  - [3Blue1Brown – Essence of Linear Algebra (YouTube playlist)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) — **bắt buộc xem**, đúng tinh thần "tảng băng trôi"
  - [Khan Academy – Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
- **Definition of Done:** Giải thích được bằng lời (không cần công thức) vì sao nhân ma trận là một phép biến đổi không gian.
- [ ] Hoàn thành

### 1.4. Trực giác Giải tích & Xác suất cho ML
- **Vì sao:** *Gradient Descent* (thuật toán học của hầu hết model ML) chính là đạo hàm. *Loss Function* là một bài toán tối ưu em đã quen từ Giải tích lớp 12 (tìm cực trị).
- **Cần học gì:** Đạo hàm (ôn lại, liên hệ slope), đạo hàm riêng phần (partial derivative), khái niệm phân phối xác suất cơ bản (đã có nền từ Toán THPT).
- **Link miễn phí:**
  - [3Blue1Brown – Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
  - [StatQuest with Josh Starmer (YouTube) – Statistics Fundamentals](https://www.youtube.com/c/joshstarmer) — kênh huyền thoại, giải thích cực dễ hiểu
  - [Khan Academy – Statistics & Probability](https://www.khanacademy.org/math/statistics-probability)
- **Definition of Done:** Tự vẽ được trên giấy minh họa Gradient Descent đi xuống "thung lũng" loss như thế nào.
- [ ] Hoàn thành

### 1.5. Mini-Project tổng hợp Giai đoạn 1
- **Vì sao:** "Học qua dự án" — gắn kết toàn bộ kiến thức trên thành sản phẩm cụ thể.
- **Gợi ý dự án:** Xử lý ảnh grayscale bằng mảng 2 chiều thuần Python/NumPy (không dùng thư viện ML) — đúng tinh thần "dạy mảng 2D qua xử lý ảnh" trong roadmap của em.
- **Link tham khảo:** [NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html)
- **Definition of Done:** Code chạy được, có docstring, README mô tả, đẩy lên GitHub cá nhân.
- [ ] Hoàn thành

---

## 📍 GIAI ĐOẠN 2 — NĂM NHẤT UET (song hành các môn cơ sở ngành)
**Mục tiêu:** Không học lý thuyết suông — mỗi môn nặng ở trường đều có một "cánh cửa" ứng dụng trực tiếp vào ML.

### 2.1. Đại số tuyến tính (môn ĐHQGHN) → ứng dụng ML
- **Vì sao:** Học sâu hơn Giai đoạn 1 — SVD, PCA dùng để giảm chiều dữ liệu, là nền của Recommendation System và Computer Vision cổ điển.
- **Link miễn phí:**
  - [MIT 18.06 Linear Algebra – Gilbert Strang (OCW)](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — kinh điển
  - [StatQuest – PCA giải thích trực quan](https://www.youtube.com/watch?v=FgakZw6K1QQ)
- **Ứng dụng thực chiến:** Tự code PCA từ đầu bằng NumPy (không dùng `sklearn.PCA`), áp dụng nén 1 bộ ảnh.
- [ ] Hoàn thành

### 2.2. Giải tích (Calculus 2/3) → Backpropagation
- **Vì sao:** *Backpropagation* — thuật toán lõi để train Neural Network — chính là Chain Rule áp dụng hàng triệu lần.
- **Link miễn phí:**
  - [3Blue1Brown – Backpropagation calculus](https://www.youtube.com/watch?v=tIeHLnjs5U8)
  - [MIT 18.01/18.02 Calculus (OCW)](https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/)
- **Ứng dụng thực chiến:** Tự code một mạng neural 2-layer "from scratch" chỉ bằng NumPy, tự viết backprop bằng tay.
- [ ] Hoàn thành

### 2.3. Xác suất thống kê → Model Evaluation & Bayesian thinking
- **Vì sao:** Hiểu vì sao model "overfit", cách đọc *Confusion Matrix*, *p-value*, hay vì sao Naive Bayes hoạt động — tất cả đều là Xác suất thống kê ứng dụng.
- **Link miễn phí:**
  - [Harvard Stat 110 – Probability (free, có trên YouTube/edX)](https://projects.iq.harvard.edu/stat110/home)
  - [StatQuest – toàn bộ playlist Statistics Fundamentals](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9)
- [ ] Hoàn thành

### 2.4. Cấu trúc dữ liệu & Giải thuật (CTDL&GT) → Tối ưu hiệu năng ML
- **Vì sao:** Khi dữ liệu lên hàng triệu dòng, hiểu Hash Table/Tree/Graph quyết định code chạy 1 giây hay treo máy. Đây cũng là môn quyết định em có pass được phỏng vấn ML Engineer hay không.
- **Link miễn phí:**
  - [MIT 6.006 Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)
  - [NeetCode 150](https://neetcode.io/roadmap) (tiếp tục từ Giai đoạn 1, nâng độ khó)
- [ ] Hoàn thành

### 2.5. Nhập môn Machine Learning cổ điển (song song, không chờ hết năm nhất)
- **Vì sao:** Học sớm sẽ giúp các môn cơ sở ngành ở trên có "đất dụng võ" ngay lập tức thay vì học chay.
- **Link miễn phí:**
  - [Andrew Ng – Machine Learning Specialization (Coursera, audit miễn phí)](https://www.coursera.org/specializations/machine-learning-introduction)
  - [Stanford CS229 – Machine Learning (bài giảng đầy đủ, miễn phí)](https://cs229.stanford.edu/)
  - [Scikit-learn User Guide (tài liệu chính thức)](https://scikit-learn.org/stable/user_guide.html)
- **Ứng dụng thực chiến:** Làm [Kaggle Titanic Survival Prediction](https://www.kaggle.com/c/titanic) — bài toán "Hello World" của ML.
- [ ] Hoàn thành

---

## 📍 GIAI ĐOẠN 3 — NĂM 2 TRỞ ĐI: CHUYÊN SÂU MLE
**Mục tiêu:** Từ "biết ML" sang "triển khai ML thật trong production" — đây là điểm phân biệt ML Engineer với người chỉ biết chạy notebook.

### 3.1. Xử lý dữ liệu lớn (Pandas → Spark)
- **Vì sao:** Dữ liệu thật không bao giờ sạch sẵn. Pandas xử lý dữ liệu vừa, Spark xử lý dữ liệu không vừa RAM.
- **Link miễn phí:**
  - [Kaggle Learn – Pandas](https://www.kaggle.com/learn/pandas)
  - [Spark by Examples – PySpark Tutorial](https://sparkbyexamples.com/pyspark-tutorial/)
  - [Databricks Academy (free tier courses)](https://www.databricks.com/learn/training/home)
- [ ] Hoàn thành

### 3.2. Thư viện ML nền tảng: NumPy + Scikit-learn (đào sâu)
- **Vì sao:** Hiểu *Vectorization* — vì sao code NumPy nhanh hơn vòng lặp Python hàng trăm lần — là kỹ năng tối ưu hiệu năng cốt lõi của MLE.
- **Link miễn phí:**
  - [NumPy Official Documentation](https://numpy.org/doc/stable/)
  - [Scikit-learn – toàn bộ User Guide + Examples](https://scikit-learn.org/stable/auto_examples/index.html)
- [ ] Hoàn thành

### 3.3. Deep Learning với PyTorch
- **Vì sao:** PyTorch là chuẩn công nghiệp hiện tại (Meta, OpenAI, hầu hết research lab dùng). Học PyTorch thay vì TensorFlow để dễ chuyển sang công việc thực tế và đọc paper.
- **Link miễn phí:**
  - [PyTorch Official Tutorials – Learn the Basics](https://pytorch.org/tutorials/beginner/basics/intro.html)
  - [fast.ai – Practical Deep Learning for Coders](https://course.fast.ai/) — top-down, học bằng code trước lý thuyết sau, rất hợp gu "project-based" của em
  - [Stanford CS231n – Convolutional Neural Networks for Visual Recognition](https://cs231n.stanford.edu/) (notes: [cs231n.github.io](https://cs231n.github.io/)) — chuẩn vàng cho Computer Vision
  - [Jay Alammar – The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) — bắt buộc đọc khi vào NLP/LLM
- **Ứng dụng thực chiến:** Train một CNN phân loại ảnh trên CIFAR-10, sau đó thử fine-tune một pretrained model (transfer learning).
- [ ] Hoàn thành

### 3.4. MLOps: Đưa model từ Notebook ra Production
- **Vì sao:** Đây là phần phân biệt rõ nhất "Data Scientist" và "ML Engineer". 90% giá trị thực tế của ML nằm ở việc deploy và maintain model, không phải ở việc train nó.
- **Cần học gì:** Git/GitHub (versioning code), Docker (đóng gói môi trường), CI/CD cơ bản, model serving (API hóa model), giám sát model trên production.
- **Link miễn phí:**
  - [DeepLearning.AI – Machine Learning Engineering for Production (MLOps) Specialization (audit miễn phí)](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops)
  - [Made With ML – MLOps Course (hoàn toàn miễn phí, mã nguồn mở)](https://madewithml.com/)
  - [DataTalksClub – MLOps Zoomcamp (free, có GitHub repo đầy đủ)](https://github.com/DataTalksClub/mlops-zoomcamp)
  - [Docker Official Get Started Guide](https://docs.docker.com/get-started/)
- **Ứng dụng thực chiến:** Đóng gói 1 model (từ mục 3.3) thành API bằng FastAPI, containerize bằng Docker, deploy thử lên một free tier (Render/Railway/HuggingFace Spaces).
- [ ] Hoàn thành

### 3.5. Capstone: Project tổng hợp cuối lộ trình
- **Vì sao:** Một project end-to-end là thứ chứng minh năng lực rõ ràng nhất khi đi xin internship/việc làm — quan trọng hơn nhiều so với việc liệt kê đã học khóa nào.
- **Gợi ý:** Chọn 1 bài toán thật (vd: dự đoán giá nhà Hà Nội từ dữ liệu crawl thật) → thu thập data → EDA → train model → đóng gói API → viết README chuẩn GitHub.
- **Link tham khảo thêm:** [Made With ML – Full MLOps course đi từ project thật](https://madewithml.com/#course)
- [ ] Hoàn thành

---

## 🗺️ Cách dùng file này hiệu quả
1. Mỗi tuần hè, chọn 1-2 node ở Giai đoạn 1, không ôm đồm.
2. Khi vào UET, đối chiếu node ở Giai đoạn 2 với đúng môn học trên lớp — học "kép": vừa hiểu lý thuyết thầy cô dạy, vừa thấy ứng dụng ML ngay lập tức.
3. Mỗi node hoàn thành, quay lại hỏi Claude để được ra **bài tập thử thách** theo đúng format: Kiến thức cốt lõi → Ví dụ thực chiến → Cạm bẫy → Challenge.
4. Đừng nhảy cóc sang Giai đoạn 3 quá sớm nếu Giai đoạn 1-2 chưa vững — MLOps vô nghĩa nếu chưa hiểu model đang làm gì.

---
*File này là bản đồ sống — quay lại bất cứ lúc nào để Claude cập nhật, mở rộng, hoặc đi sâu vào từng node.*
