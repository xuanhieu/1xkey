# 1xKey: bộ gõ tiếng Việt tối giản cho macOS

> **Bộ gõ đơn giản, tối giản, thuận tiện cho người Việt chỉ muốn gõ tiếng Việt chuẩn.**

**Trang chủ và tải về:** [1x.xuanhieu.org/key](https://1x.xuanhieu.org/key) · **Tác giả:** [Phạm Xuân Hiếu](https://xuanhieu.org/gioi-thieu)

1xKey chỉ làm một việc: gõ tiếng Việt chuẩn, không lỗi, ở mọi nơi trên Mac, từ ô chat, trình duyệt, app Electron đến Terminal và các công cụ CLI.

## Vì sao dùng 1xKey

- **Gõ thẳng, không gạch chân.** Chữ hiện ra ngay khi gõ, không có vùng soạn thảo gạch chân như bộ gõ có sẵn của macOS.
- **Không mất dấu.** Có luật riêng cho ô địa chỉ trình duyệt, Google Docs, Word Online, ô chat Claude, ChatGPT, Gemini, Slack, Discord, Zalo, Teams, Messenger và Terminal.
- **Tối giản.** Không có cửa sổ cài đặt. Menu trên thanh menu chỉ gồm: bật/tắt tiếng Việt, Telex hoặc VNI, Thoát. Bảng mã luôn là Unicode.
- **Riêng tư.** Không có dịch thuật, không đồng bộ đám mây, không telemetry, không tự cập nhật. App không kết nối mạng. Log chẩn đoán không bao giờ ghi chữ bạn gõ.
- **Nhẹ.** Khoảng 7,6 MB, chạy native trên Apple Silicon.
- **Tôn trọng ô mật khẩu.** Tự tắt khi macOS bật Secure Input.

## Cài đặt

Yêu cầu: Mac chip Apple Silicon (M1 trở lên).

1. Tải `1xKey-1.0.0.zip` ở trang [1x.xuanhieu.org/key](https://1x.xuanhieu.org/key) hoặc mục [Releases](../../releases). Kiểm tra sha256 nếu muốn.
2. Giải nén, kéo `1xKey.app` vào thư mục Applications.
3. Mở 1xKey. Lần đầu macOS sẽ chặn vì app chưa được Apple công chứng. Vào **System Settings → Privacy & Security**, bấm **Open Anyway**.
4. Cấp quyền **Accessibility** và **Input Monitoring** cho 1xKey (cũng trong Privacy & Security).
5. Chọn Input Source là **ABC** và tắt bộ gõ tiếng Việt có sẵn của Apple, để không bị thêm dấu hai lần.

Bật/tắt tiếng Việt: dùng menu 1xKey trên thanh menu, hoặc phím ⌘⇧V.

## Mã nguồn và giấy phép

1xKey là phần mềm tự do theo **GPL-3.0**. Mã nguồn đầy đủ: [github.com/xuanhieu/1xkey-src](https://github.com/xuanhieu/1xkey-src).

1xKey được phát triển từ [XKey](https://github.com/xmannv/xkey) của xmannv (MIT) và [OpenKey](https://github.com/tuyenvm/OpenKey) của Mai Vũ Tuyên (GPL-3.0). Xin cảm ơn hai tác giả.

## Sản phẩm khác của Xuân Hiếu (1x)

- [1xQuickConvertFormat](https://1x.xuanhieu.org/qcf): giữ Shift, kéo file trong Finder, thả vào định dạng cần. Ảnh, video, âm thanh, Office, PDF, sửa font TCVN3/VNI. Chạy trên Mac, không upload.
- [Bình Dân Học Vụ Số Pro](https://1x.xuanhieu.org/bdhvs): tiện ích Chrome cho người học khóa video trực tuyến.
- [Save Image as JPG, PNG, WebP](https://1x.xuanhieu.org/save-image-as): chuột phải lưu ảnh web thành JPG, PNG hoặc WebP.
- [Sửa font TCVN3, VNI sang Unicode](https://1x.xuanhieu.org/playground/fix-vietnamese-fonts): công cụ online miễn phí.
- Toàn bộ sản phẩm: [1x.xuanhieu.org](https://1x.xuanhieu.org)

## Chia sẻ

1xKey miễn phí. Nếu thấy hữu ích, hãy chia sẻ [1x.xuanhieu.org/key](https://1x.xuanhieu.org/key) cho bạn bè và đồng nghiệp đang khổ vì gõ tiếng Việt trên Mac.

---

© 2026 [Phạm Xuân Hiếu](https://xuanhieu.org) · [xuanhieu.org](https://xuanhieu.org) · mail@xuanhieu.org
