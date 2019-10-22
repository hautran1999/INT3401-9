1. ý tưởng Trả về khoảng cách mahattan vị trí pacman sau khi thực hiện 
hành động tới điểm thức ăn gần nhất mà pacman trước khi thực hiện 
hành động.
   bài toán trả về số lớn tốt hơn => nhân với -1.

2. ý tưởng dựa vào thuật toán minimax đã học
   vì có nhiều hơn 1 con ma nên để xác định Agent đang hoạt động cần dựa vào 
AgentIndex

3. ý tưởng giống vs câu 2 nhưng khác là sd thêm 2 biến a va b để cắt tỉa 
cho thuật toán nhanh hơn

4. khác vs 2 câu trên là các con ma đi ngẫu nhiên nên hàm sẽ trả về 
tổng giá trị các điểm của các trạng thái sau khi đã thực các hành động 
chia cho tổng số hành động.

5. ý tưởng dựa trên chiến thuật ngấu nghiến thức ăn nghĩa là trạng thái nào càng
gần thức ăn thì càng được ưu tiên
