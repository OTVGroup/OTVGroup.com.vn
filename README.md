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
        padding: 30px 20px; /* Khoảng cách bên trong ngăn, giúp thoáng đẹp */
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
      #youtube-videos {
        background: white; /* Màu trắng giúp nội dung nhẹ nhàng */
      }

      /* Ngăn 3: Tin Mới */
      #facebook-reels {
        background: #e0f7fa; /* Xanh nhạt, thân thiện */
      }

      /* Ngăn 4: Thông Tin */
      #more-channels {
        background: #e1e1e1; /* Màu xám chủ đạo */
      }

      /* Ngăn 5: Footer */
      footer {
        background: #333; /* Màu đen đậm giúp phân biệt rõ footer */
        color: white;
        width: 100%;
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
    <section id="youtube-videos">
      <h2>Youtube Videos</h2>
      <div
        id="videos-container"
        style="
          display: flex;
          flex-wrap: wrap;
          gap: 15px;
          justify-content: center;
        "
      >
        <div id="videosOTVChannel" style="width: 360px"></div>
        <div id="videosOTVStory" style="width: 360px"></div>
        <div id="videosOTVGaming" style="width: 360px"></div>
      </div>
    </section>

    <!-- Ngăn 3: Tin Mới -->
    <section id="facebook-reels">
      <h2>Facebook Reals</h2>
      <div
        style="
          display: flex;
          justify-content: center;
          gap: 15px;
          flex-wrap: wrap;
          padding-top: 30px;
        "
      >
        <div style="width: 100px; text-align: center">
          <a href="https://www.facebook.com/OtisVo586" target="_blank">
            <img
              src="https://i.pinimg.com/736x/15/c2/33/15c233ab5cce7b9e60094a36653a3dc5.jpg"
              width="80"
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
        <div style="width: 100px; text-align: center">
          <a href="https://www.facebook.com/OtisGamerVN" target="_blank">
            <img
              src="https://i.pinimg.com/736x/34/59/6a/34596a4db3932a3855c872c2f4833e5d.jpg"
              width="80"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/facebook-new.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTISStore
            </p>
          </a>
        </div>
        <div style="width: 100px; text-align: center">
          <a href="https://www.facebook.com/OtisSeller" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="80"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/facebook-new.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTISShop
            </p>
          </a>
        </div>
      </div>
      <!-- Nhúng reel hoặc bài viết Facebook -->
      <div id="fb-root"></div>
      <script
        async
        defer
        crossorigin="anonymous"
        src="https://connect.facebook.net/vi_VN/sdk.js#xfbml=1&version=v18.0"
      ></script>

      <!-- Container chứa các post -->
      <div
        style="
          display: flex;
          flex-wrap: wrap;
          gap: 15px;
          justify-content: center;
          max-width: 1200px;
          margin: auto;
        "
      >
        <!-- Bài 1 -->
        <div
          style="
            max-width: 360px;
            max-height: 640px;
            background: #1a1a1a;
            border-radius: 8px;
            color: #eee;
            box-sizing: border-box;
          "
        >
          <div
            class="fb-post"
            data-href="https://www.facebook.com/OtisSeller/posts/672996332031027"
            data-width="360"
            data-show-text="true"
          ></div>
          <p style="font-size: 16px; margin-top: 12px">
            Chờ đợi hoài một điều diệu kì...🌱
          </p>
        </div>

        <!-- Bài 2 -->
        <div
          style="
            max-width: 360px;
            max-height: 640px;
            background: #1a1a1a;
            border-radius: 8px;
            color: #eee;
            box-sizing: border-box;
          "
        >
          <div
            class="fb-post"
            data-href="https://www.facebook.com/OtisSeller/videos/693901322996665"
            data-width="360"
            data-show-text="true"
          ></div>
          <p style="font-size: 16px; margin-top: 12px">
            OTISSTORE - Uy Tín Tạo Nên Thương Hiệu!
          </p>
        </div>

        <!-- Bài 3 -->
        <div
          style="
            max-width: 360px;
            max-height: 640;
            background: #1a1a1a;
            border-radius: 8px;
            color: #eee;
            box-sizing: border-box;
          "
        >
          <div
            class="fb-post"
            data-href="https://www.facebook.com/OtisSeller/posts/122138746688611769"
            data-width="360"
            data-show-text="true"
          ></div>
          <p style="font-size: 16px; margin-top: 12px">
            OTISShop | Chất Lượng - Uy Tín - Tin Cậy.
          </p>
        </div>
      </div>
    </section>

    <!-- Ngăn 4: More Channels -->
    <section id="more-channels">
      <h2>More Channels</h2>
      <div
        style="
          display: flex;
          justify-content: center;
          gap: 15px;
          flex-wrap: wrap;
          padding-top: 30px;
        "
      >
        <div style="width: 100px; text-align: center">
          <a href="https://www.instagram.com/otisshopvn" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="80"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/instagram-new.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTISShop
            </p>
          </a>
        </div>
        <div style="width: 100px; text-align: center">
          <a href="https://www.tiktok.com/@otisshop" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="80"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/color/20/tiktok--v1.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTISShop
            </p>
          </a>
        </div>
        <div style="width: 100px; text-align: center">
          <a href="https://www.threads.net/@otisshopvn" target="_blank">
            <img
              src="https://i.pinimg.com/736x/ea/24/e1/ea24e1a0ed40857020ab39336b9fc78c.jpg"
              width="80"
              style="border-radius: 50%; box-shadow: 0 0 5px rgba(0, 0, 0, 0.2)"
            />
            <p>
              <img
                src="https://img.icons8.com/ios-filled/20/000000/threads.png"
                style="vertical-align: middle; margin-right: 5px"
              />OTISShop
            </p>
          </a>
        </div>
      </div>
      <div
        style="
          display: flex;
          flex-wrap: wrap;
          gap: 15px;
          justify-content: center;
          max-width: 1200px;
          margin: auto;
        "
      >
        <!-- Instagram Post -->
        <div style="width: 360px; flex-shrink: 0">
          <blockquote
            class="instagram-media"
            data-instgrm-permalink="https://www.instagram.com/reel/DGCafd-IIfu/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA=="
            data-instgrm-version="14"
            style="width: 360px"
          ></blockquote>
          <script async src="//www.instagram.com/embed.js"></script>
        </div>

        <!-- TikTok Post -->
        <div style="width: 360px; flex-shrink: 0">
          <blockquote
            class="tiktok-embed"
            cite="https://www.tiktok.com/@otisshop/video/7503553465981930760"
            data-video-id="7503553465981930760"
            style="width: 360px"
          >
            <section></section>
          </blockquote>
          <script async src="https://www.tiktok.com/embed.js"></script>
        </div>

        <!-- Threads Post -->
        <!-- <div style="width: 360px; flex-shrink: 0">
          <iframe
            src="https://www.threads.net/@otisshopvn/post/DBfkPY1PZlu"
            width="360"
            frameborder="0"
            scrolling="no"
            allowfullscreen
          ></iframe>
        </div> -->
      </div>
    </section>

    <!-- Ngăn 5: Footer -->
    <footer
      style="
        background: #121212;
        color: #e4e4e4;
        font-family: sans-serif;
        padding: 30px 0;
      "
    >
      <div
        style="
          display: flex;
          justify-content: center;
          flex-wrap: wrap;
          max-width: 1200px;
          margin: auto;
          text-align: center;
        "
      >
        <!-- Contact -->
        <div style="flex: 1; min-width: 200px">
          <h3>Contact</h3>
          <ul style="list-style: none; padding: 0; line-height: 1.5">
            <li>
              Zalo:
              <a
                href="https://zalo.me/0329022431"
                target="_blank"
                style="color: #007aff; text-decoration: none"
              >
                0329 022 431
              </a>
            </li>
            <li>
              Hotline:
              <a
                href="tel:0329022431"
                style="color: #007aff; text-decoration: none"
              >
                0329 022 431
              </a>
            </li>
            <li>
              Email:
              <a
                href="mailto:thinhkvtm2006@gmail.com"
                style="color: #007aff; text-decoration: none"
              >
                thinhkvtm2006@gmail.com
              </a>
            </li>
          </ul>
        </div>

        <!-- Donate -->
        <div style="flex: 1; min-width: 200px">
          <h3>Donate</h3>
          <ul style="list-style: none; padding: 0; line-height: 1.5">
            <li>
              <a
                href="https://nhantien.momo.vn/0843840438"
                target="_blank"
                style="
                  display: inline-block;
                  background: #c8102e;
                  color: #fff;
                  padding: 1px;
                  margin: 2.5px 0;
                  border-radius: 2px;
                  text-decoration: none;
                "
                >Momo: 0843 840 438</a
              >
            </li>
            <li>
              <a
                href="https://vietqr.net/9704056607205230700"
                target="_blank"
                style="
                  display: inline-block;
                  background: #c8102e;
                  color: #fff;
                  padding: 1px;
                  margin: 2.5px 0;
                  border-radius: 2px;
                  text-decoration: none;
                "
              >
                Agribank: 6607205230700
              </a>
            </li>
          </ul>
        </div>
      </div>
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
