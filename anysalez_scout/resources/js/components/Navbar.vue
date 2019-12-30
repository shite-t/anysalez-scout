<template>
  <nav class="navbar">
    <RouterLink class="navbar__brand" to="/">
      anysalez_scout
    </RouterLink>
    <div class="navbar__menu">
      <div class="navbar__item">
        <button class="button">
          <i class="icon ion-md-add"></i>
          share
        </button>
      </div>
      <span class="navbar__item">
        username
      </span>
      <div class="navbar__item">
        <RouterLink class="button button--link" to="/login">
          スカウト設定
        </RouterLink>
        <RouterLink class="button button--link" to="/login">
          スカウト状況
        </RouterLink>
        <RouterLink class="button button--link" to="/login">
          プロフィール更新
        </RouterLink>
        <RouterLink class="button button--link" to="/login">
          共有
        </RouterLink>
        <RouterLink class="button button--link" to="/login">
          ヘルプ
        </RouterLink>
        <RouterLink class="button button--link" to="/login">
          詳細設定
        </RouterLink>
        <RouterLink class="button button--link" to="/login">
          ログイン / 登録
        </RouterLink>
      </div>
    </div>
  </nav>
</template>