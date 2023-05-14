# Transformer-Machine-Translation
Dịch từ tiếng Anh sang tiếng Việt
# Dữ liệu 
Dữ liệu là các title của những bài báo Tiếng Anh được dịch sang tiếng Việt do mình tạo ra
# Xử lý
- Đối với input sẽ là các câu tiếng Anh, ta sẽ sử dụng Tokenizer từ thư viện transformers của Hugging face một model pretrain là bert-basde-uncased
- Đối với outpt sẽ là các câu Tiếng Việt, ta sẽ sử dụng tương tự như trên nhưng model sẽ là vinai/phobert-base
