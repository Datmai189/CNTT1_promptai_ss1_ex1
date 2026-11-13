Phương án 1
Hãy phân loại tin nhắn khách hàng vào đúng một trong ba nhóm:
TÍCH CỰC: Khen sản phẩm ngon hoặc rẻ
TIÊU CỰC: Chê giao hàng chậm hoặc thái độ phục vụ tệ
CẦN HỖ TRỢ: Hỏi địa chỉ cửa hàng hoặc hỏi giá
Khi đưa ra câu trả lời chỉ cần trả lời không cần nói tên nhóm chứ không nói chi tiết nhóm đó
Với câu : “Quán phục vụ chu đáo quá, bắt khách đợi hẳn 1 tiếng!” sẽ đưa vào nhóm TIÊU CỰC vì khách đang mỉa mai rằng quán phục vụ quá lâu
Phương án 2
Hãy phân loại tin nhắn khách hàng vào một trong ba nhóm: TÍCH CỰC, TIÊU CỰC, CẦN HỖ TRỢ. Chỉ cần trả lời tên nhóm
Vd1: “Đồ ăn ngon mà giá lại rẻ.” > trả lời TÍCH CỰC
Vd2: “Quán phục vụ chu đáo quá, bắt khách đợi hẳn 1 tiếng!” > trả lời TIÊU CỰC
Vd3: “Quán mình ở địa chỉ nào vậy?” > trả lời CẦN HỖ TRỢ
Bảng so sánh Trade-off
Tiêu chí                Zero-shot                        Few-shot
Cách làm                Chỉ đưa luật phân loại           đưa luật và 3 ví dụ
Câu mỉa mai             Dễ nhầm “chu đáo” là lời khen    Nhận ra khách đang chê vì phải đợi lâu
Token sử dụng           xử lý nhanh hơn,nhưng ít token   tốn nhiều token hơn nhưng xử lý câu khó hiệu quả hơn
                        nên dễ sai câu khó
Thử nghiệm thực tế :
Sau khi đưa lên GPT thì có kết quả là
Khi chạy prompt đầu tức phương án 1 thì có khả năng Zero-shot chọn nhầm TÍCH CỰC , Few-shot có khả năng chọn TIÊU CỰC cao hơn so với chọn TÍCH CỰC
