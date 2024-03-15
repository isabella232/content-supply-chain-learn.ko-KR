---
title: 자산 관리 자습서
description: 컨텐츠 제작 및 완료에 이르는 계획 프로세스를 통해 컨텐츠 요구 사항을 연결하고 추적하기 위해 고군분투하는 기업 프로젝트 전반에 걸쳐 효과적인 프로세스, 계획, 승인 및 데이터 일관성이 결여되어 이 회사의 콘텐츠 공급망은 생산성과 효율성을 모두 저해하고 있습니다.
solution: Experience Cloud, Experience Manager Assets
feature-set: Experience Manager, Experience Manager Assets
feature: Asset Management, Asset Processing
topic: Content Management, Collaboration, Artificial Intelligence
role: Admin, User, Leader, Developer
level: Beginner
last-substantial-update: 2024-03-06T00:00:00Z
jira: KT-15076
source-git-commit: f3082975a674a13152aa92c06302e67e9f4715b6
workflow-type: tm+mt
source-wordcount: '1075'
ht-degree: 3%

---


# 자산 관리 자습서

브랜드 일관성을 보장하면서 단일 클라우드 기반 솔루션에서 수백만 개의 자산에 손쉽게 액세스하고 재사용할 수 있습니다.  이 자습서는 Adobe Experience Manager Assets 사용에 중점을 둡니다.


