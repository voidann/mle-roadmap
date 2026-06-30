# 🌳 SKILL TREE: Machine Learning Engineer
### Lộ trình cá nhân hóa — Từ học sinh lớp 12 đến ML Engineer | CN20 UET

> **Cách đọc file này:**
> - Mỗi checklist item có 3 phần: **[Số thứ tự ưu tiên]** → **Resource cụ thể (tên bài/video/trang)** → **✓ Tiêu chí done**
> - Số thứ tự ưu tiên: `P1` = học trước tiên (blocking), `P2` = học sau P1, `P3` = học sau P2, `[optional]` = không bắt buộc nhưng có ích
> - Tick `[x]` khi đạt được đúng tiêu chí done — không phải khi chỉ đọc xong
> - Giai đoạn 2-5 ở mức tổng quan, sẽ được bổ sung chi tiết khi đến gần

---

## 📍 GIAI ĐOẠN 1 — PRE-UET (Hè 2026, ~10-12 tuần)
**Mục tiêu:** Có tư duy lập trình vững, trực giác Toán cho ML, và một mini-project hoàn chỉnh để tự tin bước vào năm nhất.

---

### 1.1. Python tinh gọn cho Data/ML
> **Nguồn học chính:** CS50P (Harvard) — https://cs50.harvard.edu/python/
> Học theo đúng thứ tự Lecture 0 → Lecture 9 của CS50P. Mỗi Lecture có bài tập chấm tự động — **bắt buộc làm bài tập**, không chỉ xem video.

#### Nhóm A — Nền tảng bắt buộc (P1, học trong 2 tuần đầu)

