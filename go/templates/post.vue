{{ define "content" }} 
<!-- <link rel="stylesheet" href="post-style.css"> -->
<style type="text/css" media="screen">
@import url("/assets/css/post-style.css")
</style>
<div class="box4">
    <h2>投稿画面</h2>
        <form method="POST" action="/posts" enctype="multipart/form-data">
        <input id="title" type="text" name="title" placeholder="Title" pattern=".*\S+.*" required>
        <textarea id="body" type="text" name="body" placeholder="Body" pattern=".*\S+.*" rows="5" required></textarea>
        <input type="submit" value="送信する">
        <input type="reset" value="取消する">
    </form>
</div>
{{ end }}
