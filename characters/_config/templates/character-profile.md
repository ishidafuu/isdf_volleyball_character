---
# Character Profile Template
version: 1.0.0  # テンプレートのバージョン番号
last_updated: YYYY-MM-DD  # 最終更新日
status: draft|review|final  # ドキュメントの状態（下書き/レビュー中/完成）

# Basic Information
character_id: XX-00  # 学校コード(2文字) + 通し番号(2桁)
name:
  given: ""  # 名前（例：太郎）
  family: ""  # 苗字（例：山田）
  full: ""   # フルネーム（例：山田太郎）
  reading: "" # フリガナ（例：ヤマダタロウ）

# Core Stats
year: 1|2|3  # 学年（1年/2年/3年）
position: WSP|MB|S|L|OPP  # ポジション（ウィングスパイカー/ミドルブロッカー/セッター/リベロ/オポジット）
height: 000  # 身長（センチメートル）
team: ""     # 所属チーム名
previous_team: ""  # 前所属中学校名
previous_club: ""  # 前所属部活動名

# Abilities (S|A|B|C)
abilities:
  attack: ""    # 攻撃力（S：卓越/A：優秀/B：平均的/C：要改善）
  receive: ""   # レシーブ（S：卓越/A：優秀/B：平均的/C：要改善）
  serve: ""     # サーブ（S：卓越/A：優秀/B：平均的/C：要改善）
  block: ""     # ブロック（S：卓越/A：優秀/B：平均的/C：要改善）
  stamina: ""   # スタミナ（S：卓越/A：優秀/B：平均的/C：要改善）
  technique: "" # 技術（S：卓越/A：優秀/B：平均的/C：要改善）

# Personality Axes
personality:
  energy_axis:
    core_energy: "internal|external|balanced"  # エネルギーの源泉（内的：個人の内面から力を得る/外的：環境との相互作用で活性化/バランス型：状況に応じて切り替え可能）
    energy_expression: "active|passive|selective"  # エネルギーの発露（能動的：自ら行動を起こす/受動的：状況を見守る/選択的：TPOに応じた使い分け）
    influence_type: "direct|indirect|catalytic"  # 影響の方向性（直接的：明確な指示や行動/間接的：環境づくりや雰囲気作り/触媒的：他者の変化を促進）
    influence_scope: "individual|group|adaptive"  # 影響の範囲（個人：一対一の関係性重視/集団：チーム全体への働きかけ/適応的：状況に応じた切り替え）

  motivation_axis:
    internal_motivation: 
      primary: "self_improvement|curiosity|competitive|exploratory"  # 主要な内的動機（自己向上：可能性の追求/探究心：純粋な興味/競争心：他者との競い合い/好奇心：新しい可能性）
      secondary: ""  # 副次的な内的動機（主要な動機を補完する二次的な動機）
    external_motivation:
      primary: "team_contribution|recognition|duty"  # 主要な外的動機（チーム貢献：集団への貢献/承認欲求：他者からの評価/使命感：役割遂行への責任）
      secondary: ""  # 副次的な外的動機（主要な動機を補完する二次的な動機）
    behavioral_approach: "innovative|challenging|conservative|planned"  # 行動アプローチ（革新的：新しい方法の開発/挑戦的：困難への積極的取り組み/保守的：実績ある方法重視/計画的：段階的なアプローチ）
    interpersonal_style: "cooperative|harmonious|competitive|independent"  # 対人関係スタイル（協力的：チームワーク重視/調和的：バランス重視/競争的：結果重視/独立的：自律的判断）

  information_axis:
    stress_response:
      cognitive: "analytical|intuitive"  # ストレス認知パターン（分析型：論理的に分解して理解/感覚型：直感的な状況把握）
      processing: "expressive|overcoming|avoidant|accepting"  # ストレス処理方法（発散型：外部に表出/克服型：直接対峙/回避型：距離を置く/受容型：状況を受け入れる）
      coping: "diversionary|meditative|supportive|social"  # ストレス対処戦略（転換型：活動の切り替え/瞑想型：内的な整理/支援型：他者との共有/社交型：交流による解消）
    learning_style:
      input: "experiential|observational|theoretical"  # 学習情報の入力方式（体験学習：実践重視/観察学習：モデリング重視/理論学習：概念理解重視）
      processing: "systematic|trial_and_error|integrative"  # 学習情報の処理方式（系統的：順序立てた学習/試行錯誤：実験的な学習/統合的：複数の視点の統合）
      development: "imitative|innovative|conservative"  # 学習成果の発展方式（模倣発展：既存モデルの応用/革新的：新規の方法開発/保守的：確実な定着重視）

  expression_axis:
    basic_stance:
      openness: "open|restrained|selective"  # 表現の開放度（開放的：自由な感情表出/抑制的：制御された表出/選択的：状況に応じた使い分け）
      method: "direct|indirect|symbolic"  # 表現方法の特徴（直接的：率直な意思伝達/間接的：遠回しな伝達/象徴的：メタファーの使用）
    style:
      interpersonal: "instructive|diplomatic|exemplary"  # 対人関係での表現スタイル（指導的：教え導く姿勢/外交的：調整役としての機能/模範的：行動による示唆）
      situational: "observant|adaptive|creative"  # 状況対応での表現スタイル（観察的：状況把握重視/適応的：柔軟な対応/創造的：新しい表現方法の開発）

# Related files
related_files:  # 関連する文書やリソースファイルへのパス（複数指定可）
  - path/to/related/file1.md  # 関連設定文書（例：詳細な性格設定、成長履歴）
  - path/to/related/file2.md  # 関連リソース（例：イラスト設定、動作参考資料）
---

# {character_name}（{character_name_reading}）

## 基本情報
- ID: {character_id}
- 学年：{year}年
- ポジション：{position}
- 身長：{height}cm
- 所属：{team}
- 出身：{previous_team}（{previous_club}）

## 能力値
- 攻撃力：{abilities.attack}
- レシーブ：{abilities.receive}
- サーブ：{abilities.serve}
- ブロック：{abilities.block}
- スタミナ：{abilities.stamina}
- テクニック：{abilities.technique}

## 性格・特徴
### パーソナリティ4軸分析
#### 1. エネルギーの方向性
- コアエネルギー：
- エネルギーの発露：
- 影響力の特徴：
- 影響範囲：

#### 2. 行動の原動力
- 主な内的動機：
- 主な外的動機：
- 行動アプローチ：
- 対人関係スタイル：

#### 3. 情報処理特性
- ストレス対処：
  - 認知傾向：
  - 処理方法：
  - 対処方法：
- 学習スタイル：
  - 入力方式：
  - 処理方式：
  - 発展方式：

#### 4. 表現様式
- 基本姿勢：
  - 開放度：
  - 表現方法：
- スタイル：
  - 対人関係：
  - 状況対応：

### 性格
[性格の詳細な説明]

### 特徴的な要素
[特徴的な要素の説明]

## 来歴
### 中学時代
[中学時代の詳細]

### 高校での成長
[高校でのエピソード]

## キャリア
[主な実績や経験]

## 人間関係
### 家族関係
[家族との関係]

### チーム内
[チームメイトとの関係]

### ライバル
[ライバルとの関係]

## 特記事項
[その他の重要な情報]
