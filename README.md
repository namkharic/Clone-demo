﻿
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css1.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" /></head>
</head>
<body>
    <script languague="javascript" >
    var x=confirm("Chào mừng bạn đến với Shark Shoes!!");
    function gio(){
        var x = new Date ();
    var a = x.getHours ();
    var b = x.getMinutes ();
    var c = x.getSeconds ();
    var hienthi=document.getElementById("result");
    hienthi.innerHTML=a+":"+b+":"+c;
}
setInterval(gio,1000);
</script>
<header>
    <div class="container-fluid header">
        <div class="row">
            <div class="col-4 a ">
                SHARK SHOES
            </div>
            <div class="col-5 b">
                <input class="search" type="text" placeholder="Tìm kiếm trong đây. . .">
                <button type="submit"><i class="fas fa-search"></i></button>
            </div>
            <div class="col-3 c">
                <a id="phone" href="#"><i class="fa-solid fa-square-phone"></i></a>
                <a id="user" href="#"><i class="fa-solid fa-circle-user"></i></a>
                <a id="cart"href="#"><i class="fa-solid fa-cart-shopping "></i></a>
            </div>
    </div>
    <div id="wrapper">
      <div id="head" class="clearfix">
          <div class="wrapper_container">
              <ul id="main_menu">
                  <li><a href="">Trang Chủ</a></li>
                  <li><a href="">Thương Hiệu</a>
                      <ul class="sub_menu">
                          <li><a href="">Adidas</a></li>
                          <li><a href="">Nike</a></li>
                          <li><a href="">Converse</a></li>
                          <li><a href="">Vans</a></li>
                          <li><a href="">NewBalance</a></li>
                      </ul>
                  </li>
                  <li><a href="">Sự Kiện</a></li>
                  <li><a href="">Ưu Đãi</a></li>
                  <li><a href="">Danh mục</a>
                    <ul class="sub_menu">
                      <li><a href="">Giày</a>
                        <ul class="sub_menu">
                          <li><a href="">Giày nam</a></li>
                          <li><a href="">Giày nữ</a></li>
                        </ul>
                        <li><a href="">Quần Áo</a>
                          <ul class="sub_menu">
                            <li><a href="">Quần áo nam</a></li>
                            <li><a href="">Quần áo nữ</a></li>
                        </ul>
                        <li><a href="">Phụ Kiện</a>
                          <ul class="sub_menu">
                            <li><a href="">Phụ kiện nam</a></li>
                            <li><a href="">Phụ kiện nữ</a></li>
                          </ul>
                    </ul>
                  </li>
                  <li><a href="">Tin tức</a></li>
                  <li><a href="">Về Chúng Tôi</a></li>
              </ul>
          </div>
      </div>
  </div>
</header>
<section>
<div id="slideshow">
    <div class="slide-wrapper">
      <div class="slide"><img src="slide/adidas.jpg"></div>
      <div class="slide"><img src="slide/converse.jpg"></div>
      <div class="slide"><img src="slide/NewBalance.jpg"></div>
    </div>
</div>
<div class="sale">
  <img src="slide/Sale1.jpg">
</div>

<div class="container-fluid middle">
  <div class="row">
      <div class="col-md-4">
          <div class="dong1">
              <a><img src="images/7filthy.jpg"></a>
              <a href="#"><p>PALLADIUM</p></a>
          </div>
          <div class="dong2">
              <a><img src="images/shoes-gc98e306c9_1280.jpg"></a>
              <a href="#"><p>ADIDAS</p></a>
          </div>
      </div>
      <div class="col-md-4">
          <div class="dong1">
              <a><img src="images/kicks-g392b3aba3_1280.jpg"></a>
              <a href="#"><p>NIKE</p></a>
          </div>
          <div class="dong2">
              <a><img src="images/shoes-g6fb3d0127_1280.jpg"></a>
              <a href="#"><p>CONVERSE</p></a>
          </div>
      </div>
      <div class="col-md-4">
          <div class="dong1">
              <a><img src="images/skate-g2e0dee077_1280.jpg"></a>
              <a href="#"><p>VANS</p></a>
          </div>
          <div class="dong2">
            <a><img src="images/shoes-gd2346f48b_1280.jpg"></a>
             <a href="#"><p>PHỤ KIỆN</p></a>
          </div>
      </div>
  </div>
