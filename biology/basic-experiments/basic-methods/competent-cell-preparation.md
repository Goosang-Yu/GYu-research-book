---
description: Rubidium chloride를 사용한 형질전환용 박테리아 제작
---

# Competent cell preparation

_E.Coli_에 원하는 외래DNA (plasmid)를 전달하는 '형질전환'은 생명공학 연구자들이 거의 매일 같이 사용하는 실험 기법이다. 일반적인 _E.Coli_는 plasmid를 쉽게 안으로 도입할 수 없으나, 인공적인 처리를 한 경우에는 훨씬 쉽게 세포 안으로 plasmid를 받아들일 수 있는 상태가 된다. 이렇게 형질전환이 쉽게 일어나는 세포를 competent cell이라고 한다.&#x20;

본 글에서는 heat shock으로 형질전환을 할 수 있는 competent cell을 제작하는 방법에 대해 다룬다.&#x20;

## 수용성 세포 (competent cell)의 원리





## Competent cell 제작 방법

{% hint style="info" %}
본 방법은 E.Coli 2L culture를 기준으로 작성하였다.&#x20;
{% endhint %}

### 0. 요약

{% tabs %}
{% tab title="준비과정" %}
제작에 필요한 재료들을 준비한다.&#x20;

* Plain E.Coli (DH5a) cell colony
* [RF-1 buffer](competent-cell-preparation.md#rf-1-buffer-1000ml)
* [RF-2 buffer](competent-cell-preparation.md#rf-2-buffer-200ml)

Deep freezer를 넉넉넉하게 비워둔다.
{% endtab %}

{% tab title="1일차" %}
1. E.Coli strain (DH5a) stock을 녹인 후, plain LB agar plate에 도말한다.
2. 37℃에서 다음 날까지 키운다.&#x20;
{% endtab %}

{% tab title="2일차" %}
1. Single colony를 30mL plain LB broth에 접종한다.&#x20;
2. 37℃에서 다음 날까지 키운다.
{% endtab %}

{% tab title="3일차" %}
실험 테이블과 파이펫 에이드 등을 에탄올로 깨끗하게 닦아둔다.&#x20;

Dry ice와 얼음 등을 미리 준비해둔다.

1. Culture 6mL을 600mL LB에 넣고, 37℃에서 2시간 15분간 배양한다. (OD 값 약 0.4\~0.6)
2. Culture flask를 ice에 15분간 둔다.
3. Culture 용액을 50mL conical tube에 분주한다.&#x20;
4. 3500 rpm, 4℃로 30분간 centrifuge 한다.
5. 상층액을 버린다.
6. 50mL tube 하나 당 RF-1 buffer 15mL씩 넣고 pellet을 풀어준다.
7. 얼음에 1시간 15분간 둔다.
8. 3500 rpm, 4℃로 30분간 centrifuge 한다.
9. 상층액을 버린다.
10. 50mL tube 하나 당 RF-2 buffer 2-3mL씩 넣고 pellet을 풀어준다.
11. 얼음에 15분간 둔다.
12. EP tube에 분주하고 바로 deep freezer에 넣는다.&#x20;
{% endtab %}
{% endtabs %}

### 1. 재료 / 기구 준비

| Material                              | Company           | Cat.No.        | Comments                                                                                                                             |
| ------------------------------------- | ----------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Beakers                               |                   |                | <mark style="color:red;">Autoclaved</mark>                                                                                           |
| Glass mass cylinder                   |                   |                | <mark style="color:red;">Autoclaved</mark>                                                                                           |
| Magnetic bars                         |                   |                | <mark style="color:red;">Autoclaved</mark>                                                                                           |
| Glass bottles                         |                   |                | <mark style="color:red;">Autoclaved</mark>                                                                                           |
| Bottle-top filter                     | Corning           | 431118         |                                                                                                                                      |
| EP tube                               | Axygen            | MCT-175-C      | <mark style="color:red;"></mark>[<mark style="color:red;">Autoclaved</mark>](#user-content-fn-1)[^1]<mark style="color:red;"></mark> |
| Conical tubes                         | SPL               |                |                                                                                                                                      |
| Distilled water (DW)                  |                   |                | <mark style="color:red;">Autoclaved</mark>                                                                                           |
| LB Ager / Broth                       | Duchefa Biochemie | L1706 / L1704  | Plain LB 사용                                                                                                                          |
| Rubidium Chloride (RbCl2)             | Sigma             | R2252          |                                                                                                                                      |
| Manganous Chloride (MnCl2•4H2O)       | Duksan            | 83C221         |                                                                                                                                      |
| Potassium Acetate                     | Sigma             | P1190          | <mark style="color:red;">Autoclaved</mark> (3M solution)                                                                             |
| Calcium Chloride (CaCl2•2H2O)         | Sigma             | C5670          |                                                                                                                                      |
| Glycerol                              | Sigma             | G5516          | <mark style="color:red;">Autoclaved</mark>                                                                                           |
| MOPS[^2]                              | Sigma             | M1254 or M1442 | Powder / solution (1M)                                                                                                               |
| [Acetic acid](#user-content-fn-3)[^3] | Duksan            | D414           | pH 조절을 위해 사용 (0.2M)                                                                                                                  |
| Sodium Hydroxide (NaOH)               | TCI               | S0543          | <p>pH 조절을 위해 사용 (0.1N)<br>* Do Not Autoclave</p>                                                                                     |

#### 0.2M acetic acid 만들기 (40ml 기준)

Acetic acid, glacial (CH3COOH)의 molecular weight은 60.05g•mol-1이다. Density는 1.05g/cm3 이다. 이를 이용해 molar concentration을 계산하여 물에 희석하여 만든다.&#x20;

0.2M 40ml 기준, 480.4mg이 필요하므로, 약 39.54ml 물에 457.52uL glacial acetic acid를 희석한다.

#### 3M potassium acetate (pH 7.5) 만들기 (80ml 기준)

1. 자석 stirrer가 들어있는 비커에 50ml DW를 담고, 23.55g의 Potassium acetate를 녹인다.&#x20;
2. 그 다음, 0.2M acetic acid를 이용해서 pH를 7.5로 맞춘다.&#x20;
3. 마지막으로 DW를 채워서 최종 80ml로 맞춘다.&#x20;
4. 이 용액을 autoclave (121℃ for 15-20min)해서 멸균한다.

<figure><img src="../../../.gitbook/assets/Potassium acetate pH (1).png" alt=""><figcaption><p>Potassium acetate buffer pH 맞추기</p></figcaption></figure>

{% hint style="warning" %}
Potassium acetate는 결정이 단단히 뭉치는 성질이 강해서 통에서 덜어내기 위해 덩어리를 깨는데 고생스러웠다. 또한 묻은 부분이 굉장히 미끄러워지므로 도구들을 떨어뜨리지 않게 주의가 필요하다.

Potassium acetate 자체의 부피가 굉장히 크기 때문에, pH 조절하기 전에 이미 80ml에 가까워졌다. 처음 용해시킬 때, 충분히 적은 양의 증류수에서 시작해야할 것 같다.

60ml DW에 potassium acetate 23.6g을 넣었을 때, 측정된 pH는 9.01이었다. 찾아본 자료에 따르면 일반적인 potassium acetate solution pH는 7.5\~8.5라고 나와있는데, 예상보다 높게 나온 것 같다. 0.2M acetic acid 기준, 8.75ml을 넣었을 때, pH 7.6이 되었다. 80ml을 넘어설 것 같아서 추가적은 pH 조절은 하지 않았다.
{% endhint %}

#### 0.5M MOPS 제작하기 (1000mL 기준)

1. DW 700mL에 3-N-morpholino propanesulfonic acid (MOPS) 104.6g을 녹인다.
2. 1N NaOH (=1M NaOH)를 이용해서 pH 6.8로 맞춘다.
3. DW를 추가하면서 최종 부피 1000mL로 맞춘다.
4. 0.2um membrane bottle-top filter로 거른 후 4℃에서 보관한다.

{% hint style="info" %}
MOPS solution (sigma, M1442)을 구매하여 사용하면 훨씬 편리하다. 1M 농도인 것으로 판매하므로, 이를 희석해서 쓰거나, 최종 농도만 맞게끔 넣는 양을 조절하여 사용.
{% endhint %}

### 2. Buffer 제작

#### RF-1 buffer 만들기 (1000mL 기준)

| Reagent                             | Amount        | Final Conc. |
| ----------------------------------- | ------------- | ----------- |
| 3M Potassium Acetate stock (pH 7.5) | 10mL          | 30mM        |
| MnCl2•4H2O                          | 9.9 g         | 50mM        |
| RbCl2                               | 12 g          | 100mM       |
| CaCl2•2H2O                          | 1.5 g         | 10mM        |
| Glycerol                            | 150g or 120ml | 15% wt/vol  |

1. 비커에 magnetic stirrer와 DW 650mL을 넣은 후, 3M potassium acetate 10mL, MnCl2•4H2O 9.9g, RbCl2 12g, CaCl2•2H2O 1.5g, Glycerol 120mL을 순서대로 녹인다.&#x20;
2. 0.2M acetic acid를 이용해서 조심스럽게 pH 5.8로 맞춘다. pH가 너무 낮아지지 않도록 주의한다.
3. DW를 추가하면서 최종 부피를 1000mL에 맞춘다.
4. 0.2um membrane의 bottle-top filter로 거른 후, 4℃에 보관한다.

#### RF-2 buffer 만들기 (200mL 기준)

| Reagent         | Amount      | Final Conc. |
| --------------- | ----------- | ----------- |
| RbCl2           | 240mg       | 10mM        |
| CaCl2•2H2O      | 2.2g        | 75mM        |
| 0.5M MOPS stock | 4mL         | 10mM        |
| Glycerol        | 30g or 24mL | 15% wt/vol  |

1. 비커에 magnetic stirrer와 DW 150mL을 넣은 후, RbCl2 240mg, CaCl2•2H2O 2.2g, 0.5M MOPS stock 4mL, Glycerol 24mL을 순서대로 녹인다.
2. 0.1N NaOH (=0.1M NaOH)를 이용해서 pH 6.8로 조심스럽게 맞춘다. pH가 너무 높아지지 않도록 주의한다.&#x20;
3. DW를 추가하면서 최종 부피를 200 mL로 맞춘다.
4. 0.2um membrane의 bottle-top filter로 거른 후, 4℃에 보관한다.

{% hint style="info" %}
200ml RF-2 buffer 제작 기준, DW 150ml에 chemical 위에 적힌 비율대로 넣고, NaOH (0.2M) 기준 10ml을 넣어서 pH 6.8을 맞춰주었다. 이후 DW 40ml을 추가하여 최종 200ml을 맞춰주었다.
{% endhint %}

{% hint style="info" %}
NaOH가 없다면 KOH 등으로 대신할 수 있다. 하지만 실험실에 NaOH 같은 기본적인 용액은 대부분 보유하고 있다.
{% endhint %}

### 3. _E.Coli_ competent cell 제작

{% hint style="info" %}
Culture 과정이 필요하기 때문에 3일 과정으로 진행된다.
{% endhint %}

#### 1일차











[^1]: 양이 너무 많으면sterilization pouch 사용

[^2]: 3-(N-morpholino)propanesulfonic acid

[^3]: glacial Acetic acid
