---
layout: post
title: GDPR (General Data Protection Regulation)
author: dev
date: '2018-02-28 04:37'
image: /static/images/gdpr_main.jpg
cover:
  link: ''
  title: ''
tags:
  - research
  - GDPR
published: true
---
> GDPR (General Data Protection Regulation)이 다가옵니다! 커밍 순!

2018년 5월 25일, 드디어 EU(유럽연합)의 GDPR(General Data Protection Regulation)이 시행됩니다. 새해가 밝자마자, 여러 매체에서는 GDPR을 전체 비즈니스업계의 최대 이슈로 선정하기도 했는데요.

GDPR은 General Data Protection Regulation의 약자로 유럽연합의 일반 정보 보호 규정을 말합니다. 1995년부터 시행된 정보보호지침을 대체하는 법으로 2016년 4월 EU의회에 의해 승인되었고, 2018년 5월 25일부터 발효됩니다. 기존 법이 Directive(입법지침 가이드라인)이었다면, GDPR은 Regulation으로 법적 구속력을 가지며, 모든 EU회원국들에게 직접적으로 적용됩니다. 법적 성격이 바뀌었을 뿐만 아니라 GDPR은 개인정보에 관련된 규제의 범위와 개념을 상당 부분 넓히는 법이라고 할 수 있는데요. 어떤 것이 얼마나 달라졌을까요?

# \#적용대상이 달라졌다.

“설마 EU법인데 우리 나라에도 적용되겠어?” 라는 생각을 하실 수도 있겠습니다. 그러나 GDPR은 지리적 범위에만 적용 되는 것은 아닙니다. 이 어마어마한 법의 적용범위는 꽤 넓은데요. EU시민의 개인정보를 처리하는 기업 중에, 다음과 같은 기업이 해당됩니다.

![](/static/images/GDPR_1.png)

유럽법인을 가지고 있는 국내 최대 게임사 ‘넥슨’도 GDPR에 대응하기 위한 예산을 따로 책정해 놓았다고 하네요. 위 적용 대상에 해당되는 기업들은 미리미리 준비해야겠습니다. D-DAY가 다가오니까요!

# \#결국 모든 것은 개인정보다.

두 번째로 개인정보(Personal Data)의 ‘정의’가 달라졌습니다. 앞서 GDPR이 개인정보에 관련된 개념을 상당 부분 넓힌다고 말씀 드렸는데요. GDPR에서는 개인정보 (Personal Data)를 직간접적으로 ‘사람’을 식별할 수 있는 데이터로 규정하고 있습니다. 또한 현행법과는 달리 온라인 식별자 정보 (IP주소, 쿠키, 디바이스ID, 광고 ID 등…)도 ‘사람’을 식별할 수 있다고 판단합니다. 어떤 데이터들이 개인정보에 포함될까요? 결론은, “거의 모두 다 포함된다.” 입니다.

![](/static/images/GDPR_2.png)

# \#동의

가장 눈에 띄게 달라진 것은 사용자의 ‘동의’ 부분입니다. 위에서 명시한 개인정보를 수집하고 사용하는 모든 기업들은 GDPR이 발효되고 난 후부터 개인정보를 수집할 때, 이용의 명확한 목적을 밝히고 개인정보 주체의 뚜렷하고! 명료한! 동의를 얻어야 합니다. 뚜렷하고 명료한 동의란 무엇을 말하는 걸까요? 여기서 퀴즈 하나 나갑니다! 다음 쿠키 사용 동의 배너는 GDPR 동의 기준을 충족할까요?

![](/static/images/GDPR_3.png)

“당신에게 향상된 서비스를 제공하기 위해, 우리는 쿠키를 수집하고 있습니다. 이 웹사이트를 계속 사용하면, 쿠키정책에 동의하는 것으로 간주하겠습니다.” 이런 문구 많이 보셨죠? 현행법상 이러한 쿠키 사용 동의 배너는 합법이지만, GDPR이 발효되고 난 후부터, 이런 식으로 EU시민의 쿠키 사용 동의를 얻는다면? 모두 불법입니다! 왜 안될까요? GDPR이 정의하는 동의와 관련해서 여러 가지 지켜야 할 조항들이 있습니다. **살펴보시죠!**

![](/static/images/GDPR_4.png)

퀴즈에서 보여드렸던 동의서는 정보를 수집하는 기업의 명확한 정보도 없었고, 수집의 목적도 구체적으로 제시하지도 않았습니다. 또한, 이 웹사이트를 계속 이용하면, 개인정보 사용 정책에 동의하는 것으로 간주한다? 정보주체의 적극적인 행위로 동의가 이루어지지도 않았습니다. 앞으로 이런 방식의 동의서는 모두 법을 위반하는 것이 됩니다. 그렇다면 어떻게 동의서를 만들어야 할까요?

![](/static/images/GDPR_5.png)

바로 이렇게 만들어야 합니다! PageFair에서 만든 동의서 예시를 보면 “우리는 당신의 개인 정보를 6개월 동안 수집할 것입니다. 보관하는 이유는 당신의 프로필을 더 구체적으로 만들어서 인사이트를 추출하고 당신과 관계 있는 광고를 보여주기 위함입니다. 그리고 당신의 프로필은 이런 것 저런 것들을 포함하고 있답니다.” 라는 문구가 적혀있습니다. 개인정보 수집의 목적, 보관 기관, 수집하는 정보의 종류 모두 구체적으로 설명합니다. 그리고 아래쪽에는 개인정보와 관련된 기업정보들이 모두 제공되고 있습니다. 동의 체크도 해지되어 있네요. 만약 사용자가 이 동의서에 동의 체크를 한다면, 적극적인 의사로 동의를 표현했다고 판단할 수 있을 것입니다.