</div>
<div class="container-fluid gioithieu">
    <div class="row">
        <div class="col-7">
            <h2>-NIKE-</h2>
            <p>Nike, Inc. là một tập đoàn đa quốc gia của Mỹ hoạt động trong lĩnh vực thiết kế, phát triển, sản xuất, quảng bá cũng như kinh doanh các mặt hàng giày dép, quần áo, phụ kiện, trang thiết bị và dịch vụ liên quan đến thể thao.
             Trụ sở của công ty được đặt gần Beaverton, Oregon, tại khu vực đô thị Portland. Nike là nhà cung cấp giày thể thao và quần áo lớn nhất trên thế giới và cũng là một nhà sản xuất thiết bị thể thao danh tiếng, với mức lợi nhuận
             vào năm 2018 đạt được là 36,39 tỷ USD. Vào năm 2018, tập đoàn này cũng có khoảng 73.100 nhân viên trên toàn thế giới. Thương hiệu của tập đoàn cũng được định giá là 29,6 tỷ USD vào năm 2017, trở thành thương hiệu giá trị nhất 
             trong ngành kinh doanh hàng thể thao. Nike đứng thứ 89 trong danh sách Fortune 500 vào năm 2018 xếp hạng các tập đoàn lớn nhất Hòa Kỳ tính theo tổng doanh thu...</p>
             <a href="#">Xem tất cả ></a>
        </div>
        <div class="col-5">
            <img src="images/nike pt.png">
        </div>
    </div>
</div>
<div class="mathang">
    <div class="hang">
        <div class="dong1">
            <img src="images/Nike Dunk Low Disrupt 2 Phantom University Blue (W).jfif">
        </div>
        <div class="dong2">
            <a>Nike Dunk Low Disrupt 2 Phantom University Blue</a>
        </div>
        <div class="dong3">
            <a href="#">3.239.000đ</a>
            <input class="chitiet" type="submit" value="Chi tiết">
        </div>
    </div>
    <div class="hang">
        <div class="dong1">
            <img src="images/Nike-Air-Force-1-Mid-LV8-Overbrand-_GS_.jpg">
        </div>
        <div class="dong2">
            <a>Nike Air Force 1 Mid LV8 Overbrand</a>
        </div>
        <div class="dong3">
            <a href="#">4.550.000đ</a>
            <input class="chitiet" type="submit" value="Chi tiết">
        </div>
    </div>
    <div class="hang">
        <div class="dong1">
            <img src="images/Nike-Dunk-Low-Disrupt-2-Pale-Ivory-Black-_W_.jpg">
        </div>
        <div class="dong2">
            <a>Nike Dunk Low Disrupt 2 Pale Ivory Black</a>
        </div>
        <div class="dong3">
            <a href="#">4.676.000đ</a>
            <input class="chitiet" type="submit" value="Chi tiết">
        </div>
    </div>
    <div class="hang">
        <div class="dong1">
            <img src="images/Nike-Dunk-Low-Disrupt-2-White-University-Blue-_W_.jpg">
        </div>
        <div class="dong2">
            <a>Nike Dunk Low Disrupt 2 White University Blue</a>
        </div>
        <div class="dong3">
            <a href="#">6.590.000đ</a>
            <input class="chitiet" type="submit" value="Chi tiết">
        </div>
    </div>
    <div class="hang">
        <div class="dong1">
            <img src="images/Nike-Dunk-Low-Retro-White-Black-Panda-_2021_-_W_.jpg">
        </div>
        <div class="dong2">
            <a>Nike Dunk Low Retro White Black Panda </a>
        </div>
        <div class="dong3">
            <a href="#">8.690.000đ</a>
            <input class="chitiet" type="submit" value="Chi tiết">
        </div>
    </div>
