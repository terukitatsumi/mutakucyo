<template>
  <main>
    <!-- メインビジュアル -->
    <div id="mainvisual">
      <picture>
        <source media="(max-width: 600px)" :srcset="require('@/assets/main-sp.jpg')" />
        <img :src="require('@/assets/main-pc.jpg')" alt="テキストテキストテキスト" />
      </picture>
    </div>

    <!-- About -->
    <section id="about" class="wrapper">
      <h2 class="sec-title">About</h2>
      <ul>
        <li>空調整備会社</li>
        <li>空調整備の仕事をおこなっています。</li>
        <li>空調設備のメンテナンスや保守点検</li>
        <li>メールアドレス：xxxxxxx@xxx.com</li>
      </ul>
      <p>
        保守・メンテナンス作業は空調設備を長く使用できるように定期的にケアする作業のことです。
        一般的な作業内容は異常がないか点検した上で、適宜フィルターのクリーニング、空調ガスの補充、機器の洗浄などを実施します。
      </p>
    </section>

    <!-- Works -->
    <section id="works" class="wrapper">
      <h2 class="sec-title">Works</h2>
      <ul>
        <li><img :src="require('@/assets/works1.jpg')" alt="work1" /></li>
        <li><img :src="require('@/assets/works2.jpg')" alt="work2" /></li>
        <li><img :src="require('@/assets/works3.jpg')" alt="work3" /></li>
        <li><img :src="require('@/assets/works4.jpg')" alt="work4" /></li>
        <li><img :src="require('@/assets/works5.jpg')" alt="work5" /></li>
        <li><img :src="require('@/assets/works6.jpg')" alt="work6" /></li>
        <li><img :src="require('@/assets/works2.jpg')" alt="work1" /></li>
        <li><img :src="require('@/assets/works4.jpg')" alt="work2" /></li>
        <li><img :src="require('@/assets/works1.jpg')" alt="work3" /></li>
      </ul>
    </section>

    <!-- News -->
    <section id="news" class="wrapper">
      <h2 class="sec-title">News</h2>
      <dl>
        <dt>2024/12/10</dt>
        <dd>本サイトをリリースしました。</dd>
        <dt>2024/12/10</dt>
        <dd>こんにちは。</dd>
        <dt>2024/12/10</dt>
        <dd>よろしくお願いいたします。</dd>
      </dl>
    </section>

    <!-- Contact -->
    <section id="contact" class="wrapper">
      <h2 class="sec-title">Contact</h2>
      <p>お問い合わせは以下のフォームから</p>
      <form action="#" method="post">
        <dl>
          <dt><label for="name">お名前</label></dt>
          <dd><input type="text" id="name" /></dd>
          <dt><label for="email">メールアドレス</label></dt>
          <dd><input type="email" id="email" /></dd>
          <dt><label for="content">内容</label></dt>
          <dd><textarea id="content" cols="30" rows="10"></textarea></dd>
        </dl>
        <div class="button"><input type="submit" value="送信" /></div>
      </form>
    </section>
  </main>
</template>

<script>
export default {
  name: 'MainContent'
}
</script>

<style scoped>
/* メインコンテンツ専用のスタイルがあればここに記述 */
</style>
