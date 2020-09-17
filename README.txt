ĐỌC FILE NÀY ĐỂ LÀM BÀI ĐÚNG

--STEP01: XEM VIDEO LAB05 ĐỂ BIẾT ĐỀ. NÊN XEM KỸ ĐỂ LÀM ĐÚNG YÊU CẦU ĐỀ
--STEP02: ĐỌC FILE NÀY
--STEP03: XEM THÊM FILE VIDEO ĐỂ HIỂU THÊM VỀ ĐỀ. BẮT ĐẦU TỪ PHÚT 45:00

CÁC KHÁI NIỆM THUẬT NGỮ:
documents are pre-processed before words are counted
stemming: remove endings for words
filter (remove) stop words

<Xem thêm tại file pdf Ref_Slides để hiểu thêm về những thuật ngữ và ví dụ 
về bài tập phân tích văn bản>

CÓ 2 TRƯỜNG CẦN ĐƯỢC QUAN TÂM NHẤT: OVERALL và REVIEWTEXT

YÊU CẦU BÀI TOÁN: XÂY DỰNG MÔ HÌNH DỰ ĐOÁN NHÃN: ĐỌC, PHÂN TÍCH XỬ LÝ DỮ LIỆU
<CHỈ ĐƯỢC SỬ DỤNG PHƯƠNG PHÁP BÌNH PHƯƠNG TỐI TIỂU>

CÁC LƯU Ý KHI LÀM BÀI NÀY:
0. Nên nghiên cứu cách đọc file JSON, vì cần đọc file này để xử lý văn bản

1. KHÔNG ĐƯỢC IMPORT THÊM THƯ VIỆN NÀO KHÁC. CHỈ ĐƯỢC SỬ DỤNG CÁC THƯ VIỆN ĐƯỢC
LIỆT KÊ SẴN TRONG FILE 180000.IPYNB. LÀM THẲNG TRÊN FILE 180000.IPYNB. Sài thoải mái các method trong số các thư viện được import sẵn

2. ĐỀ YÊU CẦU BAO NHIÊU INPUT, BAO NHIÊU OUTPUT THÌ CHỈ ĐƯỢC LÀM NHƯ VẬY. (có thể hiểu: TỨC LÀ TIỀN XỬ LÝ XONG THÌ IN RA CÁI OUTPUT NHƯ CÔ MUỐN ĐỂ CÔ KIỂM TRA, output này có thể 
là 1 câu bất kỳ sau khi đã được xử lý trong tập valid)

==> K được làm nhiều hơn hoặc ít hơn
LƯU Ý: 
train_set_path và valid_set_path được dùng để chứa dg dẫn
đg dẫn tới tập train 
đg dẫn tới tập valid
và 1 con số bất kỳ

3. CHỈ ĐƯỢC SỬ DỤNG PHƯƠNG PHÁP BÌNH PHƯƠNG TỐI TIỂU, k được sử dụng pp khác
(XEM THÊM PP này Ở FILE LAB4.IPYNB ==> làm sai hay dùng pp khác thì sẽ phải làm lại :()

4. Đọc kĩ bước a. Xử lý dữ liệu dạng văn bản. Step này 5 điểm

5. Có thể chọn cách "Sử dụng mô hình hồi quy tuyến tính bình phg tối tiểu để làm"
hoặc "sử dụng độ chính xác để đánh giá mô hình" . LƯU Ý: CHỈ 1 TRONG 2. Cách sau sẽ được tối đa 10 điểm. Nếu thấy cái sau khó quá có thể làm phần 8 điểm
(Vector i 5 chiều)

6. Xem thêm file result.png để có thể lường trước KQ (lưu ý: M1 k phải là 0.4582 mà là con số 0.54 - 0.55..)

7. PHẦN BÁO CÁO GHI HẲN TRONG FILE BÀI LÀM. BÁO CÁO TỪNG PHẦN CODE RÕ RÀNG:

	+ NÊN LÀM THEO TODOLIST CỦA CÔ: VÌ MỖI MỘT PHẦN CẦN ĐƯỢC BÁO CÁO
	+ CHỨC NĂNG CHÍNH CỦA HÀM
	+ THAM SỐ TRUYỀN VÀO GỒM NHỮNG BIẾN NÀO, CÓ KIỂU LÀ GÌ
	+ MÔ TẢ CHI TIẾT CÁCH HOẠT ĐỘNG/Ý TƯỞNG CỦA HÀM: ví dụ: vì sao làm cách này mà k dùng cách kia, làm như v được gì, dùng cách/method nào để làm, đối với trường hợp này
sẽ dùng abc, đối với TH này sẽ dùng xyz, v.v.... Nên lưu ý những điểm nào khi....
	+ KHÔNG ĐƯỢC BÁO CÁO CÁI MÌNH KHÔNG CÓ LÀM


