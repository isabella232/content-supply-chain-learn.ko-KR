---
title: 콘텐츠 제작 및 프로덕션 튜토리얼
description: 강력한 생성 AI와 Creative Cloud과 통합된 원활한 공동 작업 도구를 통해 관념화와 생성을 가속화합니다. Adobe은 혁신적인 AI와 함께 업계 최고의 창의적 기술을 결합하여 창의력을 발휘하고, 생산을 확장하며, 창의적인 품질을 유지합니다.
solution: Experience Cloud, Creative Cloud
feature-set: Creative Cloud
feature: Gen AI
topic: Content Management, Collaboration
role: Admin, User, Leader, Developer
level: Beginner
last-substantial-update: 2024-03-06T00:00:00Z
jira: KT-14155
source-git-commit: fecc107042220664ce5b76584f834a025844ef4b
workflow-type: tm+mt
source-wordcount: '480'
ht-degree: 7%

---


# 콘텐츠 제작 및 프로덕션 튜토리얼

강력한 생성 AI와 Creative Cloud과 통합된 원활한 공동 작업 도구를 통해 관념화와 생성을 가속화합니다. Adobe은 혁신적인 AI와 함께 업계 최고의 창의적 기술을 결합하여 창의력을 발휘하고, 생산을 확장하며, 창의적인 품질을 유지합니다.

컨텐츠 작성에 사용되는 Adobe 솔루션:

<table>
    <tr style="border: 0;">
      <td style="align: center">
        <p style="margin: 0"><img alt="Workfront" src="/help/assets/adobe-express-logo.png" style="width: 42px;height:  42px;"></p>
        <strong>고속</strong>
      </td>
      <td style="align: center">
        <p style="margin: 0"><img alt="Frame.io" src="/help/assets/frameio-logo.png" style="width: 42px;height:42px;"></p>
        <strong>Frame.io</strong>
      </td>
      <td style="align: center">
        <p style="margin: 0"><img alt="Frame.io" src="/help/assets/cce-logo.png" style="width: 42px;height:42px;"></p>
        <strong>Creative Cloud</strong>
      </td>
    </tr>
</table>

