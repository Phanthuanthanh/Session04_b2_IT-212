## BÀI 2: Tối ưu Prompt (Thực hành viết Prompt giải nghĩa Stack Trace và gỡ lỗi)

### 1. Nội dung Prompt sau khi tối ưu (Áp dụng 5 thành phần cốt lõi)
"**[Role]** Hãy đóng vai trò là một Chuyên gia gỡ lỗi Java (Java Debugging Expert) giàu kinh nghiệm.
**[Goal]** Nhiệm vụ của bạn là phân tích và khắc phục lỗi `NullPointerException` đang làm sập chương trình của tôi.
**[Context]** Dưới đây là mã nguồn lớp `UserManager` và dấu vết lỗi (Stack Trace) hiển thị trên console:
- Mã nguồn:
```java
import java.util.List;
public class UserManager {
    private List<String> users;
    public void addUser(String user) {
        users.add(user);
    }
}