- [ ] **P1 | Biến và kiểu dữ liệu cơ bản**
  - Resource: CS50P Lecture 0 "Functions, Variables" (https://cs50.harvard.edu/python/2022/weeks/0/)
  - ✓ Done khi: Viết được chương trình nhận tên người dùng từ bàn phím, in ra lời chào có tên, không nhìn tài liệu

- [ ] **P1 | Toán tử và biểu thức điều kiện (`if`/`elif`/`else`)**
  - Resource: CS50P Lecture 1 "Conditionals" (https://cs50.harvard.edu/python/2022/weeks/1/)
  - ✓ Done khi: Giải được bài tập "Deep Thought" và "Home Federal Savings Bank" trong Problem Set 1 mà không xem solution

- [ ] **P1 | Vòng lặp `for` và `while`**
  - Resource: CS50P Lecture 2 "Loops" (https://cs50.harvard.edu/python/2022/weeks/2/)
  - ✓ Done khi: Viết được chương trình in bảng cửu chương 1-10 bằng cả `for` lẫn `while`, giải thích được sự khác biệt khi nào dùng cái nào

- [ ] **P1 | Hàm (function): định nghĩa, tham số, return value**
  - Resource: CS50P Lecture 0 phần "def" + Lecture 3 "Exceptions" (https://cs50.harvard.edu/python/2022/weeks/3/)
  - ✓ Done khi: Viết được hàm tính BMI nhận `weight` và `height` làm tham số, return kết quả và phân loại (Underweight/Normal/Overweight)

- [ ] **P1 | Exception handling: `try`/`except` và các Exception phổ biến**
  - Resource: CS50P Lecture 3 "Exceptions" (https://cs50.harvard.edu/python/2022/weeks/3/)
  - ✓ Done khi: Bắt được đúng `ValueError` khi người dùng nhập không phải số, chương trình tiếp tục chạy thay vì crash — và giải thích được tại sao không dùng `except:` trống

#### Nhóm B — Cấu trúc dữ liệu (P1, học song song hoặc ngay sau nhóm A)

- [ ] **P1 | List: tạo, index, slice, các method cơ bản**
  - Resource: CS50P Lecture 2 phần Lists + Python Docs "Lists" (https://docs.python.org/3/tutorial/introduction.html#lists)
  - ✓ Done khi: Viết được hàm nhận một list điểm số, trả về list chỉ giữ lại điểm >= 5, sắp xếp tăng dần — không dùng thư viện ngoài

- [ ] **P1 | Tuple: khi nào dùng tuple thay list**
  - Resource: Python Docs "Tuples and Sequences" (https://docs.python.org/3/tutorial/datastructures.html#tuples-and-sequences)
  - ✓ Done khi: Giải thích được bằng lời tại sao tọa độ (x, y) nên là tuple, không phải list — liên hệ với khái niệm immutable

- [ ] **P1 | Dictionary: tạo, truy cập, `.get()`, `.items()`, `.keys()`, `.values()`**
  - Resource: CS50P Lecture 3 phần dicts + Python Docs "Dictionaries" (https://docs.python.org/3/tutorial/datastructures.html#dictionaries)
  - ✓ Done khi: Viết được chương trình đếm tần suất xuất hiện của từng từ trong một câu, lưu kết quả vào dict, in ra từ xuất hiện nhiều nhất

- [ ] **P2 | Set và phép toán tập hợp**
  - Resource: Python Docs "Sets" (https://docs.python.org/3/tutorial/datastructures.html#sets)
  - ✓ Done khi: Dùng set để tìm các phần tử xuất hiện trong list A nhưng không xuất hiện trong list B (phép hiệu tập hợp) — 1 dòng code

#### Nhóm C — Python theo tư duy Data/ML (P2, học sau khi vững nhóm A-B)

- [ ] **P2 | List comprehension cơ bản**
  - Resource: CS50P Lecture 4 "Libraries" phần comprehension + Real Python "List Comprehensions" (https://realpython.com/list-comprehension-python/)
  - ✓ Done khi: Viết lại bài tập lọc điểm >= 5 ở nhóm B bằng 1 dòng list comprehension, không dùng vòng lặp for thông thường

- [ ] **P2 | List comprehension có điều kiện lọc (`if` trong comprehension)**
  - Resource: Real Python "List Comprehensions" phần "Conditional Comprehensions" (https://realpython.com/list-comprehension-python/#using-conditional-logic)
  - ✓ Done khi: Từ một list hỗn hợp số và chuỗi, dùng 1 dòng comprehension để lấy ra chỉ những số chẵn

- [ ] **P2 | Dict comprehension**
  - Resource: Real Python "Dict Comprehensions" (https://realpython.com/iterate-over-dictionary-python/#using-comprehensions)
  - ✓ Done khi: Từ một list tên học sinh và một list điểm số tương ứng, tạo ra dict `{tên: điểm}` bằng 1 dòng dict comprehension

- [ ] **P2 | `map()`, `filter()`, `zip()`**
  - Resource: Real Python "Python's map()" (https://realpython.com/python-map-function/) + "Python's filter()" (https://realpython.com/python-filter-function/)
  - ✓ Done khi: Dùng `zip()` để "ghép" list tên và list điểm thành list các tuple (tên, điểm), sau đó dùng `filter()` để lọc ra các học sinh đậu (>= 5.0)

- [ ] **P2 | `lambda` function**
  - Resource: Real Python "Python Lambda Functions" (https://realpython.com/python-lambda/)
  - ✓ Done khi: Dùng `sorted()` với `key=lambda` để sắp xếp list dict học sinh theo điểm số giảm dần — và giải thích được khi nào nên dùng lambda, khi nào nên dùng `def` thông thường

#### Nhóm D — Hàm nâng cao và OOP cơ bản (P2)

- [ ] **P2 | Type hinting**
  - Resource: Real Python "Python Type Checking" phần annotations (https://realpython.com/python-type-checking/#hello-types)
  - ✓ Done khi: Viết lại 3 hàm đã làm ở nhóm A-B với type hinting đầy đủ (tham số và return value), dùng `Optional` từ module `typing` khi hàm có thể trả về `None`

- [ ] **P2 | Docstring chuẩn**
  - Resource: Google Python Style Guide phần Docstrings (https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings)
  - ✓ Done khi: Viết docstring cho 3 hàm ở nhóm A-B theo đúng chuẩn Google style — có mô tả, Args, Returns, Raises (nếu có)

- [ ] **P2 | Tham số mặc định và `*args`, `**kwargs`**
  - Resource: Real Python "Python args and kwargs" (https://realpython.com/python-kwargs-and-args/)
  - ✓ Done khi: Giải thích được bằng lời vấn đề mutable default argument (`def f(x=[])`) và viết được cách sửa đúng — không nhìn tài liệu

- [ ] **P3 | Class cơ bản: `__init__`, `self`, method**
  - Resource: CS50P Lecture 8 "Object-Oriented Programming" (https://cs50.harvard.edu/python/2022/weeks/8/)
  - ✓ Done khi: Viết class `Student` có thuộc tính `name` và `scores` (list), method `average()` trả về điểm trung bình, method `is_passing()` trả về True/False

- [ ] **P3 | Kế thừa (Inheritance) cơ bản**
  - Resource: CS50P Lecture 8 phần inheritance
  - ✓ Done khi: Tạo class `GraduateStudent` kế thừa `Student`, thêm thuộc tính `thesis_score`, override method `is_passing()` với điều kiện khác

#### Nhóm E — Làm việc với file và dữ liệu thật (P2)

- [ ] **P2 | Đọc/ghi file `.txt` và `.csv` bằng thư viện chuẩn**
  - Resource: CS50P Lecture 6 "File I/O" (https://cs50.harvard.edu/python/2022/weeks/6/) + Python Docs "Reading and Writing Files" (https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files)
  - ✓ Done khi: Đọc được file CSV có header, lọc các dòng thỏa điều kiện, ghi kết quả ra file CSV mới — dùng `with open(...)` đúng cách, không để file bị unclosed

- [ ] **P2 | Đọc/ghi file `.json`**
  - Resource: Real Python "Working With JSON Data in Python" (https://realpython.com/python-json/)
  - ✓ Done khi: Đọc một file JSON, chỉnh sửa một trường dữ liệu, ghi lại file với indent=2

- [ ] **P3 | Quản lý môi trường ảo (`venv`) và `pip`**
  - Resource: Real Python "Python Virtual Environments: A Primer" (https://realpython.com/python-virtual-environments-a-primer/)
  - ✓ Done khi: Tạo được `venv` mới, kích hoạt, cài thư viện vào đó, xuất `requirements.txt` bằng `pip freeze`

- [ ] **P3 | Tổ chức code thành nhiều module/file**
  - Resource: Real Python "Python Modules and Packages" (https://realpython.com/python-modules-packages/)
  - ✓ Done khi: Tách code của mini-project thành ít nhất 2 file (vd: `utils.py` chứa hàm phụ trợ, `main.py` chứa logic chính), import đúng cách

#### Nhóm F — Tiêu chuẩn code (P2, áp dụng xuyên suốt)

- [ ] **P2 | Phong cách code PEP 8**
  - Resource: PEP 8 Official (https://peps.python.org/pep-0008/) — đọc các mục: Indentation, Imports, Naming Conventions, Whitespace
  - ✓ Done khi: Cài `flake8` (`pip install flake8`), chạy `flake8` trên toàn bộ code mini-project, không còn warning nào

- [ ] **[optional] | Dùng `black` để auto-format code**
  - Resource: Black documentation (https://black.readthedocs.io/en/stable/)
  - ✓ Done khi: Chạy `black` trên codebase, hiểu được ý nghĩa của từng thay đổi black tự động áp dụng

- **Definition of Done toàn mục 1.1:** Viết được script đọc 1 file CSV thật (vd: dữ liệu điểm học sinh), lọc theo điều kiện, tính thống kê cơ bản, xuất kết quả ra file CSV mới. Code có type hinting, docstring, xử lý lỗi file không tồn tại. Chạy `flake8` không báo lỗi.
- [ ] Hoàn thành toàn bộ mục 1.1

---

### 1.2. Tư duy thuật toán nền tảng (Algorithmic Thinking)
> **Nguồn học chính:** NeetCode Roadmap (https://neetcode.io/roadmap) kết hợp Visualgo (https://visualgo.net/)
> Quy tắc: Với mỗi bài LeetCode, **tự làm ít nhất 20 phút trước khi xem gợi ý**. Sau khi giải xong, bắt buộc phân tích Big-O của solution mình viết.

#### Nhóm A — Nền tảng Big-O (P1, học trước tiên)

- [ ] **P1 | Khái niệm Big-O notation: O(1), O(log n), O(n), O(n log n), O(n²)**
  - Resource: Video "Big-O Notation" của NeetCode trên YouTube (https://www.youtube.com/watch?v=BgLTDT03QtU)
  - ✓ Done khi: Cho một đoạn code Python bất kỳ có 1-2 vòng lặp, tự phân tích được Time Complexity mà không tra Google

- [ ] **P1 | Phân biệt Time Complexity và Space Complexity**
  - Resource: NeetCode video "Big-O" phần Space Complexity (cùng link trên)
  - ✓ Done khi: Giải thích được tại sao một hàm tạo list kết quả có Space Complexity O(n) dù chỉ có 1 vòng lặp

- [ ] **P1 | Phân tích vòng lặp đơn, lồng nhau, và gọi hàm đệ quy**
  - Resource: MIT 6.006 Lecture 1 "Algorithmic Thinking" (https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/pages/lecture-notes/) — đọc lecture notes, không cần xem video dài
  - ✓ Done khi: Tự phân tích được Bubble Sort là O(n²) bằng cách đếm số lần so sánh — không tra Wikipedia

#### Nhóm B — Mảng và Chuỗi (P1)

- [ ] **P1 | Thao tác mảng cơ bản và độ phức tạp từng thao tác**
  - Resource: Visualgo — Array (https://visualgo.net/en/array)
  - ✓ Done khi: Bảng liệt kê được Access/Search/Insert/Delete trên mảng là O(?) và giải thích được tại sao

- [ ] **P1 | Two Pointers pattern**
  - Resource: NeetCode "Two Pointers" playlist (https://neetcode.io/roadmap) — xem phần Two Pointers
  - ✓ Done khi: Tự giải được LeetCode #125 "Valid Palindrome" và #167 "Two Sum II" bằng two pointers, không xem solution

- [ ] **P1 | Sliding Window pattern**
  - Resource: NeetCode "Sliding Window" playlist
  - ✓ Done khi: Tự giải được LeetCode #643 "Maximum Average Subarray I" bằng sliding window — và giải thích tại sao nó tốt hơn brute force O(n²)

- [ ] **P1 | Thao tác chuỗi và vấn đề hiệu năng nối chuỗi trong vòng lặp**
  - Resource: Real Python "Strings and Character Data in Python" phần concatenation (https://realpython.com/python-strings/)
  - ✓ Done khi: Giải thích được tại sao `result = result + char` trong vòng lặp n lần là O(n²) — và dùng `"".join()` để sửa thành O(n)

#### Nhóm C — Đệ quy (P2)

- [ ] **P2 | Đệ quy cơ bản: base case và recursive case**
  - Resource: CS50P Lecture 5 "Unit Tests" — không có đệ quy trực tiếp, dùng: Real Python "Recursion in Python" (https://realpython.com/python-recursion/)
  - ✓ Done khi: Tự viết hàm tính giai thừa (factorial) bằng đệ quy, vẽ tay call stack cho `factorial(4)` trên giấy

- [ ] **P2 | Vẽ call stack và nhận biết Stack Overflow**
  - Resource: Visualgo — Recursion trace (https://visualgo.net/en/recursion)
  - ✓ Done khi: Chạy `factorial(-1)` và giải thích được tại sao Python báo `RecursionError: maximum recursion depth exceeded`

- [ ] **P2 | Fibonacci bằng đệ quy và vấn đề chồng lặp tính toán**
  - Resource: Real Python "Recursion" phần Fibonacci
  - ✓ Done khi: Code được `fib(n)` đệ quy, đo thời gian chạy cho `fib(35)`, giải thích tại sao chậm — và sửa bằng memoization (`@functools.lru_cache`)

#### Nhóm D — Thuật toán tìm kiếm và sắp xếp (P2)

- [ ] **P2 | Linear Search và Binary Search**
  - Resource: Visualgo — Binary Search (https://visualgo.net/en/bst) + LeetCode #704 "Binary Search"
  - ✓ Done khi: Tự code được Binary Search từ đầu (không copy), giải thích tại sao cần mảng đã sắp xếp, và xác định được Time Complexity là O(log n)

- [ ] **P2 | Bubble Sort và Selection Sort (hiểu cơ chế)**
  - Resource: Visualgo — Sorting (https://visualgo.net/en/sorting) — chọn Bubble và Selection
  - ✓ Done khi: Sắp xếp bằng tay (trên giấy) mảng [5, 2, 8, 1, 9] bằng cả hai thuật toán, đếm số lần so sánh — xác nhận đúng là O(n²)

- [ ] **P2 | Merge Sort — tư duy chia để trị**
  - Resource: Visualgo — Sorting → Merge Sort + NeetCode "Merge Sort" (https://www.youtube.com/watch?v=MsYZSinhuFo)
  - ✓ Done khi: Tự code được Merge Sort, giải thích được tại sao nó là O(n log n) thay vì O(n²)

#### Nhóm E — Hash Table (P2)

- [ ] **P2 | Cơ chế Hash Table và tại sao dict Python là O(1) trung bình**
  - Resource: NeetCode video "Hash Tables" (https://www.youtube.com/watch?v=jalSiaIi8j4)
  - ✓ Done khi: Giải thích được khái niệm hash function và collision — và biết tại sao worst case của dict lookup vẫn là O(n)

- [ ] **P2 | Ứng dụng Hash Table để tối ưu bài toán Two Sum**
  - Resource: LeetCode #1 "Two Sum" — tự giải hai cách: brute force O(n²) và hash map O(n)
  - ✓ Done khi: Code được cả hai solution, đo được sự chênh lệch thời gian chạy trên input lớn

#### Nhóm F — Luyện tập tổng hợp (P2-P3)

- [ ] **P2 | Giải 10 bài Easy đầu tiên trên NeetCode**
  - Resource: NeetCode Roadmap phần "Arrays & Hashing" và "Two Pointers" (https://neetcode.io/roadmap)
  - ✓ Done khi: 10 bài đều tự giải không xem solution, tự viết được Big-O analysis cho mỗi bài trong comment

- [ ] **P3 | Giải thêm 15-20 bài Easy/Medium**
  - Resource: NeetCode Roadmap tiếp — "Sliding Window", "Stack", "Binary Search"
  - ✓ Done khi: Tỉ lệ tự giải được (không xem gợi ý) đạt ít nhất 60% — điều này quan trọng hơn số lượng bài

- **Definition of Done toàn mục 1.2:** Giải được 25-30 bài LeetCode/NeetCode (Easy/Medium), với ít nhất 60% là tự giải không xem gợi ý. Với mỗi bài, tự viết được Big-O Time và Space Complexity trong comment.
- [ ] Hoàn thành toàn bộ mục 1.2

---

### 1.3. Trực giác Đại số tuyến tính cho ML
> **Nguồn học chính:** 3Blue1Brown "Essence of Linear Algebra" (https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
> Quy tắc: Sau mỗi video 3Blue1Brown, **tắt video và giải thích lại bằng lời của mình** (vd: giải thích cho một người bạn tưởng tượng chưa biết gì). Nếu giải thích không được, xem lại — không tiếp tục video tiếp theo khi chưa giải thích được video trước.

#### Nhóm A — Vector (P1)

- [ ] **P1 | Vector là gì — vừa là điểm, vừa là mũi tên**
  - Resource: 3Blue1Brown Essence of Linear Algebra — Chapter 1 "Vectors, what even are they?" (https://www.youtube.com/watch?v=fNk_zzaMoSs)
  - ✓ Done khi: Giải thích được tại sao vector [3, 4] trong ML không chỉ là "hai số" mà là một điểm trong không gian 2D hoặc một hướng di chuyển — bằng lời, không cần công thức

- [ ] **P1 | Phép cộng vector và nhân với số vô hướng (scalar)**
  - Resource: 3Blue1Brown Chapter 1 (phần cuối) + Khan Academy "Vector addition" (https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/adding-vectors)
  - ✓ Done khi: Vẽ được trên giấy kết quả của [1,2] + [3,1] và 2×[1,2] — giải thích được ý nghĩa hình học

- [ ] **P1 | Tích vô hướng (dot product) và ý nghĩa hình học**
  - Resource: 3Blue1Brown Chapter 9 "Dot products and duality" (https://www.youtube.com/watch?v=LyGKycYT2v0)
  - ✓ Done khi: Giải thích được tại sao trong ML, dot product dùng để đo "độ giống nhau" giữa hai vector — và tại sao dot product của hai vector vuông góc là 0

- [ ] **P1 | Độ dài vector (norm L2) và khoảng cách Euclid**
  - Resource: Khan Academy "Vector magnitude" (https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/vector-magnitude)
  - ✓ Done khi: Tính được độ dài của vector [3, 4] bằng tay (không dùng máy tính), liên hệ với định lý Pythagoras từ cấp 3

#### Nhóm B — Ma trận và phép biến đổi không gian (P1)

- [ ] **P1 | Ma trận như một phép biến đổi không gian**
  - Resource: 3Blue1Brown Chapter 3 "Linear transformations and matrices" (https://www.youtube.com/watch?v=kYB8IZa5AuE)
  - ✓ Done khi: Giải thích được bằng hình vẽ (trên giấy) ma trận [[2,0],[0,2]] làm gì với mỗi điểm trong không gian — không dùng công thức

- [ ] **P1 | Phép nhân ma trận với vector**
  - Resource: 3Blue1Brown Chapter 3 (phần phép nhân) + Khan Academy "Matrix-vector products" (https://www.khanacademy.org/math/linear-algebra/matrix-transformations/linear-transformations/v/matrix-vector-products-as-linear-transformations)
  - ✓ Done khi: Tính được tay kết quả của ma trận 2×2 nhân vector 2×1 — và giải thích được đây là "áp dụng phép biến đổi lên vector"

- [ ] **P1 | Phép nhân hai ma trận — ghép nối nhiều phép biến đổi**
  - Resource: 3Blue1Brown Chapter 4 "Matrix multiplication as composition" (https://www.youtube.com/watch?v=XkY2DOUCWMU)
  - ✓ Done khi: Giải thích được tại sao AB ≠ BA nói chung — bằng ví dụ hình học (xoay 90° rồi lật khác với lật rồi xoay 90°)

- [ ] **P2 | Ma trận đơn vị (Identity matrix) và ma trận nghịch đảo**
  - Resource: 3Blue1Brown Chapter 7 "Inverse matrices, column space and null space" (https://www.youtube.com/watch?v=uQhTuRlWMxw)
  - ✓ Done khi: Giải thích được bằng lời tại sao ma trận nghịch đảo giống như "đảo ngược phép biến đổi" — và khi nào một ma trận không có nghịch đảo (hint: det = 0)

- [ ] **P2 | Định thức (determinant) — đo mức độ "co giãn" không gian**
  - Resource: 3Blue1Brown Chapter 6 "The determinant" (https://www.youtube.com/watch?v=Ip3X9LOh2dk)
  - ✓ Done khi: Giải thích được tại sao det = 0 có nghĩa là ma trận "xẹp" không gian xuống một chiều thấp hơn — liên hệ với việc không thể nghịch đảo

#### Nhóm C — Không gian và biến đổi nâng cao (P2-P3)

- [ ] **P2 | Cơ sở (Basis) và hệ tọa độ**
  - Resource: 3Blue1Brown Chapter 13 "Change of basis" (https://www.youtube.com/watch?v=P2LTAUO1TdA)
  - ✓ Done khi: Giải thích được tại sao trong ML, thay đổi "basis" tương đương với nhìn dữ liệu từ một góc độ khác — đây chính là ý tưởng của PCA

- [ ] **P2 | Eigenvector và Eigenvalue — trực giác**
  - Resource: 3Blue1Brown Chapter 14 "Eigenvectors and eigenvalues" (https://www.youtube.com/watch?v=PFDu9oVAE-g)
  - ✓ Done khi: Giải thích được bằng lời: eigenvector là hướng nào trong không gian mà khi áp dụng ma trận lên nó chỉ bị kéo dài/thu ngắn (không bị lệch hướng) — không cần tính toán

- [ ] **P3 | Liên hệ eigenvector/eigenvalue với PCA (chuẩn bị cho Giai đoạn 2)**
  - Resource: StatQuest "PCA Step-by-Step" (https://www.youtube.com/watch?v=FgakZw6K1QQ)
  - ✓ Done khi: Giải thích được ở mức tổng quan: PCA tìm các eigenvector của ma trận hiệp phương sai để tìm hướng dữ liệu "phân tán" nhiều nhất — không cần tính toán

- **Definition of Done toàn mục 1.3:** Giải thích được bằng lời (3-5 câu, không dùng công thức) tại sao trong một Neural Network, mỗi layer thực chất là áp dụng một phép biến đổi ma trận lên dữ liệu đầu vào.
- [ ] Hoàn thành toàn bộ mục 1.3

---

### 1.4. Trực giác Giải tích & Xác suất cho ML
> **Nguồn học chính:** 3Blue1Brown "Essence of Calculus" (https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) + StatQuest with Josh Starmer (https://www.youtube.com/@statquest)

#### Nhóm A — Giải tích (P1)

- [ ] **P1 | Đạo hàm là gì — tốc độ thay đổi và độ dốc**
  - Resource: 3Blue1Brown Essence of Calculus Chapter 2 "The paradox of the derivative" (https://www.youtube.com/watch?v=9vKqVkMQHKk)
  - ✓ Done khi: Vẽ được trên giấy đồ thị y=x², chỉ ra tiếp tuyến tại x=2, và tính được độ dốc (đạo hàm) tại điểm đó bằng tay

- [ ] **P1 | Đạo hàm của các hàm cơ bản (đa thức, mũ, log)**
  - Resource: Khan Academy "Basic differentiation rules" (https://www.khanacademy.org/math/differential-calculus/dc-diff-intro/dc-basic-diff-rules/v/power-rule)
  - ✓ Done khi: Tính được đạo hàm của f(x) = 3x³ - 2x² + x - 5 bằng tay, không dùng máy tính

- [ ] **P1 | Chain Rule — quy tắc đạo hàm hàm hợp**
  - Resource: 3Blue1Brown Chapter 4 "Visualizing the chain rule" (https://www.youtube.com/watch?v=YG15m2VwSjA) + Khan Academy "Chain rule" (https://www.khanacademy.org/math/differential-calculus/dc-chain-rule/dc-chain-rule-intro/v/chain-rule-introduction)
  - ✓ Done khi: Tính được đạo hàm của f(x) = sin(x²) và f(x) = e^(3x) bằng tay — và giải thích được tại sao Chain Rule là cơ chế của Backpropagation

- [ ] **P1 | Cực trị — đạo hàm bằng 0**
  - Resource: Khan Academy "Finding critical points" (https://www.khanacademy.org/math/ap-calculus-ab/ab-diff-analytical-applications-new/ab-5-2/v/minima-maxima-and-critical-points)
  - ✓ Done khi: Tìm cực tiểu của f(x) = x² - 4x + 5 bằng tay — liên hệ: tìm cực tiểu của Loss Function chính là bài toán ML đang làm

- [ ] **P1 | Đạo hàm riêng phần (Partial Derivative)**
  - Resource: Khan Academy "Partial derivatives" (https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/partial-derivative-and-gradient-articles/a/introduction-to-partial-derivatives)
  - ✓ Done khi: Tính được ∂f/∂x và ∂f/∂y của f(x,y) = x²y + 3xy² bằng tay

- [ ] **P1 | Gradient — vector chỉ hướng tăng nhanh nhất**
  - Resource: 3Blue1Brown "Gradient" trong series Multivariable Calculus (https://www.youtube.com/watch?v=tIpKfDc295M) + Khan Academy "Gradient" (https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/partial-derivative-and-gradient-articles/a/the-gradient)
  - ✓ Done khi: Tính được gradient của f(x,y) = x² + y² tại điểm (1, 2) — và giải thích được hướng gradient vector chỉ về đâu

- [ ] **P1 | Gradient Descent — trực giác tìm cực tiểu**
  - Resource: 3Blue1Brown "Gradient Descent, how neural networks learn" (https://www.youtube.com/watch?v=IHZwWFHWa-w)
  - ✓ Done khi: Vẽ được trên giấy sơ đồ "người đi xuống dốc" minh họa Gradient Descent — chỉ ra được Learning Rate ảnh hưởng như thế nào đến bước đi

- [ ] **P2 | Learning Rate và vấn đề khi chọn sai**
  - Resource: StatQuest "Gradient Descent, Step-by-Step" (https://www.youtube.com/watch?v=sDv4f4s2SB8)
  - ✓ Done khi: Giải thích được bằng hình vẽ 2 kịch bản xấu: learning rate quá lớn (dao động/diverge) và quá nhỏ (hội tụ chậm)

#### Nhóm B — Xác suất và thống kê (P1-P2)

- [ ] **P1 | Biến ngẫu nhiên rời rạc và liên tục**
  - Resource: StatQuest "Probability is not Likelihood" (https://www.youtube.com/watch?v=pYxNSUDSFH4)
  - ✓ Done khi: Giải thích được sự khác biệt giữa P(X=5) với biến rời rạc và P(4.9 < X < 5.1) với biến liên tục — tại sao P(X=5) = 0 với biến liên tục

- [ ] **P1 | Phân phối Normal (Gaussian) — hình dạng và ý nghĩa**
  - Resource: StatQuest "Normal Distribution, Clearly Explained" (https://www.youtube.com/watch?v=rzFX5NWojp0)
  - ✓ Done khi: Giải thích được tại sao trong ML, nhiều noise và nhiều hiện tượng tự nhiên có phân phối Normal (Central Limit Theorem ở mức trực giác)

- [ ] **P1 | Kỳ vọng (Mean) và Phương sai (Variance)**
  - Resource: StatQuest "Mean, Variance and Standard Deviation, Clearly Explained" (https://www.youtube.com/watch?v=SzZ6GpcfoQY)
  - ✓ Done khi: Tính được tay E[X] và Var[X] cho một phân phối rời rạc đơn giản — và giải thích được Variance đo "độ phân tán" nghĩa là gì

- [ ] **P2 | Xác suất có điều kiện (Conditional Probability)**
  - Resource: StatQuest "Conditional Probability" (https://www.youtube.com/watch?v=_IgyaD7vOOA)
  - ✓ Done khi: Giải thích được P(A|B) ≠ P(B|A) bằng ví dụ thực tế — đây là lỗi tư duy phổ biến, liên quan đến Định lý Bayes ở Giai đoạn 2

- **Definition of Done toàn mục 1.4:** Tự vẽ được trên giấy (không nhìn tài liệu) sơ đồ hoàn chỉnh minh họa: Loss Function hình chữ U, điểm khởi đầu ngẫu nhiên, mũi tên gradient, bước đi Gradient Descent, và điểm đến cực tiểu — chú thích được vai trò của Learning Rate.
- [ ] Hoàn thành toàn bộ mục 1.4

---

### 1.5. Mini-Project tổng hợp Giai đoạn 1 — Xử lý ảnh grayscale bằng NumPy
> **Mục tiêu:** Không có thư viện ML nào — chỉ Python + NumPy. Đây là cách chứng minh em thực sự hiểu mảng 2D, không chỉ biết gọi thư viện.

**Checklist theo thứ tự thực hiện:**

- [ ] **Bước 1 | Cài NumPy và đọc được ảnh dưới dạng mảng số**
  - Resource: NumPy Quickstart (https://numpy.org/doc/stable/user/quickstart.html) + dùng `Pillow` để đọc ảnh: `from PIL import Image; img = Image.open(...).convert('L'); arr = np.array(img)`
  - ✓ Done khi: In ra được `arr.shape`, `arr.dtype`, và giá trị của pixel tại vị trí (100, 200)

- [ ] **Bước 2 | Hiểu cấu trúc mảng 2D: shape, dtype, min/max**
  - Resource: NumPy Quickstart phần "Array Creation" và "Basic Operations"
  - ✓ Done khi: Giải thích được tại sao ảnh grayscale 100×200 pixels có shape (100, 200) — không phải (200, 100)

- [ ] **Bước 3 | Viết hàm làm sáng/tối ảnh**
  - ✓ Done khi: Hàm nhận `arr` và `delta` (số), cộng/trừ delta vào mọi pixel, giới hạn kết quả trong [0, 255] bằng `np.clip` — có type hinting và docstring

- [ ] **Bước 4 | Viết hàm lật ảnh ngang và dọc**
  - ✓ Done khi: Dùng slicing 2D (`arr[::-1, :]` và `arr[:, ::-1]`) — không dùng vòng lặp, giải thích được slicing đó làm gì

- [ ] **Bước 5 | Viết hàm crop ảnh (cắt một vùng)**
  - ✓ Done khi: Hàm nhận `top, bottom, left, right` và trả về mảng con bằng slicing `arr[top:bottom, left:right]`

- [ ] **Bước 6 | Viết hàm làm mờ đơn giản (box blur)**
  - Resource: Đọc về convolution cơ bản: https://setosa.io/ev/image-kernels/ (tương tác trực quan)
  - ✓ Done khi: Viết được hàm trung bình các pixel lân cận 3×3 cho mỗi pixel (dùng vòng lặp thông thường), lưu kết quả ra ảnh mới và kiểm tra bằng mắt thấy ảnh mờ hơn

- [ ] **Bước 7 | So sánh tốc độ: vòng lặp Python vs NumPy vectorization**
  - Resource: NumPy Quickstart phần "Universal Functions"
  - ✓ Done khi: Đo được thời gian chạy hàm làm sáng/tối bằng `time.time()` — phiên bản vòng lặp Python vs phiên bản NumPy — ghi lại kết quả, giải thích tại sao NumPy nhanh hơn

- [ ] **Bước 8 | Viết README và đẩy lên GitHub**
  - ✓ Done khi: Repo có `main.py`, `utils.py` (chứa các hàm), `README.md` mô tả project, `requirements.txt` — và đẩy được lên GitHub bằng `git add`, `commit`, `push`

- **Definition of Done toàn mục 1.5:** Repo GitHub có thể clone về, chạy `pip install -r requirements.txt` rồi `python main.py` và output ra 4 ảnh: original, brightened, flipped, blurred — không có lỗi.
- [ ] Hoàn thành toàn bộ mục 1.5

---

## 📍 GIAI ĐOẠN 2 — NĂM NHẤT UET (song hành các môn cơ sở ngành)
**Mục tiêu:** Mỗi môn nặng ở trường đều có một "cánh cửa" ứng dụng trực tiếp vào ML.

### 2.1. Đại số tuyến tính (môn ĐHQGHN) → ứng dụng ML
- **Vì sao:** SVD, PCA dùng giảm chiều dữ liệu, nền của Recommendation System và Computer Vision cổ điển.

**Checklist chi tiết:**
- [ ] Không gian vector (Vector space) và không gian con (Subspace) — định nghĩa hình thức
- [ ] Tính độc lập tuyến tính (Linear independence)
- [ ] Cơ sở (Basis) và số chiều (Dimension) của không gian vector
- [ ] Phép biến đổi tuyến tính (Linear transformation) — định nghĩa hình thức, không chỉ trực giác
- [ ] Trị riêng, vector riêng (Eigenvalue, Eigenvector) — tính toán cụ thể bằng tay với ma trận nhỏ
- [ ] Chéo hóa ma trận (Diagonalization) — ý nghĩa và điều kiện áp dụng
- [ ] Phân tích giá trị kỳ dị (Singular Value Decomposition - SVD) — khái niệm và công thức
- [ ] Principal Component Analysis (PCA) — liên hệ PCA với eigenvector của ma trận hiệp phương sai
- [ ] Ứng dụng PCA: giảm chiều dữ liệu, trực quan hóa dữ liệu nhiều chiều
- [ ] Norm của ma trận và một số tính chất cơ bản

- **Link miễn phí:**
  - [MIT 18.06 Linear Algebra – Gilbert Strang](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
  - [StatQuest – PCA giải thích trực quan](https://www.youtube.com/watch?v=FgakZw6K1QQ)
- **Ứng dụng thực chiến:** Tự code PCA từ đầu bằng NumPy (không dùng `sklearn.PCA`), áp dụng nén 1 bộ ảnh.
- [ ] Hoàn thành toàn bộ mục 2.1

---

### 2.2. Giải tích (Calculus 2/3) → Backpropagation
- **Vì sao:** Backpropagation chính là Chain Rule áp dụng hàng triệu lần.

**Checklist chi tiết:**
- [ ] Đạo hàm hàm nhiều biến — ôn lại và mở rộng từ 1.4
- [ ] Gradient của hàm nhiều biến — vector đạo hàm riêng phần
- [ ] Ma trận Jacobian — đạo hàm của hàm vector theo vector
- [ ] Chain Rule mở rộng cho hàm hợp nhiều lớp (multivariable chain rule)
- [ ] Cấu trúc một Neural Network đơn giản: input layer, hidden layer, output layer
- [ ] Hàm kích hoạt (Activation function): Sigmoid, ReLU, Tanh — công thức và đạo hàm
- [ ] Forward pass — tính toán đầu ra từ đầu vào qua từng lớp
- [ ] Backward pass — lan truyền gradient ngược từ Loss về từng trọng số (weight)
- [ ] Cập nhật trọng số bằng Gradient Descent sau khi có gradient
- [ ] Khái niệm Vanishing Gradient và Exploding Gradient ở mức trực giác

- **Link miễn phí:**
  - [3Blue1Brown – Backpropagation calculus](https://www.youtube.com/watch?v=tIeHLnjs5U8)
  - [MIT 18.01/18.02 Calculus](https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/)
- **Ứng dụng thực chiến:** Tự code một mạng neural 2-layer "from scratch" chỉ bằng NumPy, tự viết backprop bằng tay.
- [ ] Hoàn thành toàn bộ mục 2.2

---

### 2.3. Xác suất thống kê → Model Evaluation & Bayesian thinking
- **Vì sao:** Hiểu vì sao model overfit, cách đọc Confusion Matrix, p-value, vì sao Naive Bayes hoạt động.

**Checklist chi tiết:**
- [ ] Định lý Bayes — công thức và ý nghĩa trực giác (cập nhật niềm tin khi có bằng chứng mới)
- [ ] Phân phối xác suất rời rạc: Bernoulli, Binomial
- [ ] Phân phối xác suất liên tục: Normal, Uniform (ôn sâu hơn 1.4)
- [ ] Khái niệm Maximum Likelihood Estimation (MLE) ở mức trực giác
- [ ] Confusion Matrix: True Positive, False Positive, True Negative, False Negative
- [ ] Accuracy, Precision, Recall — công thức và khi nào dùng metric nào
- [ ] F1-score — vì sao cần kết hợp Precision và Recall
- [ ] Đường cong ROC và chỉ số AUC ở mức khái niệm
- [ ] Khái niệm Overfitting và Underfitting — liên hệ với Bias-Variance Tradeoff
- [ ] Train/Validation/Test split — vì sao cần chia 3 phần, không chỉ 2
- [ ] Cross-validation — khái niệm K-fold
- [ ] p-value và kiểm định giả thuyết (Hypothesis testing) ở mức cơ bản
- [ ] Naive Bayes Classifier — liên hệ trực tiếp với Định lý Bayes

- **Link miễn phí:**
  - [Harvard Stat 110](https://projects.iq.harvard.edu/stat110/home)
  - [StatQuest – Statistics Fundamentals playlist](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9)
- [ ] Hoàn thành toàn bộ mục 2.3

---

### 2.4. Cấu trúc dữ liệu & Giải thuật (CTDL&GT) → Tối ưu hiệu năng ML
- **Vì sao:** Hash Table/Tree/Graph quyết định code chạy 1 giây hay treo máy. Quyết định pass phỏng vấn MLE hay không.

**Checklist chi tiết:**
- [ ] Linked List: singly và doubly, các thao tác cơ bản
- [ ] Stack: LIFO, ứng dụng (vd: kiểm tra dấu ngoặc hợp lệ)
- [ ] Queue: FIFO, ứng dụng (vd: xử lý theo hàng đợi)
- [ ] Binary Tree: định nghĩa, duyệt cây (preorder, inorder, postorder)
- [ ] Binary Search Tree (BST): tính chất, tìm kiếm/chèn/xóa
- [ ] Cây cân bằng (Balanced Tree) ở mức khái niệm (AVL hoặc Red-Black, không cần cài đặt chi tiết)
- [ ] Heap: Min-heap, Max-heap, ứng dụng Priority Queue
- [ ] Hash Table: cơ chế hash function, xử lý va chạm (collision)
- [ ] Graph: biểu diễn bằng Adjacency List và Adjacency Matrix
- [ ] Duyệt đồ thị: BFS (Breadth-First Search) và DFS (Depth-First Search)
- [ ] Thuật toán tìm đường đi ngắn nhất cơ bản (Dijkstra ở mức khái niệm)
- [ ] Dynamic Programming: khái niệm overlapping subproblems, memoization
- [ ] Phân tích độ phức tạp của các cấu trúc dữ liệu trên (so sánh thao tác)

- **Link miễn phí:**
  - [MIT 6.006 Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)
  - [NeetCode 150](https://neetcode.io/roadmap)
- [ ] Hoàn thành toàn bộ mục 2.4

---

### 2.5. Nhập môn Machine Learning cổ điển
- **Vì sao:** Học sớm giúp các môn cơ sở ngành có "đất dụng võ" ngay lập tức.

**Checklist chi tiết:**
- [ ] Phân biệt Supervised, Unsupervised, Reinforcement Learning
- [ ] Linear Regression: công thức, hàm mất mát (MSE), cách giải
- [ ] Logistic Regression: từ Linear Regression đến bài toán phân loại
- [ ] Hàm Sigmoid và Decision Boundary trong Logistic Regression
- [ ] Gradient Descent áp dụng cho Linear/Logistic Regression cụ thể
- [ ] K-Nearest Neighbors (KNN): cơ chế hoạt động, ưu nhược điểm
- [ ] Decision Tree: cách chọn điểm chia (Gini, Entropy)
- [ ] Random Forest: ý tưởng ensemble từ nhiều Decision Tree
- [ ] K-Means Clustering: thuật toán, cách chọn số cụm K
- [ ] Regularization: L1 (Lasso) và L2 (Ridge) — vì sao cần và khác nhau thế nào
- [ ] Feature Scaling: Normalization và Standardization — vì sao cần thiết
- [ ] Quy trình chuẩn của một bài toán ML: EDA → Preprocessing → Train → Evaluate

- **Link miễn phí:**
  - [Andrew Ng – Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction)
  - [Stanford CS229](https://cs229.stanford.edu/)
  - [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- **Ứng dụng thực chiến:** [Kaggle Titanic Survival Prediction](https://www.kaggle.com/c/titanic)
- [ ] Hoàn thành toàn bộ mục 2.5

---

## 📍 GIAI ĐOẠN 3 — NĂM 2 UET: DEEP LEARNING FOUNDATIONS + DATA ENGINEERING NỀN TẢNG
**Mục tiêu:** Có nền Deep Learning đầy đủ (không chỉ "biết train CNN" mà hiểu sâu cơ chế), đồng thời có khả năng xử lý dữ liệu thật quy mô lớn — vì DL không có data pipeline tốt thì chỉ chạy được trên dataset mẫu.

### 3.1. PyTorch nền tảng — Tensor, Autograd, Training Loop
- **Vì sao:** Đây là "ngôn ngữ" để diễn đạt mọi kiến trúc Deep Learning sau này. Không vững phần này, mọi thứ phía sau đều là học vẹt.

**Checklist chi tiết:**
- [ ] Tensor: tạo, kiểu dữ liệu (`dtype`), shape, device (CPU/GPU)
- [ ] Các thao tác Tensor cơ bản: indexing, slicing, reshape, view, squeeze/unsqueeze
- [ ] Broadcasting trong PyTorch — quy tắc giống NumPy
- [ ] Phép toán Tensor: cộng/trừ/nhân/chia element-wise, matrix multiplication (`@`, `matmul`)
- [ ] `requires_grad=True` và ý nghĩa của Autograd
- [ ] Computational Graph — cách PyTorch xây dựng đồ thị tính toán động
- [ ] `.backward()` và cách gradient được tích lũy vào `.grad`
- [ ] `torch.no_grad()` — khi nào cần tắt tính gradient (vd: lúc inference)
- [ ] `nn.Module` — xây dựng layer và model bằng class
- [ ] `nn.Linear`, `nn.ReLU`, `nn.Sequential` — các building block cơ bản
- [ ] Hàm mất mát: `nn.MSELoss`, `nn.CrossEntropyLoss`, `nn.BCELoss` — khi nào dùng loss nào
- [ ] Optimizer: `torch.optim.SGD`, `torch.optim.Adam` — sự khác biệt về cơ chế cập nhật
- [ ] Training loop chuẩn: `zero_grad()` → `forward()` → `loss.backward()` → `optimizer.step()`
- [ ] `Dataset` và `DataLoader` — cách nạp dữ liệu theo batch, shuffle
- [ ] Custom Dataset — viết class kế thừa `torch.utils.data.Dataset`
- [ ] Train/Eval mode: `.train()` và `.eval()` khác nhau thế nào (ảnh hưởng Dropout, BatchNorm)
- [ ] Lưu và load model: `state_dict()`, `torch.save`, `torch.load`
- [ ] Chuyển model/tensor lên GPU: `.to(device)`, kiểm tra `torch.cuda.is_available()`

- **Link miễn phí:**
  - [PyTorch Official Tutorials – Learn the Basics](https://pytorch.org/tutorials/beginner/basics/intro.html)
  - [PyTorch Official – 60 Minute Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)
- **Definition of Done:** Tự viết được training loop hoàn chỉnh cho một bài toán phân loại đơn giản, không copy code mẫu.
- [ ] Hoàn thành toàn bộ mục 3.1

---

### 3.2. Computer Vision — Convolutional Neural Network (CNN)
- **Vì sao:** CNN là kiến trúc nền tảng cho mọi bài toán liên quan đến ảnh — nắm vững CNN mở khóa cả nhánh Computer Vision.

**Checklist chi tiết:**
- [ ] Vì sao Fully Connected Network không hiệu quả với ảnh (số tham số quá lớn)
- [ ] Phép tích chập (Convolution) — cơ chế trượt kernel qua ảnh
- [ ] Kernel/Filter — vai trò trong việc trích xuất đặc trưng (edge, texture...)
- [ ] Stride và Padding — ảnh hưởng đến kích thước output
- [ ] Feature Map — cách hiểu output của một lớp Convolution
- [ ] Pooling layer: Max Pooling, Average Pooling — vai trò giảm chiều và tăng tính bất biến
- [ ] Receptive Field — vùng ảnh gốc mà một neuron ở lớp sâu "nhìn thấy"
- [ ] Kiến trúc CNN cổ điển: LeNet, sau đó AlexNet (ở mức đọc hiểu kiến trúc)
- [ ] Batch Normalization — vì sao giúp training ổn định và nhanh hơn
- [ ] Dropout — cơ chế chống overfitting
- [ ] Data Augmentation cho ảnh: flip, rotate, crop, color jitter
- [ ] Kiến trúc hiện đại hơn: ResNet và khái niệm Skip Connection/Residual
- [ ] Transfer Learning: dùng pretrained model (ResNet, EfficientNet...) làm backbone
- [ ] Fine-tuning: đóng băng (freeze) một số layer, chỉ train layer cuối
- [ ] Bài toán phân loại ảnh end-to-end: từ raw image đến prediction

- **Link miễn phí:**
  - [Stanford CS231n – Convolutional Neural Networks](https://cs231n.stanford.edu/) (notes: [cs231n.github.io](https://cs231n.github.io/))
  - [fast.ai – Practical Deep Learning for Coders](https://course.fast.ai/)
- **Ứng dụng thực chiến:** Train CNN từ đầu trên CIFAR-10, sau đó so sánh với fine-tune ResNet pretrained — đo chênh lệch accuracy và thời gian train.
- [ ] Hoàn thành toàn bộ mục 3.2

---

### 3.3. Xử lý dữ liệu tuần tự — RNN, LSTM cơ bản
- **Vì sao:** Đây là nền tảng lịch sử dẫn tới Transformer — hiểu RNN giúp hiểu rõ tại sao Transformer ra đời để giải quyết vấn đề gì.

**Checklist chi tiết:**
- [ ] Vì sao CNN/Fully Connected không phù hợp với dữ liệu tuần tự (text, time series)
- [ ] Cấu trúc RNN cơ bản — trạng thái ẩn (hidden state) truyền qua từng bước thời gian
- [ ] Vấn đề Vanishing Gradient trong RNN khi chuỗi dài
- [ ] LSTM (Long Short-Term Memory) — cơ chế cổng (gate): forget gate, input gate, output gate
- [ ] GRU (Gated Recurrent Unit) ở mức khái niệm — phiên bản đơn giản hơn LSTM
- [ ] Bài toán Sequence Classification (vd: phân loại cảm xúc văn bản) bằng RNN/LSTM
- [ ] Embedding layer — biểu diễn từ/token thành vector số

- **Link miễn phí:**
  - [Stanford CS231n RNN module](https://cs231n.github.io/)
  - [Colah's Blog – Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- [ ] Hoàn thành toàn bộ mục 3.3

---

### 3.4. Xử lý dữ liệu lớn — Pandas nâng cao và Spark
- **Vì sao:** Dữ liệu thật không bao giờ sạch sẵn và thường vượt quá khả năng xử lý của một máy đơn lẻ.

**Checklist chi tiết:**
- [ ] DataFrame và Series — cấu trúc cơ bản, ôn lại và đào sâu
- [ ] Đọc/ghi nhiều định dạng: CSV, JSON, Parquet
- [ ] Lọc và chọn dữ liệu nâng cao: `.loc`, `.iloc`, `query()`, boolean filtering phức tạp
- [ ] Xử lý dữ liệu thiếu: chiến lược `dropna` vs `fillna` (mean/median/mode imputation)
- [ ] `groupby` nâng cao: multiple aggregation, `transform`, `apply`
- [ ] Merge/Join nâng cao: inner, outer, left, right join, xử lý trùng khóa
- [ ] Pivot table và Melt — reshape dữ liệu giữa wide và long format
- [ ] Xử lý dữ liệu thời gian: resample, rolling window
- [ ] Tối ưu hiệu năng Pandas: dtype phù hợp, tránh vòng lặp, dùng vectorization
- [ ] Giới hạn của Pandas khi dữ liệu vượt RAM — dấu hiệu nhận biết
- [ ] Khái niệm Spark: kiến trúc Driver-Executor, xử lý phân tán
- [ ] RDD (Resilient Distributed Dataset) — khái niệm cơ bản
- [ ] Spark DataFrame API — tương đồng và khác biệt với Pandas
- [ ] Transformation và Action trong Spark — lazy evaluation
- [ ] PySpark thực hành: đọc dữ liệu lớn, filter, groupBy, join cơ bản

- **Link miễn phí:**
  - [Kaggle Learn – Pandas](https://www.kaggle.com/learn/pandas)
  - [Spark by Examples – PySpark Tutorial](https://sparkbyexamples.com/pyspark-tutorial/)
  - [Databricks Academy](https://www.databricks.com/learn/training/home)
- **Ứng dụng thực chiến:** Xử lý một bộ dữ liệu thật (vài triệu dòng) bằng cả Pandas và PySpark, so sánh thời gian chạy.
- [ ] Hoàn thành toàn bộ mục 3.4

---

### 3.5. Mini-Project tổng hợp Năm 2
**Checklist chi tiết:**
- [ ] Chọn một bài toán Computer Vision thực tế (vd: phân loại rác thải, nhận diện biển số...)
- [ ] Thu thập hoặc dùng dataset có sẵn (Kaggle, Hugging Face Datasets)
- [ ] Thực hiện Data Augmentation phù hợp với bài toán
- [ ] Train từ đầu một CNN nhỏ, ghi lại kết quả (accuracy, loss curve)
- [ ] Fine-tune một pretrained model trên cùng bài toán, so sánh kết quả
- [ ] Viết báo cáo ngắn so sánh hai cách tiếp cận, giải thích vì sao có chênh lệch
- [ ] Đẩy code + báo cáo lên GitHub, viết README rõ ràng

- [ ] Hoàn thành toàn bộ mục 3.5

---

## 📍 GIAI ĐOẠN 4 — NĂM 3 UET: CHUYÊN SÂU 1 HƯỚNG + MLOPS NỀN TẢNG
**Mục tiêu:** Chọn một chuyên môn sâu (Computer Vision hoặc NLP) giống cách một MLE thật phải chuyên môn hóa, đồng thời học MLOps cơ bản — vì giờ đã có model đủ tốt để đáng deploy.

> **Lưu ý:** Mục 4.1 và 4.2 là hai lựa chọn thay thế nhau — chọn 1 trong 2 theo hướng quan tâm, không cần học cả hai cùng mức độ sâu (có thể học hướng còn lại ở mức tổng quan sau này).

### 4.1. [Lựa chọn A] Chuyên sâu Computer Vision
- **Vì sao:** CV là lĩnh vực có nhiều ứng dụng thực tế tại Việt Nam (an ninh, y tế, nông nghiệp, xe tự hành) và có nhu cầu tuyển dụng ổn định.

**Checklist chi tiết:**
- [ ] Object Detection — khái niệm, phân biệt với Classification
- [ ] Kiến trúc YOLO ở mức hiểu pipeline (single-shot detection)
- [ ] Kiến trúc Faster R-CNN ở mức khái niệm (two-stage detection)
- [ ] Image Segmentation — phân biệt Semantic Segmentation và Instance Segmentation
- [ ] Kiến trúc U-Net ở mức hiểu pipeline (encoder-decoder, skip connection)
- [ ] Vision Transformer (ViT) ở mức khái niệm — áp dụng Transformer cho ảnh
- [ ] Metric đánh giá CV: IoU (Intersection over Union), mAP (mean Average Precision)
- [ ] Xử lý ảnh nâng cao: Non-Maximum Suppression trong Object Detection
- [ ] Khái niệm Generative model cơ bản: Autoencoder, GAN ở mức tổng quan
- [ ] Thực hành với một framework CV chuyên dụng (Ultralytics YOLO hoặc Detectron2)

- **Link miễn phí:**
  - [Stanford CS231n](https://cs231n.stanford.edu/) (phần Detection/Segmentation)
  - [Ultralytics YOLO Documentation](https://docs.ultralytics.com/)
- [ ] Hoàn thành toàn bộ mục 4.1

---

### 4.2. [Lựa chọn B] Chuyên sâu Natural Language Processing (NLP)
- **Vì sao:** NLP là nền tảng của LLM — lĩnh vực đang dẫn dắt ngành AI hiện tại, nhu cầu tuyển dụng tăng nhanh nhất.

**Checklist chi tiết:**
- [ ] Tiền xử lý văn bản: tokenization, stopwords, stemming/lemmatization
- [ ] Biểu diễn văn bản cổ điển: Bag of Words, TF-IDF
- [ ] Word Embedding: Word2Vec, GloVe — trực giác "từ gần nghĩa nằm gần nhau trong không gian vector"
- [ ] Kiến trúc Transformer chi tiết: Self-Attention, Multi-Head Attention
- [ ] Positional Encoding — vì sao Transformer cần nó (không có cấu trúc tuần tự như RNN)
- [ ] Kiến trúc Encoder-Decoder trong Transformer gốc
- [ ] BERT — kiến trúc Encoder-only, khái niệm Masked Language Model
- [ ] GPT — kiến trúc Decoder-only, khái niệm Autoregressive generation
- [ ] Fine-tuning một pretrained language model cho bài toán cụ thể (classification, NER)
- [ ] Hugging Face Transformers: load model, tokenizer, pipeline cơ bản
- [ ] Khái niệm cơ bản về Retrieval-Augmented Generation (RAG)
- [ ] Metric đánh giá NLP cơ bản: BLEU, ROUGE ở mức khái niệm

- **Link miễn phí:**
  - [Jay Alammar – The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
  - [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course)
  - [Stanford CS224n (bài giảng công khai trên YouTube)](https://web.stanford.edu/class/cs224n/)
- [ ] Hoàn thành toàn bộ mục 4.2

---

### 4.3. MLOps nền tảng — Từ code đến API chạy được
- **Vì sao:** Đây là kỹ năng phân biệt rõ nhất "Data Scientist" và "ML Engineer" — biết deploy, không chỉ biết train.

**Checklist chi tiết:**
- [ ] Git nâng cao: branching strategy, resolve merge conflict, pull request workflow
- [ ] Viết `requirements.txt` hoặc dùng `poetry`/`pip-tools` để quản lý dependency chính xác
- [ ] Đóng gói model thành REST API bằng FastAPI: định nghĩa endpoint, request/response schema
- [ ] Validate input bằng Pydantic trong FastAPI
- [ ] Viết test cơ bản cho API (pytest)
- [ ] Khái niệm Docker: Image, Container, Layer — phân biệt rõ ràng
- [ ] Viết Dockerfile cho một ứng dụng Python/FastAPI hoàn chỉnh
- [ ] Docker Compose — chạy nhiều service cùng lúc (vd: API + database)
- [ ] Khái niệm CI/CD: tự động test khi push code (GitHub Actions cơ bản)
- [ ] Viết một GitHub Actions workflow đơn giản (chạy test tự động)
- [ ] Model serialization: so sánh pickle, joblib, ONNX ở mức khái niệm
- [ ] Logging cơ bản trong ứng dụng Python (module `logging`)
- [ ] Deploy thử API lên một nền tảng free tier (Render, Railway, Hugging Face Spaces)
- [ ] Khái niệm Environment Variables và quản lý secret cơ bản (không hardcode API key)

- **Link miễn phí:**
  - [Made With ML](https://madewithml.com/)
  - [DataTalksClub – MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp)
  - [Docker Official Get Started Guide](https://docs.docker.com/get-started/)
  - [FastAPI Official Tutorial](https://fastapi.tiangolo.com/tutorial/)
- **Ứng dụng thực chiến:** Đóng gói model từ mục 4.1/4.2 thành API, containerize, deploy public — có thể demo qua URL thật.
- [ ] Hoàn thành toàn bộ mục 4.3

---

### 4.4. Mini-Project tổng hợp Năm 3
**Checklist chi tiết:**
- [ ] Chọn bài toán thuộc đúng hướng chuyên sâu đã chọn (CV hoặc NLP)
- [ ] Train model đạt độ chính xác hợp lý, có ghi log thí nghiệm (thử nhiều cấu hình)
- [ ] Đóng gói thành API hoàn chỉnh với FastAPI
- [ ] Containerize bằng Docker, viết Docker Compose nếu có thêm service phụ
- [ ] Thiết lập CI cơ bản: tự động chạy test mỗi khi push code lên GitHub
- [ ] Deploy bản demo công khai, có thể truy cập qua URL
- [ ] Viết README đầy đủ: bài toán, kiến trúc, cách chạy local, link demo

- [ ] Hoàn thành toàn bộ mục 4.4

---

## 📍 GIAI ĐOẠN 5 — NĂM 4 UET: MLOPS NÂNG CAO, SYSTEM DESIGN & CHUẨN BỊ ĐI LÀM
**Mục tiêu:** Chuyển từ "người học" sang "người sẵn sàng làm việc" — biết thiết kế hệ thống ML quy mô lớn, hoàn thiện Capstone, và chuẩn bị phỏng vấn thực tế.

### 5.1. MLOps nâng cao — Monitoring, Versioning, Orchestration
- **Vì sao:** Deploy một model là chưa đủ — duy trì nó hoạt động đúng theo thời gian mới là phần khó và ít người làm tốt.

**Checklist chi tiết:**
- [ ] Model Monitoring — phân biệt Data Drift và Concept Drift
- [ ] Công cụ theo dõi thí nghiệm: MLflow hoặc Weights & Biases — tracking metric, params
- [ ] Model Registry — quản lý phiên bản model một cách có hệ thống
- [ ] Feature Store — khái niệm và vì sao cần thiết khi nhiều model dùng chung feature
- [ ] Workflow Orchestration: Airflow hoặc Prefect ở mức khái niệm — tự động hóa pipeline
- [ ] A/B Testing cho model — cách so sánh hai model trong production
- [ ] Canary Deployment và Blue-Green Deployment — chiến lược deploy an toàn
- [ ] Khái niệm Shadow Deployment — chạy model mới song song mà không ảnh hưởng người dùng thật
- [ ] Cơ bản về Kubernetes: Pod, Deployment, Service — khái niệm orchestrate container ở quy mô lớn
- [ ] Batch Inference vs Real-time Inference — khi nào dùng kiến trúc nào

- **Link miễn phí:**
  - [DataTalksClub – MLOps Zoomcamp (phần nâng cao)](https://github.com/DataTalksClub/mlops-zoomcamp)
  - [MLflow Official Documentation](https://mlflow.org/docs/latest/index.html)
  - [Kubernetes Official – Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- [ ] Hoàn thành toàn bộ mục 5.1

---

### 5.2. System Design cho Machine Learning
- **Vì sao:** Đây là phần thường bị bỏ qua nhưng là nội dung trọng tâm trong phỏng vấn MLE tại các công ty lớn.

**Checklist chi tiết:**
- [ ] Quy trình thiết kế hệ thống ML: từ yêu cầu nghiệp vụ đến kiến trúc kỹ thuật
- [ ] Cách đặt câu hỏi làm rõ yêu cầu (clarifying questions) trước khi thiết kế
- [ ] Lựa chọn metric phù hợp với bài toán kinh doanh, không chỉ metric kỹ thuật
- [ ] Thiết kế pipeline Data Collection → Feature Engineering → Training → Serving
- [ ] Cân nhắc Trade-off: độ chính xác vs độ trễ (latency) vs chi phí (cost)
- [ ] Thiết kế hệ thống Recommendation cơ bản (vd: gợi ý sản phẩm)
- [ ] Thiết kế hệ thống phát hiện gian lận (Fraud Detection) cơ bản
- [ ] Thiết kế hệ thống tìm kiếm/xếp hạng (Search/Ranking) cơ bản
- [ ] Khái niệm Scalability — thiết kế hệ thống chịu được lượng truy cập lớn
- [ ] Cách trình bày một thiết kế hệ thống rõ ràng (vẽ sơ đồ, giải thích từng thành phần)

- **Link miễn phí:**
  - [Chip Huyen – Designing Machine Learning Systems (bài viết blog liên quan miễn phí)](https://huyenchip.com/ml-interviews-book/)
  - [Made With ML – System Design section](https://madewithml.com/)
- [ ] Hoàn thành toàn bộ mục 5.2

---

### 5.3. Capstone Project — Sản phẩm tốt nghiệp
- **Vì sao:** Một project end-to-end chất lượng cao là thứ chứng minh năng lực rõ ràng nhất khi xin việc, quan trọng hơn bảng điểm.

**Checklist chi tiết:**
- [ ] Xác định bài toán thật, có giá trị thực tế (không phải bài toán "đồ chơi")
- [ ] Thu thập dữ liệu thật (crawl, API công khai, hoặc hợp tác lấy dữ liệu)
- [ ] Thực hiện EDA đầy đủ, trình bày insight rõ ràng
- [ ] Thử nghiệm nhiều phương pháp, ghi log so sánh có hệ thống (dùng MLflow/W&B)
- [ ] Chọn model cuối cùng dựa trên trade-off rõ ràng (không chỉ chọn model có accuracy cao nhất)
- [ ] Đóng gói thành hệ thống hoàn chỉnh: API + Database (nếu cần) + Frontend đơn giản (nếu cần)
- [ ] Containerize toàn bộ hệ thống bằng Docker Compose
- [ ] Thiết lập CI/CD đầy đủ
- [ ] Thiết lập Monitoring cơ bản cho model đã deploy
- [ ] Deploy bản demo công khai, ổn định, có thể truy cập lâu dài
- [ ] Viết tài liệu kỹ thuật đầy đủ: kiến trúc hệ thống, quyết định thiết kế, hạn chế đã biết
- [ ] Chuẩn bị một bản trình bày (slide) ngắn gọn về project để phỏng vấn

- **Link tham khảo thêm:** [Made With ML – Full MLOps course đi từ project thật](https://madewithml.com/#course)
- [ ] Hoàn thành toàn bộ mục 5.3

---

### 5.4. Chuẩn bị phỏng vấn ML Engineer
- **Vì sao:** Kiến thức tốt không tự động chuyển thành lời mời làm việc — cần luyện kỹ năng trình bày và giải bài tập theo đúng format phỏng vấn thực tế.

**Checklist chi tiết:**
- [ ] Ôn lại toàn bộ thuật toán/CTDL cơ bản (quay lại mục 1.2 và 2.4), luyện thêm bài Medium/Hard
- [ ] Luyện trả lời câu hỏi lý thuyết ML cơ bản (giải thích Bias-Variance, Regularization, Overfitting...)
- [ ] Luyện trả lời câu hỏi về Deep Learning (giải thích Backpropagation, Batch Norm, Attention...)
- [ ] Luyện System Design Interview cho ML (dùng lại checklist mục 5.2)
- [ ] Chuẩn bị kể chuyện (storytelling) về Capstone project — vì sao chọn bài toán đó, khó khăn gặp phải, cách giải quyết
- [ ] Chuẩn bị CV/Resume tập trung vào project thật, không liệt kê khóa học suông
- [ ] Tối ưu GitHub profile: pin đúng project tốt nhất, README rõ ràng cho từng repo
- [ ] Luyện phỏng vấn hành vi (behavioral interview) cơ bản

- **Link miễn phí:**
  - [Chip Huyen – Machine Learning Interviews Book (miễn phí trên GitHub)](https://huyenchip.com/ml-interviews-book/)
  - [NeetCode 150 (ôn lại để phỏng vấn)](https://neetcode.io/roadmap)
- [ ] Hoàn thành toàn bộ mục 5.4

---

## 🗺️ Cách dùng file này hiệu quả
1. Mỗi tuần/tháng, chọn 1-2 dòng checklist trong 1 mục, không ôm đồm cả mục cùng lúc.
2. Khi vào UET, đối chiếu checklist Giai đoạn 2 với đúng nội dung môn học trên lớp.
3. Từ Năm 2 trở đi, mỗi dòng checklist hoàn thành nên đi kèm một đoạn code thực hành nhỏ, không chỉ đọc lý thuyết.
4. Mỗi dòng checklist hoàn thành, quay lại hỏi Claude theo format: Kiến thức cốt lõi → Ví dụ thực chiến → Cạm bẫy → Challenge.
5. Tick `[x]` vào dòng checklist nhỏ trước, dòng "Hoàn thành toàn bộ mục X.X" chỉ tick khi mọi checklist con trong mục đó đã xong.
6. Ở mục 4.1/4.2 (chọn CV hoặc NLP), không cần áy náy nếu không học hướng còn lại sâu — đó là lựa chọn chuyên môn hóa hợp lý, giống senior MLE thật.

---
*File này là bản đồ sống — quay lại bất cứ lúc nào để Claude cập nhật, mở rộng, hoặc đi sâu vào từng node.*
