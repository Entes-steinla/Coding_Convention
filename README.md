# CODING CONVENTION

## Phạm vi hoặc ý nghĩa

| Tiền tố | Ý nghĩa                                               | Ví dụ                       |
| :------ | ----------------------------------------------------- | --------------------------- |
| `s_`    | **Static:** Biến tĩnh, dùng chung giữa các phiên bản. | `static int s_count;`       |
| `m_`    | **Member:** Biến thành viên của lớp.                  | `int m_id;`                 |
| `g_`    | **Global:** Biến toàn cục.                            | `int g_total;`              |
| `t_`    | **Thread-local:** Biến cục bộ theo luồng.             | `thread_local int t_index;` |
| `k`     | **Constant:** Biến hằng số.                           | `const int kMaxSize = 100;` |
| `_`     | **Private:** Dùng cho các thành viên private.         | `int _value;`               |
| `n`     | **Số nguyên _(number)_.**                             | `nCount, nTotal;`           |

## Kiểu dữ liệu

| Tiền tố | Ý nghĩa                                        | Ví dụ                     |
| :------ | ---------------------------------------------- | ------------------------- |
| `i`     | **Integer:** Biến kiểu số nguyên.              | `int iCount;`             |
| `f`     | **Float:** Biến kiểu số thực.                  | `float fValue;`           |
| `d`     | **Double:** Biến kiểu số thực.                 | `double dResult;`         |
| `c`     | **Char:** Biến kiểu ký tự.                     | `char cGrade;`            |
| `b`     | **Boolean:** Biến kiểu logic.                  | `bool bIsActive;`         |
| `p`     | **Pointer:** Con trỏ.                          | `int* pArray;`            |
| `str`   | **String:** Chuỗi ký tự.                       | `std::string strName;`    |
| `v`     | **Vector:** Biến kiểu danh sách/vector.        | `std::vector<int> vNums;` |
| `p_`    | **Pointer:** Biến kiểu con trỏ.                | `int* p_array;`           |
| `r_`    | **Reference _(Tham chiếu)_:** Biến tham chiếu. | `int& r_value;`           |
| `arr_`  | **Array _(Mảng)_:** Biến kiểu mảng.            | `int arr_numbers[10];`    |

## Chức năng hoặc ngữ cảnh

| Tiền tố   | Ý nghĩa                                                 | Ví dụ                           |
| :-------- | ------------------------------------------------------- | ------------------------------- |
| `tmp_`    | **Temporary _(Tạm thời)_:** Biến tạm thời trong xử lý.  | `tmp_result, tmp_value;`        |
| `prev_`   | **Previous _(Trước đó)_:** Lưu giá trị trước đó.        | `prev_count, prev_value;`       |
| `cur_`    | **Current _(Hiện tại)_:** Giá trị hiện tại.             | `cur_index, cur_value;`         |
| `next_`   | **Next _(Tiếp theo)_:** Giá trị tiếp theo.              | `next_element, next_index;`     |
| `is_`     | **Boolean check:** Biến kiểm tra điều kiện.             | `bool is_ready;`                |
| `x, y, z` | **Coordinate _(Toạ độ)_:** Liên quan đến vị trí/toạ độ. | `xPosition, yPosition, zCoord;` |
| `count_`  | **Số lượng.**                                           | `count_students, count_items;`  |
| `index_`  | **Chỉ số.**                                             | `index_element, index_page;`    |

## OOP

| Tiền tố  | Ý nghĩa                                           | Ví dụ              |
| :------- | ------------------------------------------------- | ------------------ |
| `I`      | **Interface _(Giao diện)_:** Phân biệt interface. | `IShape, ILogger;` |
| `m_`     | **Member:** Biến thành viên của lớp.              | `int m_id;`        |
| `_`      | **Private:** Biến private trong lớp.              | `int _value;`      |
| `this->` | Tham chiếu trực tiếp đến thành viên của lớp.      | `this->m_name;`    |

## Cấp phát bộ nhớ

| Tiền tố  | Ý nghĩa                                                   | Ví dụ                               |
| :------- | --------------------------------------------------------- | ----------------------------------- |
| `h_`     | **Handle:** Đại diện tài nguyên hệ thống.                 | `HANDLE hFile;`                     |
| `ptr_`   | **Pointer _(Con trỏ động)_:** Con trỏ qlý bộ nhớ cấp phát | `int* ptr_data;`                    |
| `smart_` | **Smart Pointer:** Biến kiểu con trỏ thông minh.          | `std::shared_ptr<int> smart_value;` |

## Cấu trúc dữ liệu

| Tiền tố  | Ý nghĩa                                          | Ví dụ                                 |
| :------- | ------------------------------------------------ | ------------------------------------- |
| `arr_`   | **Array:** Mảng.                                 | `int arr_numbers[10];`                |
| `map_`   | **Map _(Ánh xạ)_:** Biến kiểu ánh xạ/map.        | `std::map<int, std::string> mapData;` |
| `set_`   | **Set _(Tập hợp)_:** Biến kiểu tập hợp.          | `std::set<int> setValues;`            |
| `vec_`   | **Vector _(Danh sách động)_:** Biến kiểu vector. | `std::vector<int> vecNumbers;`        |
| `queue_` | **Queue _(Hàng đợi)_:** Biến kiểu hàng đợi.      | `std::queue<std::string> queueTasks;` |
| `stack_` | **Stack _(Ngăn xếp)_:** Biến kiểu ngăn xếp.      | `std::stack<int> stackHistory;`       |
