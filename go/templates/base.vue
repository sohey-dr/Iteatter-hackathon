<!DOCTYPE html>
<html lang="ja">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iteatter</title>
    <!-- <link rel="stylesheet" href="/templates/base-style.css"> -->
    <style type="text/css" media="screen">
    @import url("/assets/css/base-style.css")
    </style>
</head>

<body>
    <div class="box1">
        <header>
            <a href="/">
                <h1>Iteatter</h1>
            </a>
            <nav>
                <ul>
                    <li><a href="/post" methods="GET">投稿する</a></li>
                    <li><a href="/posts" methods="GET">投稿を見る</a></li>
                    <li><a href="/login" methods="GET">login</a></li>
                    <li><a href="/signup" methods="GET">signup</a></li>
                </ul>
            </nav>
        </header>
    </div>

        {{template "content" .}}

        <footer>
            <p>このアプリケーションは技育CAMP2021/vol2で作成しました</p>
        </footer>
    </div>
</body>


</html>
