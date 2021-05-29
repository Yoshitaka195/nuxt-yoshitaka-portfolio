<template>
  <vs-row vs-w="12">
    <vs-col vs-lg="3" vs-md="2" vs-xs="1"></vs-col>
    <vs-col vs-lg="6" vs-md="8" vs-xs="10">
      <vs-col vs-type="flex" vs-justify="center">
        <vs-avatar
          size="150px"
          src="https://yoshitaka-portfolio.s3-ap-northeast-1.amazonaws.com/DDF93DD4-80CD-4CA4-84F7-A9E39422DD9F_1_201_a.jpeg"
        />
      </vs-col>
      <vs-col vs-type="flex" vs-justify="center">
        <h1 class="title">
          Yoshitaka Portfolio <span class="subtitle">by Nuxt.js</span>
        </h1>
      </vs-col>
      <vs-col>
        <h2>About</h2>
        <p class="subtitle">
          <br />
          はじめまして、ご覧いただきありがとうございます。<br />
          バックエンドを中心に業務を行なっている 水沼 能嵩 です。<br /><br />
          大学卒業後、新卒未経験としてシステム受託開発会社に就職。複数のWebシステム開発経験を経た後、最新技術に対する知見を深め、技術力向上を目指すべく、都内のスタートアップ企業へと転職をしました。<br /><br />
          現在はCtoCレンタルプラットフォームサービスの新規開発におけるフロントエンドからバックエンド、インフラ構築にあたるまで幅広い開発業務を経験しています。<br /><br />
          キャッチアップとレスポンスの早さを武器に、常に向上心を持って前向きに業務・自主学習に取り組んでいます。<br /><br />
          よろしくお願いいたします！
        </p>
      </vs-col>
      <vs-col>
        <h2>Skill set</h2>
        <vs-list>
          <vs-list-header icon="description" title="対応言語"></vs-list-header>
          <vs-list-item title="PHP / Java / Python / JavaScript"></vs-list-item>
          <vs-list-header
            icon="batch_prediction"
            title="フレームワーク・ライブラリ"
            color="success"
          >
          </vs-list-header>
          <vs-list-item
            title=" Laravel / Vue.js / Nuxt.js / jQuery"
          ></vs-list-item>
          <vs-list-header icon="storage" title="RDB" color="danger">
          </vs-list-header>
          <vs-list-item
            title=" MySQL / PostgreSQL / SQL Server "
          ></vs-list-item>
          <vs-list-header icon="cloud" title="AWS" color="warning">
          </vs-list-header>
          <vs-list-item
            title="EC2 / S3 / RDS / Route53 / APIGateway / Lambda / Elemental MediaConvert / CodeBuild / CodeDeploy / CodePipeline "
          ></vs-list-item>
          <vs-list-header icon="build" title="その他" color="dark">
          </vs-list-header>
          <vs-list-item title=" GitHub / Docker / SVN"></vs-list-item> </vs-list
      ></vs-col>
      <vs-col>
        <h2>Learning</h2>
        <vs-chip color="primary">TypeScript</vs-chip>
        <vs-chip color="primary">Golang</vs-chip>
        <vs-chip color="success">React</vs-chip>
        <vs-chip color="success">Next.js</vs-chip>
        <vs-chip color="warning">ECS</vs-chip>
        <vs-chip color="dark">Terraform</vs-chip>
        <vs-chip color="dark">Kurbenetes</vs-chip>
      </vs-col>
    </vs-col>
    <vs-col vs-lg="3" vs-md="2" vs-xs="1"></vs-col>
  </vs-row>
</template>

<script></script>
<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 55px;
  color: #35495e;
  letter-spacing: 1px;
  text-transform: capitalize;
  margin: 25px 0;
}
.subtitle {
  font-weight: 300;
  font-size: 1.1rem;
  color: #526488;
  word-spacing: 2px;
  padding-bottom: 15px;
}
.subtitle a {
  font-weight: 500;
  color: inherit;
}
.links {
  padding-top: 15px;
  margin-bottom: 20px;
}
.content-logos {
  display: flex;
  align-items: center;
  justify-content: center;
  min-width: 500px;
}
.plus {
  font-size: 2.5rem;
  margin: 15px;
  color: #35495e;
}
h2 {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  margin: 20px 0px;
}
h3 {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-weight: 400;
  margin: 10px;
}
</style>