>[!TIP]
>
>당사의 Adobe 제품 전문가 팀은 주요 콘텐츠 공급망 사용 사례에 대한 통합 튜토리얼 컬렉션을 취합했습니다. 두 개 이상의 솔루션을 사용하는 경우 이러한 솔루션을 통합하는 가장 좋은 방법을 알아보십시오.  다음을 확인하십시오. [콘텐츠 공급망 통합 자습서](https://experienceleague.adobe.com/docs/integrations-learn/experience-cloud/solution-categories/content-supply-chain.html?lang=en).

## 추천 과정

<table style="margin-top:0 !important">
    <tr>
      <td style="width:33%">
        <a href="https://experienceleague.adobe.com/docs/courses/using/experiencemanager-u-1-2023-assets-essentials.html" target="_blank">
          <img alt="AEM Assets Essentials 시작하기" src="https://cdn.experienceleague.adobe.com/thumb/getting-started-with-assets-essentials.png">
        </a>
        <div>
          <a href="https://experienceleague.adobe.com/docs/courses/using/experiencemanager-u-1-2023-assets-essentials.html" target="_blank">
        <strong>AEM Assets Essentials 시작하기</strong></a>
        <p class="is-size-7 recs-limit-description">AEM Assets Essentials가 어떻게 조직의 에셋 관리를 간소화할 수 있는지 알아봅니다.</p>
        <p><a href="https://experienceleague.adobe.com/docs/courses/using/experiencemanager-u-1-2023-assets-essentials.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM"><span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 알아보기</span></a></p>
        </div>
      </td>
      <td style="width:33%">
        <a href="https://experienceleague.adobe.com/docs/courses/using/experiencemanager-a-1-2020-1-assets.html" target="_blank">
          <img alt="&apos;관리자를 위한 AEM Assets 구성&apos; 자습서의 썸네일 이미지" src="https://cdn.experienceleague.adobe.com/thumb/configuring-aem-assets-for-administrators.jpg">
        </a>
        <div>
          <a href="https://experienceleague.adobe.com/docs/courses/using/experiencemanager-a-1-2020-1-assets.html" target="_blank">
        <strong>관리자용 AEM Assets 구성</strong></a>
        <p class="is-size-7 recs-limit-description">기본 콘텐츠 아키텍처 및 분류 체계 설정부터 메타데이터 및 에셋 처리 사용자 지정에 이르기까지 핵심 사항을 구성하여 AEM Assets 구현을 위한 견고한 기반을 구축하는 방법을 알아봅니다.</p>
        </div>
        <p><a href="https://experienceleague.adobe.com/docs/courses/using/experiencemanager-a-1-2020-1-assets.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM"><span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 알아보기</span></a></p>
      </td>
    </tr>
</table>

## 튜토리얼

<div class="columns is-multiline"><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Integrate Adobe Workfront and AEM Assets Essentials" tabIndex="0">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="Adobe Workfront 및 AEM Assets Essentials 통합" tabindex="-1">
          <img class="is-bordered-r-small" src="https://cdn.experienceleague.adobe.com/thumb/docs-workfront.png" alt="Adobe Workfront 및 AEM Assets Essentials 통합">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="Adobe Workfront 및 AEM Assets Essentials 통합">Adobe Workfront 및 AEM Assets Essentials 통합</a>
          </p>
          <p class="is-size-6"><em>Workfront 및 AEM Assets Essentials를 통합하여 크리에이티브 워크플로 관리를 간소화하는 방법에 대해 알아봅니다.</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 알아보기</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Use Adobe Workfront plugins to integrate with Creative Cloud" tabIndex="1">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-integrations/workfront-for-creative-cloud/wf-adobe-cc.html" title="Adobe Workfront 플러그인을 사용하여 Creative Cloud와 통합" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3415452?format=jpeg" alt="Adobe Workfront 플러그인을 사용하여 Creative Cloud와 통합">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-integrations/workfront-for-creative-cloud/wf-adobe-cc.html" title="Adobe Workfront 플러그인을 사용하여 Creative Cloud와 통합">Adobe Workfront 플러그인을 사용하여 Creative Cloud과 통합</a>
          </p>
          <p class="is-size-6"><em>Workfront을 Creative Cloud과 통합하여 Adobe Creative Cloud을 종료하지 않고 할당된 작업을 찾아 업데이트합니다.</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-integrations/workfront-for-creative-cloud/wf-adobe-cc.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">비디오 보기</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Configure Adobe Workfront and AEM Assets Essentials" tabIndex="2">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html" title="Adobe Workfront 및 AEM Assets Essentials 구성" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/336254?format=jpeg" alt="Adobe Workfront 및 AEM Assets Essentials 구성">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html" title="Adobe Workfront 및 AEM Assets Essentials 구성">Adobe Workfront 및 AEM Assets Essentials 구성</a>
          </p>
          <p class="is-size-6"><em>Adobe Workfront 및 Assets Essentials 통합을 구성하는 방법 알아보기</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">비디오 보기</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Workfront enhanced connector basics" tabIndex="3">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" title="Workfront 강화 커넥터 기본 사항" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/337575?format=jpeg" alt="Workfront 강화 커넥터 기본 사항">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" title="Workfront 강화 커넥터 기본 사항">Workfront 강화 커넥터 기본 사항</a>
          </p>
          <p class="is-size-6"><em>Adobe Workfront 및 Experience Manager Assets 강화 커넥터의 기본 사항에 대해 알아봅니다.</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">비디오 보기</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Integrate Workfront and AEM Assets with the enhanced connector" tabIndex="4">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html" title="향상된 커넥터와 Workfront 및 AEM Assets 통합" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/340331?format=jpeg" alt="향상된 커넥터와 Workfront 및 AEM Assets 통합">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html" title="향상된 커넥터와 Workfront 및 AEM Assets 통합">향상된 커넥터와 Workfront 및 AEM Assets 통합</a>
          </p>
          <p class="is-size-6"><em>향상된 커넥터를 사용하여 Workfront과 AEM Assets 통합에 대한 4부 비디오 시리즈입니다.</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">비디오 보기</span>
      </a>
    </div>
  </div>
</div></div>

<!--
<table class="tablelayout-is-fixed">
<tr>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html">
      <img alt="Integrate Adobe Workfront and AEM Assets Essentials" src="https://cdn.experienceleague.adobe.com/thumb/docs-workfront.png">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html">
    <strong>Integrate Adobe Workfront and AEM Assets Essentials</strong>
    </a>
    </div>
    <p>
    <em>Learn how to integrate Workfront and AEM Assets Essentials to streamline the management of creative workflows.</em>
    </p><p>
  </p></td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/integrations/adobe-creative-cloud/use-adobe-workfront-extensions-for-creative-cloud.html">
      <img alt="Use Adobe Workfront plugins to integrate with Creative Cloud" src="https://video.tv.adobe.com/v/3415452?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/integrations/adobe-creative-cloud/use-adobe-workfront-extensions-for-creative-cloud.html">
    <strong>Use Adobe Workfront plugins to integrate with Creative Cloud</strong>
    </a>
    </div>
    <p>
    <em>Integrate Workfront with Creative Cloud to find and update the work assigned to you without leaving Adobe Creative Cloud.</em>
    </p><p>
  </p></td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html">
    <img alt="Configure Adobe Workfront and AEM Assets Essentials" src="https://video.tv.adobe.com/v/336254?format=jpeg">
    </a>
    <div>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html">
    <strong>Configure Adobe Workfront and AEM Assets Essentials</strong>
    </a>
    </div>
    <p>
    <em>Learn how to configure the Adobe Workfront and Assets Essentials integration</em>
    </p>
  </td>
  </tr>
  <tr>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html">
      <img alt="Workfront enhanced connector basics" src="https://video.tv.adobe.com/v/337575?format=jpeg">
    </a>
     <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html">
        <strong>Workfront enhanced connector basics</strong>
      </a>
    </div>
    <p>
    <em>Learn about the basics of the Adobe Workfront and Experience Manager Assets enhanced connector.</em>
    </p>
  </td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html">
      <img alt="Integrate Workfront and AEM Assets with the enhanced connector" src="https://video.tv.adobe.com/v/340331?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html">
    <strong>Integrate Workfront and AEM Assets with the enhanced connector</strong>
    </a>
    </div>
    <p>
    <em>Four part videos series on integrating Workfront and AEM Assets using the enhanced connector.</em>
    </p><p>
  </p></td>  
</tr>
</table>
-->

## 추가 리소스

* [Experience League 이벤트](https://experienceleague.adobe.com/events/)
* [콘텐츠 공급망의 Adobe](https://business.adobe.com/resources/webinars/adobe-on-the-content-supply-chain.html)
