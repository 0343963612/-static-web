# landingpage
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Thiết kế WEBSITE</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: arial
  }
    .header {
      background-color:  blue( #33ccff 0%, #ff99cc 100%);
      color: #58257b;
      padding: 10px;
      text-align: center;
  }
  .content {
      height: 450px;
      color: #000;
      padding: 10px;
      text-align: center;
  }
  .topnav {
    overflow: hidden;
    background-color: #58257b;
  }
  .topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  .topnav a:hover {
    background-color: #db7093;
    color: white;
    font-weight: bold
  }
  .left {
    float: left;
    width: 50%;
}
  .right {
    float: right;
    overflow: hidden;
    width: 50%;
}
  </style>
</head>
<body style="background-color:#fcead1;">
    <div class="header">
     <h1><b><font color="#874e47">BOOK STORE</font></b></h1>
      <marquee scrollamount="30"><h1><b><font color="red"><pre>CHÀO MỪNG BẠN ĐẾN VỚI BOOK STORE LÊ QUỐC DANH</pre></font></b></h1></marquee>
    </div>
    </div>
           <div style="width: 38%;" class="fr" class="col-4">
                  <br />
                  <style type="text/css">
                      .require { font-weight:bold; color:#F00}
                  </style>
                  <div  style="font-weight:bold;"> BẠN CÓ THỂ TÌM SÁCH TẠI ĐÂY!!</div>

                  <br />
                  <form method="post" enctype="multipart/form-data" action="/ajax/customer_contact.php">
                      <table style="width: 100%;">
                          <tr>
                              <td>THỂ LOẠI SÁCH <span class="require">*</span></td>
                              <td><input type="text" size="40" name="contact_name" id="contact_name" /></td>
                          </tr>
                          <tr>
                              <td>LỨA TUỔI <span class="require">*</span></td>
                              <td><input type="text" size="40" name="contact_email" id="contact_email" /></td>
                          </tr>
                          <tr>
                              <td>GIÁ THÀNH</td>
                              <td><input type="text" size="40" name="contact_tel" id="contact_tel" /></td>
                          </tr>
                          <tr>
                              <td>MÔ TẢ<span class="require">*</span></td>
                              <td><textarea style="width: 99%" rows="6" name="contact_message" id="contact_message"></textarea></td>
                          </tr>
                          <tr>
                              <td></td>
                              <td>
                                  <br />
                                  <input type="button" class="btn bg_pink" value="TÌM SÁCH" onclick="return check_form();" />
                              </td>
                          </tr>
                      </table>
                      <input type="hidden" value="send" name="action" />
                      <input type="hidden" name="return_url" value="/lien-he" />
                  </form>
          </div>
    <!--content-->
    <div class="content">
        <div class="left">
            <div class="text">
              <img style="height: 250px; width: auto;" src="1.jpg" />
              <h2><font color="#53ff3c">Đắc Nhân Tâm</font></h2>
              <p><b><i>Quyển sách Đắc nhắn tâm là cuốn sách “đầu tiên và hay nhất mọi thời đại về nghệ thuật giao tiếp và ứng xử”, quyển sách đã từng mang đến thành công và hạnh phúc cho hàng triệu người trên khắp thế giới.</i></b></p>
            </div>
        </div>    
        <div class="right">
            <div class="text">
              <img style="height: 250px; width: auto" src="2.jpg" />
              <h2><font color="#53ff3c">Nhà giả kim (tiểu thuyết)</font></h2>
              <p><b><i>Nhà giả kim là một cuốn sách được xuất bản lần đầu ở Brasil năm 1988 và là cuốn sách nổi tiếng nhất của nhà văn Paulo Coelho. Nó được dịch ra 67 ngôn ngữ và bán ra tới 65 triệu bản,trở thành một trong những quyển sách bán chạy nhất mọi thời đại.[1]</i></b></p>
            </div>
        </div>
    </div>
     <div class="content">
        <div class="left">
            <div class="text">
              <img style="height: 250px; width: auto" src="3.jpg" />
              <h2><font color="#53ff3c">Rich Dad, Poor Dad (Cha Giàu, Cha Nghèo) – Robert Kiyosaki</font></h2>
              <p><b><i>Một trong những nguyên nhân khiến người giàu ngày càng giàu, người nghèo ngày càng nghèo, còn giới trung lưu thì thường mắc nợ chính là vì chủ đề tiền bạc thường được dạy ở nhà chứ không phải ở trường.</i></b></p>
            </div>
        </div>    
        <div class="right">
            <div class="text">
              <img style="height: 250px; width: auto" src="4.jpg" />
              <h2><font color="#53ff3c">Trên đường băng</font></h2>
              <p><b><i>Trên đường băng là tập hợp những bài viết được ưa thích trên Facebook của Tony Buổi Sáng. </i> </b></p>
            </div>
        </div>  
    </div>
     <marquee scrollamount="50"><h1><b><font color="#1b658a"><pre>CÁC CUỐN SÁCH KHÁC</pre></font></b></h1></marquee>
    <pre><b><font color="blue">
Nếu bạn muốn giàu có và hạnh phúc mà không phải đến trường? (1992)
Nghỉ hưu sớm, nghỉ hưu giàu có (2001)
Trường học kinh doanh của người cha giàu (2003)
Ai lấy tiền của tôi (2004)
Cha giàu, cha nghèo dành cho tuổi teen (2004)
Trước khi từ bỏ công việc của bạn (2005)
    </pre></b></font>
</body>
</html>
