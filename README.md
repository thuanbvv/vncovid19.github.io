# Vietnam COVID-19 Open data and visualization

Dữ liệu mở thu thập từ trang [thông tin chính thức](https://ncov.moh.gov.vn) của [Bộ Y Tế Việt Nam](https://moh.gov.vn), dùng cho data visualization.

Một số thông tin được thu thập bổ sung từ trang [Wiki Đại dịch COVID-19 tại Việt Nam](https://vi.wikipedia.org/wiki/%C4%90%E1%BA%A1i_d%E1%BB%8Bch_COVID-19_t%E1%BA%A1i_Vi%E1%BB%87t_Nam).

## Mô tả trường dữ liệu:

```js
{
    "17": // số thứ tự bệnh nhân, xem như ID
    {
        "positiveDate": "2020-03-06",  // ngày xác nhận dương tính
        "dischargeDate": "2020-03-22", // ngày xác xác nhận khỏi bệnh
        "gender": "female",            // male or female
        "age": 26,                     // tuổi, gán -1 nếu không có
        "treatmentLocation": "Hà Nội", // địa phương nơi có bệnh viện bệnh nhân được chữa
        "residence": "Hà Nội",     // nơi cư trú
        "nationality": "Việt Nam", // quốc tịch
        "status": "positive",      // tình trạng hiện tại (positive, negative, deseased)
        "flights": ["VN0054"],     // (các) mã chuyến bay
        "source": ["Anh"],         // nguồn lây từ (nước, ổ dịch hoặc mã BN)
        "description": "Nữ 26 tuổi đi thăm chị gái tại Anh và qua Italy, Pháp và trở về Hà Nội ngày 2/3/2020"
    }
}
```

## Tài nguyên

- Icon cờ các nước: https://freeflagicons.com/buy/round_icon/
- Danh sách mã quốc gia 2 ký tự ISO-3166: https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes
