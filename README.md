# Track_Eval_Colab
fix error version numpy >1.20
Hướng dẫn chạy
B1: File groundtruth đổi tên là gt.txt, đặt vào trong thư mục Bee/Track_Eval/data/gt/mot_challenge/MOT17-train/MOT17-02-DPM
B2: File kết quả theo vết ong với OC-SORT đổi tên là MOT17-02-DPM.txt, để vào trong thư mục Bee/Track_Eval/data/trackers/mot_challenge/MOT17-train/MPNTrack/data
B3: Để sửa số lượng frame đánh giá, cần sửa tham số trong file seqinfo.ini nằm trong thư mục trong thư mục Bee/Track_Eval/data/gt/mot_challenge/MOT17-train/MOT17-02-DPM như sau: Mở file Track_Eval.ipynb trên Colab, chạy lệnh liên kết đến drive 🡪 Nhấn vào biểu tượng Files để mở cây thư mục 🡪 tìm và click đúp vào file seqinfo.ini để mở file này 🡪 sửa lại tham số seqLength. Chú ý: file groundtruth gt.txt và file kết quả theo vết ong MOT17-02-DPM.txt phải có cùng số lượng frame (và phải <=seqLength).
