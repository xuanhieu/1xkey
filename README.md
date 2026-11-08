# 1xKey: bộ gõ tiếng Việt tối giản cho macOS

> **Bộ gõ đơn giản, tối giản, thuận tiện cho người Việt chỉ muốn gõ tiếng Việt chuẩn.**

**Trang chủ và tải về:** [1xag.com/key](https://1xag.com/key) · **Nhật ký thay đổi:** [1xag.com/key/changelog](https://1xag.com/key/changelog) · **Tác giả:** [Phạm Xuân Hiếu](https://xuanhieu.org/gioi-thieu) · `/by_xuanhieu.org`

1xKey chỉ làm một việc: gõ tiếng Việt chuẩn, không lỗi, ở mọi nơi trên Mac, từ ô chat, trình duyệt, app Electron đến Terminal và các công cụ CLI. Miễn phí, mã nguồn mở.

## Vì sao dùng 1xKey

- **Gõ thẳng, không gạch chân.** Chữ hiện ra ngay khi gõ, không có vùng soạn thảo gạch chân như bộ gõ có sẵn của macOS.
- **Không mất dấu.** Có luật riêng cho ô địa chỉ trình duyệt, Google Docs, Word Online, ô chat Claude, ChatGPT, Gemini, Slack, Discord, Zalo, Teams, Messenger và Terminal.
- **Tối giản.** Không có cửa sổ cài đặt và không chiếm phím tắt nào. Menu trên thanh menu chỉ có: bật/tắt tiếng Việt, Telex hoặc VNI, Mở cùng macOS, Giới thiệu và Thông báo, Thoát. Bảng mã luôn là Unicode.
- **Gỡ được Secure Input.** Khi Chrome hay một ứng dụng khác giữ Secure Input (macOS giấu phím khỏi mọi bộ gõ), menu hiện thẻ màu cam nói rõ ứng dụng nào và có nút xử lý, ví dụ khởi động lại Chrome mà vẫn giữ nguyên tab. Ở ô mật khẩu thật, 1xKey tự nghỉ để bảo vệ mật khẩu.
- **Riêng tư.** Không dịch thuật, không đồng bộ đám mây, không telemetry, không tự cập nhật. Không ghi, không lưu, không gửi chữ bạn gõ, nhật ký chẩn đoán cũng không có chữ. Kết nối mạng duy nhất là nạp danh sách thông báo từ [1xag.com/notices.json](https://1xag.com/notices.json), tối đa mỗi ngày một lần, không gửi dữ liệu nào.
- **Nhẹ.** Khoảng 4 MB, chạy native trên Apple Silicon.

## Cài đặt

Yêu cầu: Mac chip Apple Silicon (M1 trở lên), macOS 12 trở lên.

1. Tải `1xKey.zip` ở trang [1xag.com/key](https://1xag.com/key) hoặc mục [Releases](../../releases). Kiểm tra sha256 nếu muốn.
2. Giải nén, kéo `1xKey.app` vào thư mục Applications.
3. Mở 1xKey. Lần đầu macOS sẽ chặn vì app chưa được Apple công chứng. Vào **System Settings → Privacy & Security**, bấm **Open Anyway**.
4. Cấp quyền **Accessibility** và **Input Monitoring** cho 1xKey (cũng trong Privacy & Security).
5. Chọn Input Source là **ABC** và tắt bộ gõ tiếng Việt có sẵn của Apple, để không bị thêm dấu hai lần.

Bật/tắt tiếng Việt, chọn Telex/VNI và bật "Mở cùng macOS" ngay trên menu 1xKey. Mục "Giới thiệu và Thông báo" có hướng dẫn nhanh, liên kết và tin mới.

## Nếu không gõ được

- **Thẻ cam trong menu 1xKey:** có ứng dụng đang giữ Secure Input. Làm theo hướng dẫn trong thẻ.
- **Ra chữ thô như `tuo73ng`:** kiểm tra 1xKey đã được cấp Accessibility và Input Monitoring, và công tắc "Gõ Tiếng Việt" đang bật.
- **Bị thêm dấu hai lần:** tắt bộ gõ tiếng Việt có sẵn của Apple, dùng bàn phím ABC.
- **Báo lỗi:** [github.com/xuanhieu/1xkey/issues](https://github.com/xuanhieu/1xkey/issues), ghi rõ ứng dụng và chuỗi phím đã gõ.

## Mã nguồn và giấy phép

1xKey là phần mềm tự do theo **GPL-3.0**. Mã nguồn đầy đủ: [github.com/xuanhieu/1xkey-src](https://github.com/xuanhieu/1xkey-src).

1xKey được phát triển từ [XKey](https://github.com/xmannv/xkey) của xmannv (MIT) và [OpenKey](https://github.com/tuyenvm/OpenKey) của Mai Vũ Tuyên (GPL-3.0). Xin cảm ơn hai tác giả.

## Sản phẩm khác của 1xAg

- [1xConvert](https://1xag.com/convert): giữ Shift, kéo file trong Finder, thả vào định dạng cần. Ảnh, video, âm thanh, Office, PDF, sửa font TCVN3/VNI. Chạy trên Mac, không upload.
- [1xSnap](https://1xag.com/snap): chụp một vùng màn hình, khoanh tròn, thêm mũi tên và số, dán thẳng vào cuộc trò chuyện.
- [1xSaveAs](https://1xag.com/saveas): chuột phải lưu ảnh web thành JPG, PNG hoặc WebP.
- [1xLearn](https://1xag.com/bdhvs) và [1xNote](https://1xag.com/note): tiện ích Chrome cho người học khóa video trực tuyến.
- [1xErase](https://1xag.com/rw): xóa watermark, chữ và logo khỏi ảnh bằng AI ngay trong trình duyệt.
- [Công cụ online miễn phí](https://1xag.com/playground): đổi ảnh, sửa font TCVN3/VNI sang Unicode, kiểm tra mã hóa CSV.
- Toàn bộ sản phẩm: [1xag.com](https://1xag.com)

## Chia sẻ

1xKey miễn phí. Nếu thấy hữu ích, hãy chia sẻ [1xag.com/key](https://1xag.com/key) cho bạn bè và đồng nghiệp đang khổ vì gõ tiếng Việt trên Mac.

---

© 2026 [Phạm Xuân Hiếu](https://xuanhieu.org) · [1xAg](https://1xag.com) · `/by_xuanhieu.org` · mail@xuanhieu.org
