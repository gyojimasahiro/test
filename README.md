<style>
    /* 非表示にしたい要素用のクラス */
    .hidden {
        display: none;
    }
    
    .container {
        max-width: 600px;
        margin: 20px auto;
        padding: 10px;
    }
    
    .menu-container {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 120px 120px 120px;
        gap: 10px;
    }
    
    .menu-item {
        background-color: #f0f8ff;
        border-radius: 10px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        color: #333;
        transition: all 0.3s ease;
    }
    
    .menu-item:hover {
        transform: translateY(-3px);
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        background-color: #81d4fa; /* ホバー時に少し濃い水色に */
    }
    
    .menu-item h3 {
        margin: 0;
        font-size: 20px; /* テキストのサイズを大きくしました */
        font-weight: bold;
    }
    
    .menu-item.full-width {
        grid-column: span 2;
    }
    
    header {
        text-align: center;
        padding: 10px;
        margin-bottom: 20px;
        background-color: #e6f2ff;
        border-radius: 10px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    
    /* ヘッダー画像用のスタイル */
    .header-image {
        width: 100%;
        max-width: 600px;
        height: auto;
        border-radius: 6px;
    }
</style>

<div class="container">
    <header>
        <!-- ビズレントのヘッダー画像 -->
        <img src="images" class="header-image">
    </header>

    <h2>ビズレント各種項目</h2>
    <p>クリックして各ページへ移動できます</p>

    <div class="menu-container">
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSdgU-3mybGRR_K-7eO6__I9P7Xrh0WeXE_A9mRVMbwz2iqAYQ/viewform?usp=header" class="menu-item">
            <h3>新規発注</h3>
        </a>
        
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSdgU-3mybGRR_K-7eO6__I9P7Xrh0WeXE_A9mRVMbwz2iqAYQ/viewform?usp=header" class="menu-item">
            <h3>車両の一時預かり</h3>
        </a>
        
        <a href="https://www.twitter.com" class="menu-item">
            <h3>車検のご予約</h3>
        </a>
        
        <a href="https://www.instagram.com" class="menu-item">
            <h3>事故受け付け</h3>
        </a>
        
        <a href="https://www.amazon.co.jp" class="menu-item full-width">
            <h3>車両に関しての資料</h3>
        </a>
    </div>
</div>