</div>
<div class="space">
    <input type="submit" value="Xem Tất Cả">
</div>
<div class="container service ">
    <div class="row">
        <div class="col-3">
            <img src="images/Free shipping.jpg">
            <div class="content_right">
                <h6>SHIP COD TOÀN QUỐC</h6>
                <p>Miễn phí vận chuyển toàn quốc cho đơn hàng từ 999.000 đ.</p>
            </div>
        </div>
        <div class="col-3">
            <img src="images/logo.jpg">
            <div class="content_right">
                <h6>CHẤT LƯỢNG TUYỆT ĐỐI 100%</h6>
                <p>Cam kết sản phẩm chính hãng đến từ Converse, Vans, Palladium, Nike và Adidas.</p>
            </div>
        </div>
        <div class="col-3">
            <img src="images/Wallet.jpg">
            <div class="content_right">
                <h6>THANH TOÁN DỄ DÀNG</h6>
                <p>Phương thức thanh toán đa dạng và cực kì tiện lợi.</p>
            </div>
        </div>
        <div class="col-3">
            <img src="images/time.jpg">
            <div class="content_right">
                <h6>TIẾT KIỆM THỜI GIAN</h6>
                <p>Mua sắm dễ hơn khi Online</p>
            </div>  
        </div>
    </div>
</div>
</section>
<footer>
    <div class="container-fluid fter">
        <div class="row">
            <div class="col-3">
                <h6>SHARK SHOES</h6>
                <i class="fa-solid fa-location-dot"></i> <span>Số nhà 7b, Phường Mỹ Đình 2, Quận Nam Từ Liêm, Thành phố Hà Nội</span><br>
                <i class="fa-solid fa-phone"></i> <span>1900 1091</span><br>
                <i class="fa-solid fa-envelope"></i> <span>ecom.@SharkShoes.vn</span><br><br>
                <h6>NHẬN ƯU ĐÃI NGAY</h6>
                <input type="text" placeholder="Nhập email của bạn">
                <input id="mail" type="submit" value="Đăng Nhập">
            </div>
            <div class="col-3">
                <h6>CHĂM SÓC KHÁCH HÀNG (8H-17H30)</h6>
               <i class="fa-sharp fa-solid fa-square-envelope"></i><span> Cskh@SharkShoes.vn</span><br>
               <i class="fa-solid fa-square-phone"></i><span> 1900876543</span>
               <p>Từ các ngày T2-T6(Trừ ngày Lễ, Tết...)</p>
            </div>
            <div class="col-3">
                <h6>CHÍNH SÁCH</h6>
                <span>Điều kiện & Điều khoản</span><br>
                <span>Chính sách đặt hàng</span><br>
                <span>Chính sách giao hàng</span><br>
                <span>Chính sách đổi trả</span><br>
                <span>Chính sách bảo mật</span><br>
                <span>Chính sách bảo hành</span><br>
                <span>Câu hỏi thường gặp</span><br><br>
                <h6>HÌNH THỨC THANH TOÁN</h6>
                <img src="images/momo.jpg">
                <img src="images/zalo.jpg">
                <img src="images/vnpay.jpg">
                <img src="images/visa.jpg">
            </div>
            <div class="col-3">
                <h6>TIN TỨC</h6>
                <Span>Thời trang</Span><br>
                <span>Khuyến mãi</span><br>
                <span>Về chúng tôi</span>
            </div>
        </div>
    </div>
<div class="space2">
    <br><br><span>&#169; Bản quyền thuộc về <i>Shark Shoes</i></span>
    <div id="result"></div>
</div>
</footer>

</body>
</html>