>[!TIP]
>
>당사의 Adobe 제품 전문가 팀은 주요 콘텐츠 공급망 사용 사례에 대한 통합 튜토리얼 컬렉션을 취합했습니다. 두 개 이상의 솔루션을 사용하는 경우 이러한 솔루션을 통합하는 가장 좋은 방법을 알아보십시오.  다음을 확인하십시오. [콘텐츠 공급망 통합 자습서](https://experienceleague.adobe.com/docs/integrations-learn/experience-cloud/solution-categories/content-supply-chain.html?lang=en).

## 추천 과정
<div class="columns is-multiline">
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets - Assets View] Bulk Import - Feature Video" tabIndex="0">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html" title="[AEM Assets - 에셋 보기] 일괄 가져오기 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3426857?format=jpeg" alt="[AEM Assets - 에셋 보기] 일괄 가져오기 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html" title="[AEM Assets - 에셋 보기] 일괄 가져오기 - 기능 비디오">[AEM Assets - 에셋 보기] 일괄 가져오기 - 기능 비디오</a>
          </p>
          <p class="is-size-6">Dropbox을 명확하고 따라하기 쉬운 통합 프로세스를 위한 예제 클라우드 스토리지 공급자로 사용하여 일괄 가져오기 기능을 사용하여 많은 파일을 AEM Assets으로 가져오는 방법에 대해 알아봅니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials][Workfront] Assets Essentials and Workfront integration - Catalog" tabIndex="1">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="[Asset Essentials][Workfront] Assets Essentials 및 Workfront 통합 - 카탈로그" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3422184?format=jpeg" alt="[Asset Essentials][Workfront] Assets Essentials 및 Workfront 통합 - 카탈로그">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="[Asset Essentials][Workfront] Assets Essentials 및 Workfront 통합 - 카탈로그">[Asset Essentials][Workfront] Assets Essentials 및 Workfront 통합 - 카탈로그</a>
          </p>
          <p class="is-size-6">Workfront 및 Assets Essentials을 통합하는 방법을 알아봅니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Adobe Express integration - Feature Video" tabIndex="2">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="[AEM Assets] Adobe Express 통합 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3425193?format=jpeg" alt="[AEM Assets] Adobe Express 통합 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="[AEM Assets] Adobe Express 통합 - 기능 비디오">[AEM Assets] Adobe Express 통합 - 기능 비디오</a>
          </p>
          <p class="is-size-6">AEM Assets 및 Adobe Express을 통해 콘텐츠 공급망을 최적화하여 모든 팀원의 생산성과 접근성을 향상시키는 방법에 대해 알아봅니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Adobe Express] Empower marketing teams to create multi-channel content - Feature video" tabIndex="3">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] 마케팅 팀이 멀티채널 콘텐츠를 만들 수 있는 권한 부여 - 주요 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3424446?format=jpeg" alt="[Adobe Express] 마케팅 팀이 멀티채널 콘텐츠를 만들 수 있는 권한 부여 - 주요 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] 마케팅 팀이 멀티채널 콘텐츠를 만들 수 있는 권한 부여 - 주요 비디오">[Adobe Express] 마케팅 팀이 멀티채널 콘텐츠를 만들 수 있는 권한 부여 - 주요 비디오</a>
          </p>
          <p class="is-size-6">이벤트 마케팅 팀이 온라인 이벤트에 대한 시청자를 끌어들이기 위해 고유한 콘텐츠를 만드는 방법을 알아봅니다. 이 워크플로에서 B2B 마케터는 Adobe Express 키트 및 라이브러리의 템플릿을 사용하여 브랜드의 새 프로젝트를 시작합니다. B2B 마케터는 다양한 소셜 및 웹 채널에 대한 변형을 만들고 소셜 미디어 및 비디오 호스팅 플랫폼에서 콘텐츠를 공유합니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Workfront Enhanced Integration Basics - Feature Video" tabIndex="4">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" title="[AEM Assets] Workfront 향상된 통합 기본 사항 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/337575?format=jpeg" alt="[AEM Assets] Workfront 향상된 통합 기본 사항 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" title="[AEM Assets] Workfront 향상된 통합 기본 사항 - 기능 비디오">[AEM Assets] Workfront 향상된 통합 기본 사항 - 기능 비디오</a>
          </p>
          <p class="is-size-6">에셋 및 폴더를 연결하고, 메타데이터 매핑을 정의하고, 에셋을 AEM으로 전송하고, 에셋을 버전 관리하고 에셋을 자동 게시하는 방법을 포함하여 Adobe Workfront 및 Experience Manager Assets Enhanced Integration의 기본 사항에 대해 알아봅니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] AEM and Adobe Asset Link Creative Workflow - Value Video" tabIndex="5">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="[AEM Assets] AEM 및 Asset Link Adobe 크리에이티브 워크플로 - 가치 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/335927?format=jpeg" alt="[AEM Assets] AEM 및 Asset Link Adobe 크리에이티브 워크플로 - 가치 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="[AEM Assets] AEM 및 Asset Link Adobe 크리에이티브 워크플로 - 가치 비디오">[AEM Assets] AEM 및 Asset Link Adobe 크리에이티브 워크플로 - 가치 비디오</a>
          </p>
          <p class="is-size-6">AAL 및 AAM을 사용하는 사용자의 크리에이티브 워크플로를 보여 주는 비디오</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AJO] Create content with the Email Designer - Feature Video" tabIndex="6">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] 이메일 디자이너를 사용하여 콘텐츠 만들기 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/334150?format=jpeg" alt="[AJO] 이메일 디자이너를 사용하여 콘텐츠 만들기 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] 이메일 디자이너를 사용하여 콘텐츠 만들기 - 기능 비디오">[AJO] 이메일 디자이너를 사용하여 콘텐츠 만들기 - 기능 비디오</a>
          </p>
          <p class="is-size-6">처음부터 이메일을 작성하는 방법에 대해 알아봅니다. AEM Assets Essentials 라이브러리에서 에셋을 사용하고, 반응형 이메일 디자인을 편집하고, 템플릿에서 이메일을 작성하는 방법에 대해 이해합니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials] Getting started with Assets Essentials - Feature Video" tabIndex="7">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html" title="[Asset Essentials] Assets Essentials 시작하기 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/336005?format=jpeg" alt="[Asset Essentials] Assets Essentials 시작하기 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html" title="[Asset Essentials] Assets Essentials 시작하기 - 기능 비디오">[Asset Essentials] Assets Essentials 시작하기 - 기능 비디오</a>
          </p>
          <p class="is-size-6">Assets Essentials이 직관적이고 사용자 친화적인 사용자 인터페이스를 제공하여 에셋 및 관련 정보를 쉽게 찾고 기억할 수 있도록 하는 방법에 대해 알아봅니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Content Automation - Value video" tabIndex="8">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] 컨텐츠 자동화 - 가치 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/333197?format=jpeg" alt="[AEM Assets] 컨텐츠 자동화 - 가치 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] 컨텐츠 자동화 - 가치 비디오">[AEM Assets] 컨텐츠 자동화 - 가치 비디오</a>
          </p>
          <p class="is-size-6">Adobe Experience Manager Assets 컨텐츠 자동화와 함께 Photoshop 및 Lightroom 기능을 적용하는 개요입니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Metadata profiles - Feature Video" tabIndex="9">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] 메타데이터 프로필 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/33974?format=jpeg" alt="[Assets] 메타데이터 프로필 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] 메타데이터 프로필 - 기능 비디오">[Assets] 메타데이터 프로필 - 기능 비디오</a>
          </p>
          <p class="is-size-6">메타데이터 프로필을 사용하면 자산 폴더 내의 자산에 기본 메타데이터를 자동으로 적용할 수 있으므로 AEM 사용자의 메타데이터 관리 부담을 줄이고 메타데이터 일관성을 높일 수 있습니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Navigation - Feature Video" tabIndex="10">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="[Assets] 탐색 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32046?format=jpeg" alt="[Assets] 탐색 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="[Assets] 탐색 - 기능 비디오">[Assets] 탐색 - 기능 비디오</a>
          </p>
          <p class="is-size-6">AEM Assets 탐색의 기본 사항을 살펴보십시오.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Comments and Annotations - Feature Video" tabIndex="11">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] 댓글 및 주석 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32049?format=jpeg" alt="[Assets] 댓글 및 주석 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] 댓글 및 주석 - 기능 비디오">[Assets] 댓글 및 주석 - 기능 비디오</a>
          </p>
          <p class="is-size-6">AEM에서 주석 및 주석을 사용하여 에셋에 대해 통신하고 공동 작업하는 방법을 알아봅니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Search - Feature Video" tabIndex="12">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="[Assets] 검색 - 주요 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32054?format=jpeg" alt="[Assets] 검색 - 주요 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="[Assets] 검색 - 주요 비디오">[Assets] 검색 - 주요 비디오</a>
          </p>
          <p class="is-size-6">AEM Omnisearch를 사용하여 에셋을 빠르게 검색하는 방법에 대해 알아봅니다.</p>
        </div>
        <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Download - Feature Video" tabIndex="13">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="[Assets] 다운로드 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/35090?format=jpeg" alt="[Assets] 다운로드 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="[Assets] 다운로드 - 기능 비디오">[Assets] 다운로드 - 기능 비디오</a>
          </p>
          <p class="is-size-6">사용 및 공유를 위해 자산 및 해당 표현물을 로컬 시스템에 다운로드하는 방법에 대해 알아봅니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] AEM Desktop App 2.0 - Feature Video" tabIndex="14">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html" title="[Assets] AEM 데스크탑 앱 2.0 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/28868?format=jpeg" alt="[Assets] AEM 데스크탑 앱 2.0 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html" title="[Assets] AEM 데스크탑 앱 2.0 - 기능 비디오">[Assets] AEM 데스크탑 앱 2.0 - 기능 비디오</a>
          </p>
          <p class="is-size-6">AEM Desktop App을 사용하여 모든 응용 프로그램 및 파일 형식에 대해 데스크톱의 AEM에서 관리되는 에셋에 대한 액세스를 단순화합니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] DM Smart Image Crop - Feature Video " tabIndex="15">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html" title="[Assets] DM 스마트 이미지 자르기 - 주요 비디오 " tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/21519?format=jpeg" alt="[Assets] DM 스마트 이미지 자르기 - 주요 비디오 ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html" title="[Assets] DM 스마트 이미지 자르기 - 주요 비디오 ">[Assets] DM 스마트 이미지 자르기 - 주요 비디오 </a>
          </p>
          <p class="is-size-6">스마트 자르기는 Adobe Sensei을 사용하여 반응형 디자인을 위한 콘텐츠 자르기에 드는 시간과 비용을 없애줍니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Asset Source File Translation - Feature Video" tabIndex="16">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] 자산 소스 파일 변환 - 기능 비디오" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/18331?format=jpeg" alt="[Assets] 자산 소스 파일 변환 - 기능 비디오">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] 자산 소스 파일 변환 - 기능 비디오">[Assets] 자산 소스 파일 변환 - 기능 비디오</a>
          </p>
          <p class="is-size-6">Adobe Experience Manager(AEM) Assets를 사용하면 새로운 관련 에셋 기능을 사용하여 공통 속성을 공유하는 에셋을 식별하고 관련 에셋으로 표시할 수 있습니다.</p>
        </div>
        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">자세히 보기</span>
        </a>
      </div>
    </div>
  </div>
</div>

## 추가 리소스

* [Experience League 이벤트](https://experienceleague.adobe.com/events/)
* [콘텐츠 공급망의 Adobe](https://business.adobe.com/resources/webinars/adobe-on-the-content-supply-chain.html)
