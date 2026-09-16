# 📄 Danh sách URL Chính sách quyền riêng tư (theo app)

> Trang `index.html` hiển thị chính sách theo tham số `?app=<key>` trên URL.
> Mỗi app (theo viện + nền tảng) dùng **một key** riêng → dán đúng link vào
> **Privacy Policy URL** khi nộp CH Play / App Store.

## 🌐 Base URL

Thay `<BASE_URL>` bằng domain thật đang host trang này (điền 1 lần):

```
<BASE_URL>/index.html?app=<key>
```

Ví dụ: nếu host tại `https://chinhsach.ttsoft.vn` thì Tuyên Quang iOS là
`https://chinhsach.ttsoft.vn/index.html?app=tuyenquangios`.

---

## ✅ App ĐẶT KHÁM bệnh nhân (medipatient) — dùng cái này

> ⚠️ **iOS dùng key riêng, tên NGẮN hơn** (yêu cầu App Store). Android giữ key thường.

| Viện | Nền tảng | `?app=` | Tên hiển thị |
|---|---|---|---|
| Tuyên Quang | Android | `tuyenquang` | BV Đa Khoa tỉnh Tuyên Quang |
| Tuyên Quang | **iOS** | **`tuyenquangios`** | **BV Tuyên Quang** |
| Phố Nối | Android | `phonoi` | BV Đa Khoa Phố Nối |
| Phố Nối | **iOS** | **`phonoiios`** | **BV Phố Nối** |
| Phương Bắc | Android/iOS | `phuongbac` | BVĐK Phương Bắc |
| Hoàng Việt | Android/iOS | `hoangviet` | BV Đa Khoa Hoàng Việt |
| Tân Việt | Android/iOS | `pktanviet` | Phòng khám Tân Việt |
| Chợ Đồn | Android/iOS | `chodon` | Bệnh Viện Chợ Đồn |
| Chiêm Hóa | Android/iOS | `chiemhoa` | TTYT Chiêm Hóa |
| Mèo Vạc | Android/iOS | `meovac` | Bệnh viện Đa Khoa Mèo Vạc |

> 📌 Viện nào sau này cần **tên iOS ngắn riêng** thì thêm key `<viện>ios` (xem mục
> "Thêm app mới" cuối file), mặc định iOS/Android dùng chung 1 key cũng được.

---

## 📚 Toàn bộ key hiện có (tra cứu nhanh)

### Đặt khám / tra cứu (bệnh nhân)
| `?app=` | Tên hiển thị | Email liên hệ |
|---|---|---|
| `phuongbac` | BVĐK Phương Bắc | bvdkphuongbac@gmail.com |
| `tuyenquang` | BV Đa Khoa tỉnh Tuyên Quang | bvdkttuyenquang@gmail.com |
| `tuyenquangios` ⭐iOS | BV Tuyên Quang | bvdkttuyenquang@gmail.com |
| `hoangviet` | BV Đa Khoa Hoàng Việt | hoangviet@gmail.vn |
| `pktanviet` | Phòng khám Tân Việt | tuankhmt@gmail.com |
| `thainguyen` | BV Trung ương Thái Nguyên | vanthu@bvdktuthainguyen.gov.vn |
| `hungyen` | BV Đa Khoa tỉnh Hưng Yên | benhviendakhoatinhhungyen@gmail.com |
| `phonoi` | BV Đa Khoa Phố Nối | hanhmy1218@gmail.com |
| `phonoiios` ⭐iOS | BV Phố Nối | hanhmy1218@gmail.com |
| `chodon` | Bệnh Viện Chợ Đồn | ttytchodon@thainguyen.gov.vn |
| `chiemhoa` | TTYT Chiêm Hóa | bvdkchiemhoa67@gmail.com |
| `meovac` | Bệnh viện Đa Khoa Mèo Vạc | bvdkmeovac@gmail.com |
| `hagiang` | DK HaGiang | info@bvdkhagiang.org.vn |
| `dkhagiang` | BV Đa Khoa Hà Giang | info@bvdkhagiang.org.vn |

### Ký số
| `?app=` | Tên hiển thị | Email |
|---|---|---|
| `thainguyenkyso` | Ký Số Thái Nguyên | vanthu@bvdktuthainguyen.gov.vn |
| `kysothainguyen` | TWTN Sign | vanthu@bvdktuthainguyen.gov.vn |
| `tuyenquangkyso` | Ký số TQ | tuyenquang@gmail.vn |
| `phuongbackyso` | PhuongBac Sign | bvdkphuongbac@gmail.com |
| `hungyenkyso` | Ký số HY | benhviendakhoatinhhungyen@gmail.com |
| `bariakyso` | Ký số BR | admin@benhvienbaria.com |

### Bệnh án / Hồ sơ (bác sĩ, đính kèm)
| `?app=` | Tên hiển thị | Email |
|---|---|---|
| `hungyenbacsi` | Bệnh án HY | benhviendakhoatinhhungyen@gmail.com |
| `hungyendinhkemfile` | Hồ sơ HY | benhviendakhoatinhhungyen@gmail.com |
| `tuyenquangbacsi` | Bệnh án TQ | tuyenquang@gmail.vn |
| `tuyenquangdinhkemfile` | Hồ sơ TQ | tuyenquang@gmail.vn |
| `thainguyenbacsi` | BADT TN | vanthu@bvdktuthainguyen.gov.vn |
| `thainguyendoctor` | Bệnh án TN | vanthu@bvdktuthainguyen.gov.vn |
| `thainguyenhoso` | Hồ sơ TN | vanthu@bvdktuthainguyen.gov.vn |
| `thainguỵendinhkemfile` ⚠️ | Attach TN | vanthu@bvdktuthainguyen.gov.vn |
| `bariabacsi` | Bệnh án BR | admin@benhvienbaria.com |
| `bariahoso` | Hồ sơ BR | admin@benhvienbaria.com |

### Mặc định
| `?app=` | Tên hiển thị | Email |
|---|---|---|
| `default` (hoặc key sai/không truyền) | ttsoft app | ttsoft@gmail.com |

---

## ⚠️ Lỗi cần sửa trong `index.html`

Key **`thainguỵendinhkemfile`** đang có ký tự lạ **`ỵ`** (không phải `y` thường).
→ Nếu app trỏ tới `?app=thainguyendinhkemfile` (chữ `y` bình thường) sẽ **KHÔNG khớp**
→ rơi về `default` ("ttsoft app"). Nên sửa key này thành `thainguyendinhkemfile`.

---

## ➕ Thêm app mới

Mở `index.html`, trong object `data = { ... }` thêm 1 mục:

```js
tenkey: {
  name: "Tên hiển thị",
  email: "email@lienhe.com"
},
```
- `tenkey`: viết **thường, không dấu, không khoảng trắng** (URL tự `.toLowerCase()`).
- Nếu iOS cần tên ngắn riêng → thêm key `tenkeyios` với `name` ngắn hơn.
- Dùng link: `<BASE_URL>/index.html?app=tenkey`.

---

_Cập nhật: 2026-09 — khi đổi `index.html` nhớ cập nhật lại file này._
