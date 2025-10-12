<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>인 다이렉트 카보험</title>
  <style>
    body {
      margin: 0;
      font-family: 'Pretendard', sans-serif;
      background-color: #f8f8f8;
      color: #222;
    }

    /* 상단 이미지 영역 */
    header {
      position: relative;
      width: 100%;
      height: 100vh; /* 화면 꽉 채움 */
      background: url('main-bg.jpg') no-repeat center center;
      background-size: contain; /* 이미지 전체 표시 */
      background-color: #000;
      display: flex;
      justify-content: flex-end; /* 오른쪽 정렬 */
      align-items: center;
      padding-right: 10%;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }

    .header-text {
      text-align: right;
      color: white;
      text-shadow: 0 0 10px rgba(0, 0, 0, 0.6);
      background: rgba(0, 0, 0, 0.3);
      padding: 20px 30px;
      border-radius: 15px;
    }

    .header-text h1 {
      font-size: 2.6rem;
      margin: 0;
      font-weight: 700;
    }

    .header-text h1 span {
      color: #2d9cdb; /* 파란색 ‘인’ 강조 */
    }

    .header-text .phone {
      margin-top: 12px;
      font-size: 1.3rem;
      color: #2d9cdb;
      font-weight: 600;
    }

    /* 보험사 카드 영역 */
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 25px;
      padding: 60px 10%;
      justify-items: center;
      background-color: #fff;
    }

    .brand-card {
      background: #fff;
      border-radius: 18px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      width: 200px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .brand-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    .brand-card img {
      width: 100%;
      height: 80px;
      object-fit: contain;
      margin-bottom: 10px;
    }

    .brand-card a {
      text-decoration: none;
      color: #222;
      font-weight: 600;
      display: block;
      margin-bottom: 6px;
    }

    .phone-number {
      font-size: 0.95rem;
      color: #007bff;
    }

    footer {
      background-color: #111;
      color: #ccc;
      text-align: center;
      padding: 25px 0;
      font-size: 0.9rem;
    }

    /* 반응형 설정 */
    @media (max-width: 768px) {
      header {
        height: 70vh;
        background-size: contain;
        justify-content: center;
        padding: 20px;
      }

      .header-text {
        text-align: center;
      }

      .header-text h1 {
        font-size: 2rem;
      }

      .header-text .phone {
        font-size: 1.1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="header-text">
      <img src="인 다이렉트 로고.jpg" alt="인 다이렉트 로고" style="width:180px; margin-bottom:10px;"><br>
      <h1><span>인</span> 다이렉트 카보험</h1>
      <div class="phone">상담전화 02-6479-7942~3</div>
    </div>
  </header>

  <main class="container">
    <div class="brand-card">
      <a href="https://direct.hi.co.kr/service.do?m=28680681ee&cnc_no=0259&media_no=B294&companyId=426" target="_blank">
        <img src="현대해상 이미지.png" alt="현대해상" />
      </a>
      <div class="phone-number">050-6279-1059</div>
    </div>

    <div class="brand-card">
      <a href="https://direct.kbinsure.co.kr/websquare/promotion.jsp?pid=1090049&code=0195&page=step1" target="_blank">
        <img src="kb 이미지.png" alt="KB손해보험" />
      </a>
      <div class="phone-number">1644-9134</div>
    </div>

    <div class="brand-card">
      <a href="https://www.directdb.co.kr/product/at/pvuatarc/step1/formStepPre.do?partner_code=C460&CNC=012" target="_blank">
        <img src="db 이미지.png" alt="DB손해보험" />
      </a>
      <div class="phone-number">1566-0626</div>
    </div>

    <div class="brand-card">
      <a href="https://direct.samsungfire.com/CR_MyAnycarWeb/overture_index.jsp?OTK=A2406AF0030" target="_blank">
        <img src="삼성화재 이미지.jpg" alt="삼성화재" />
      </a>
    </div>

    <div class="brand-card">
      <img src="한화 이미지.png" alt="한화손해보험" />
      <div class="phone-number">070-7873-3060</div>
    </div>

    <div class="brand-card">
      <img src="흥국 이미지.png" alt="흥국화재" />
      <div class="phone-number">050-6279-1060</div>
    </div>

    <div class="brand-card">
      <a href="https://www.axa.co.kr/index_email_relay.jsp?sm_flag=N&site_acq_src=0104522&cmpid=co_able_dis_sb_auto&relay_lang_type=ko&go_url=%2FActionControler.action%3FscreenID%3DSHAI0000%26actionID%3DI01%26utm_source%3Dable%26utm_medium%3Daffiliate%26utm_campaign%3Dauto&cnc_no=alble0158" target="_blank">
        <img src="회사로고2.jpg" alt="AXA손해보험" />
      </a>
    </div>

    <div class="brand-card">
      <a href="#">
        <div style="font-size: 1.1rem; font-weight: 700; color: #444; margin-top: 30px;">하나손해보험</div>
      </a>
    </div>
  </main>

  <footer>
    © 2025 인 다이렉트 카보험 | All Rights Reserved.
  </footer>
</body>
</html>