정확한 정보 제공, 자유로운 동의 선택권. GDPR은 개인정보에 접근하는 방법을 새롭게 바꿔놓고 있습니다. GDPR의 동의 기준을 따르지 않으면 어떻게 될까요? 최대 2천만 유로(한화 약 245억원) 또는 총 매출액의 4% 중 더 큰 금액을 내야 합니다.

# \#개인정보를 소중히 지켜주세요.

또 GDPR은 기업은 개인정보를 가능한 ‘최소로’ 수집할 것, ‘최소한’의 기간에만 보관할 것, 그리고 개인정보 취급 및 처리와 관련해서 ‘적합한’ 기술 및 조직 차원의 조치를 이행해야 한다고 명시합니다. 개인정보를 보호하기 위한 안정장치를 마련하라는 것으로 해석할 수 있는데요. GDPR은 권한 없는 처리, 불법적 처리 및 정보 파괴 또는 손상에 대비한 적절한 보안을 보장하는 방식을 갖추어야 한다고 말합니다. 그러나 ‘적합한’ 기술에 대한 명확한 기준이 없기 때문에, 당분간은 이 조항을 ‘위반’했다고 판단하기는 어렵겠습니다.

다만 위에서 말하는 개인정보에 대한 보안을 보장하지 못하는 상황이 온다면, 예를 들어 개인 정보가 파괴되었거나 유출되었다면 기업은 즉시 이를 감독 기관에 보고해야 합니다. 보안 사고를 통지하지 않으면 최대 1천만 유로 또는 총 매출액의 2% 중 더 큰 금액을 과징금으로 내야 합니다. 개인정보 처리에 대한 기업의 책임감을 강조하는 조항이라고 볼 수 있겠습니다.

# \#우리는 GDPR을 환영합니다!

GDPR에서 정의하는 개인정보를 수집하지 않으면서 온라인 사업을 영위할 수 있을까요? 타겟팅(Targeting)에 대한 수요도가 증가하면서 이를 위해 온라인 식별자를 수집하고, 모바일 앱이나 웹을 최적화하기 위해 쿠키를 사용하는 일은 현재 아주 흔하게 일어나고 있습니다. 또한 유럽은 세계에서 가장 큰 온라인 시장 중 하나입니다. 어떤 비즈니스가 GDPR을 피할 수 있을까요?

아니나다를까, 새해의 시작과 함께 페이스북이나 구글 같은 글로벌 기업들은 GDPR에 대한 생각들과 준수하기 위한 대책들을 발표했습니다. 그리고 “진심으로 GDPR을 환영해! 잘 지킬게!”라고 말하고 있네요. 페이스북 발표 내용을 간단하게 정리했습니다. 보고 오시죠.

![](/static/images/GDPR_6.png)

# \#우리가 도와줄게요.

GDPR을 준수하는 것 자체가 어려운 기업들이 분명히 존재할 것입니다. 동의 규정도 매우 까다로워졌고, 개인정보를 처리하기 위해서는 이제 ‘적합한’ 수준의 기술이 요구되니까요. 그래서인지 GDPR과 관련된 새로운 비즈니스가 우후죽순처럼 쏟아지고 있습니다. GDPR을 준수할 수 있도록 도와주는 툴킷, 솔루션, 컨설팅 상품이 떠오르는 비즈니스 모델이 되고 있습니다.

이미 AWS (Amazon Web Services Cloud)에서도 두려움에 떨고 있는 고객들을 위한 ‘GDPR 준수’ 솔루션들을 상품으로 가지고 있는데요. 대표적으로 액세스 제어, 모니터링 및 로깅, 데이터 암호화에 대한 서비스를 제공하고 있습니다. 또한 AWS 환경에서 GDPR을 지키기 위한 백서도 마련해 놓았습니다. IBM도 적극적으로 GDPR 총괄 지원 상품을 홍보하고 있습니다. GDPR가 새로운 비즈니스 분야도 만들어냈네요! 아래 그림은 그 예입니다.

![](/static/images/GDPR_7.png)

# \#당신의 비즈니스는 어디에 있습니까?

긴 글을 마치며, 묻고 싶습니다. 우리의 비즈니스는 얼마나 GDPR에 준비되어 있을까요? 서론에서 언급한 것처럼, GDPR은 유럽에만 적용된다고 보기는 힘듭니다. EU시민의 개인 정보를 다루는 기업이라면 모두 적용 대상에 해당됩니다. 그리고 개인 정보에 대한 개념과 범위를 확장했다는 점, 기존의 개인정보 보안에 대한 문제점을 해결할 수 있다는 점에서 얼마든지 다른 국가에서도 적용을 고려해 볼 가능성이 크다고 생각합니다.

그러나 eMarketer의 최근 조사에 따르면, 북미 IT기업중 단 6%만이 GDPR에 대응할 준비가 되어있다고 응답했습니다. 한국의 기업은 더 준비가 되어있지 않습니다. 3달이 채 남지 않은 지금은, 조금씩이라도 준비해야 할 때라고 생각합니다. 또한 GDPR이 본격적으로 시행되면서 기업이 개인 정보에 대한 책임감을 무겁게 느끼게 되었으면 좋겠습니다. 우리의 정보는 소중하니까요.