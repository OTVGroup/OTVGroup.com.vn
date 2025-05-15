<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="Website chính thức của OTVGroup." />
    <meta name="author" content="OTVGroup" />
    <meta
      name="image"
      content="https://i.pinimg.com/736x/15/c2/33/15c233ab5cce7b9e60094a36653a3dc5.jpg"
    />
    <title>OTVGroup</title>
    <link
      rel="icon"
      type="image/jpeg"
      href="https://i.pinimg.com/736x/15/c2/33/15c233ab5cce7b9e60094a36653a3dc5.jpg"
    />
    <style>
      /* Cấu hình chung cho toàn bộ trang */
      body {
        font-family: Arial, sans-serif; /* Phông chữ hiện đại, dễ đọc */
        display: flex;
        flex-direction: column; /* Các phần tử con sắp xếp theo chiều dọc */
        align-items: center; /* Căn giữa theo trục ngang */
        justify-content: center; /* Căn giữa theo trục dọc */
        background-color: #000000; /* Màu nền fallback khi ảnh không load */
        color: #000000; /* Màu chữ mặc định */
        user-select: none; /* Ngăn người dùng chọn văn bản (trải nghiệm cao cấp) */
        width: 100%;
      }

      /* Cấu hình chung cho từng ngăn (section) */
      section {
        padding: 40px 20px; /* Khoảng cách bên trong ngăn, giúp thoáng đẹp */
        text-align: center; /* Căn giữa nội dung trong ngăn */
        width: 100%; /* Bắt buộc để ngăn chiếm toàn bộ chiều ngang */
        box-sizing: border-box; /* Đảm bảo padding không làm vỡ bố cục */
      }

      /* Ngăn 1: Hero */
      #hero {
        background: url("https://via.placeholder.com/1920x800") center/cover
          no-repeat;
        color: white; /* Nội dung màu trắng nổi bật trên ảnh nền */
      }

      /* Ngăn 2: Youtube */
      #youtube {
        background: white; /* Màu trắng giúp nội dung nhẹ nhàng */
      }

      /* Ngăn 3: Thông Tin */
      #projects {
        background: #e1e1e1; /* Màu xám chủ đạo */
      }

      /* Ngăn 4: Tin Mới */
      #news {
        background: #e0f7fa; /* Xanh nhạt, thân thiện */
      }

      /* Ngăn 5: Footer */
      footer {
        background: #333; /* Màu đen đậm giúp phân biệt rõ footer */
        color: white;
        padding: 40px 20px;
      }
    </style>
  </head>
  <body>
    <!-- Giao Diện -->
    <!-- Ngăn 1: Hero -->
    <section id="hero">
      <img
        src="https://i.pinimg.com/736x/15/c2/33/15c233ab5cce7b9e60094a36653a3dc5.jpg"
        alt="Logo-OTVGroup"
        height="150px"
        style="
          border-radius: 50%;
          box-shadow: 0 0 50px rgba(255, 255, 255, 0.519);
        "
      />
      <h1>Website chính thức của OTVGroup</h1>
      <form>
        <input type="text" placeholder="Tìm kiếm nhanh" width="65vh" />
        <button type="submit">Tìm kiếm</button>
      </form>
    </section>

    <!-- Ngăn 2: Youtube -->
    <section id="youtube">
      <h2>Youtube</h2>
      <div
        id="videos-container"
        style="
          display: flex;
          flex-wrap: wrap;
          gap: 20px;
          justify-content: center;
        "
      >
        <div id="videosOTVChannel" style="width: 360px"></div>
        <div id="videosOTVStory" style="width: 360px"></div>
        <div id="videosOTVGaming" style="width: 360px"></div>
      </div>
    </section>

    <!-- Ngăn 3: Thông Tin -->
    <section id="projects">
      <h2>Kết nối với chúng tôi</h2>

      <!-- Dòng 1: Facebook -->
      <div
        style="
          display: flex;
          justify-content: center;
          gap: 30px;
          flex-wrap: wrap;
          padding-top: 30px;
        "
      >
        <div style="width: 125px; text-align: center">
          <a href="https://www.facebook.com/otisvo" target="_blank">
            <img
              src="https://i.pinimg.com/736x/15/c2/33/15c233ab5cce7b9e60094a36653a3dc5.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/facebook-new.png"
                style="vertical-align: middle; margin-right: 5px"
              />Otis Võ
            </p>
          </a>
        </div>
        <div style="width: 125px; text-align: center">
          <a href="https://www.facebook.com/otisshop" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/facebook-new.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTIS Shop
            </p>
          </a>
        </div>
        <div style="width: 125px; text-align: center">
          <a href="https://www.facebook.com/otisstore" target="_blank">
            <img
              src="https://i.pinimg.com/736x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/facebook-new.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTIS Store
            </p>
          </a>
        </div>
      </div>

      <!-- Dòng 2: Các nền tảng khác -->
      <div
        style="
          display: flex;
          justify-content: center;
          gap: 30px;
          flex-wrap: wrap;
          padding-top: 30px;
        "
      >
        <div style="width: 125px; text-align: center">
          <a href="https://www.instagram.com/otisshop" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/instagram-new.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTIS Shop
            </p>
          </a>
        </div>
        <div style="width: 125px; text-align: center">
          <a href="https://www.tiktok.com/@otisshop" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/tiktok--v1.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTIS Shop
            </p>
          </a>
        </div>
        <div style="width: 125px; text-align: center">
          <a href="https://www.threads.net/@otisshop" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/ios-filled/20/000000/threads.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTIS Shop
            </p>
          </a>
        </div>
        <div style="width: 125px; text-align: center">
          <a href="https://zalo.me/otisvo" target="_blank">
            <img
              src="https://i.pinimg.com/736x/15/c2/33/15c233ab5cce7b9e60094a36653a3dc5.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/zalo.png"
                style="vertical-align: middle; margin-right: 5px"
              />Otis Võ
            </p>
          </a>
        </div>
      </div>

      <!-- Dòng 3: Youtube -->
      <div
        style="
          display: flex;
          justify-content: center;
          gap: 30px;
          flex-wrap: wrap;
          padding-top: 30px;
        "
      >
        <div style="width: 125px; text-align: center">
          <a href="https://www.youtube.com/@otvchannel" target="_blank">
            <img
              src="https://i.pinimg.com/736x/15/c2/33/15c233ab5cce7b9e60094a36653a3dc5.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/youtube-play.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTV Channel
            </p>
          </a>
        </div>
        <div style="width: 125px; text-align: center">
          <a href="https://www.youtube.com/@otvstory" target="_blank">
            <img
              src="https://i.pinimg.com/736x/09/44/f6/0944f6cacd07b3a164a82d62f02d2709.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/youtube-play.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTV Story
            </p>
          </a>
        </div>
        <div style="width: 125px; text-align: center">
          <a href="https://www.youtube.com/@otvgaming" target="_blank">
            <img
              src="https://i.pinimg.com/736x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
              width="120"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/youtube-play.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTV Gaming
            </p>
          </a>
        </div>
      </div>
    </section>

    <!-- Ngăn 4: Tin Mới -->
    <section id="news">
      <h2>Tin Mới</h2>
      <p></p>
    </section>

    <!-- Ngăn 5: Footer -->
    <footer>
      <h2>Liên hệ ngay</h2>
      <p>
        Hotline:
        <a href="tel:0329022431">0329 022 431</a>
        | Email:
        <a href="mailto:thinhkvtm2006@gmail.com">thinhkvtm2006@gmail.com</a>
      </p>
    </footer>

    <script>
      const channels = [
        { id: "UCv-PFwjDGSfgozwLVCJEv0w", target: "videosOTVChannel" }, // otvchannelvn
        { id: "UC4UOBFi4HJHU_EhynZbrefw", target: "videosOTVStory" }, // otvstoryvn
        { id: "UCM8xwnvLQ60wfEgduDRzRMg", target: "videosOTVGaming" }, // otvgamingvn
      ];

      channels.forEach((channel) => {
        fetch(
          `https://api.rss2json.com/v1/api.json?rss_url=https://www.youtube.com/feeds/videos.xml?channel_id=${channel.id}`
        )
          .then((response) => response.json())
          .then((data) => {
            let latestVideo = data.items[0];
            document.getElementById(channel.target).innerHTML = `
                    <iframe width="100%" height="215" src="https://www.youtube.com/embed/${
                      latestVideo.guid.split(":")[2]
                    }" frameborder="0" allowfullscreen loading="lazy"></iframe>
                    <h3>${latestVideo.title}</h3>
                `;
          })
          .catch((error) => {
            console.error("Lỗi tải video:", error);
            document.getElementById(
              channel.target
            ).innerHTML = `<p>Không thể tải video.</p>`;
          });
      });
    </script>
  </body>
</html>
