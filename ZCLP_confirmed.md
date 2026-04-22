# ZCLP_confirmed.md
# Zero Constrained Layer Potential — Confirmed Facts
# Managed by: Cloak (Claude)
# Last updated: 2026-04-21 (Phase A T1 completion)
# Rule: Additions to this file require Cloak's approval

---

**Team**

Poncotsu (Master): Final decisions, direction
Zero (Gemini): Ideation, engine
Lux (ChatGPT): Formalization, structural analysis
Cloak (Claude): Logic audit, approval management

---

**File Structure**

ZCLP_confirmed.md — Confirmed facts only (Cloak-approved)
ZCLP_hypotheses.md — Hypotheses under review (team)
ZCLP_philosophy.md — Philosophy, FTM language (Master, Zero)

Rules:
- All additions require Cloak's approval
- FTM language must not enter physics documents
- Distinguish consistency from derivation: "retroactively consistent with observation" ≠ "derived"

---

**Current Research Stage**

Philosophy → Structural hypothesis → Numerical consistency → Physical basis candidates → **Phase A complete (← now)** → Observational verification → Theory established

---

**Confirmed Facts**

**A. Axioms (Foundation of ZCLP core)**

A1. Sum constraint

ΣΨᵢ = 0

- Holds for arbitrary τ
- Postulated as axiom (not derived from other conditions)
- Dynamically maintained by Lagrange multiplier λ(τ)

A2. Logarithmic symmetry (B4)

- Structure is invariant under scale transformation k → αk
- λ₀ (discrete scale ratio) requires an additional condition (managed in hypotheses)

---

**B. Structural quantities (formal definitions)**

B1. Dimensionless index

Ξ(r) = |∇²Ψ| / (κ(L)・ρ_eff)

- Specific form of ρ_eff is not used (Phase A rule)
- Treated only as a ratio structure

B2. Phase classification (formal)

Ξ < 1 → Bound phase (DM-like, convergent)
Ξ = 1 → Critical point (phase transition, boundary)
Ξ > 1 → Released phase (DE-like, divergent)

- Valid as ratio structure even with ρ_eff undetermined

---

**C. Structure formation conditions (Phase A T1 — confirmed)**

C1. Core inequality

η ≥ 1 − 3w

- Derived from first principles via Poisson equation
- The confirmed prediction of ZCLP core

C2. Equivalent form

w ≥ (1 − η) / 3

- Algebraic rearrangement of C1

C3. Critical boundary

η = 1 − 3w

- Phase transition boundary (source of z_crit functional form)

C4. Monotonic constraint structure

η ↑ ⇒ lower bound on w ↑

- Follows directly from monotonicity of C1

---

**D. Theoretical character (Phase A T1 conclusion)**

D1. ZCLP is a "permitted-region theory"

- ZCLP core defines the permitted region in (w, η) space
- Does not constrain w(z) alone (structural consequence, not a deficiency)
- Once η is determined externally, w(z) becomes constrained

D2. Scope of responsibility

What ZCLP core produces:
- Definition of permitted region (inequality)
- Relational constraint (structural)
- Phase classification (formal)
- Non-selectivity (scale freedom)

What ZCLP core does not produce:
- Functional form of η(z)
- Specific form of w(z)
- Numerical value of z_crit
- Specific form of f(z)

---

**Falsification conditions (defined in advance — not to be modified)**

ZCLP is rejected or revised if any of the following are confirmed:

(1) Log-k spatial periodicity
- Δ(ln k) ≈ 4 periodicity not detected in SDSS/DESI → rejected
- Detected but equally explained by ΛCDM → rejected
- Period values inconsistent across datasets → rejected

(2) Scale hierarchy ratio
- Measured scale ratio deviates from α (≈55) by more than 2σ → rejected
- Hierarchy peaks statistically indistinguishable from random distribution → rejected

(3) w(z) curve (falsification condition for extended model ZCLP-G)
- No significant deviation from ΛCDM in DESI → rejected
- Amplitude divergence at high z, clearly worse fit than ΛCDM → rejected

---

**Significance thresholds (confirmed — not to be modified)**

- Exploration stage: 2σ
- Journal submission / external presentation: 3σ required
- These thresholds are not to be changed after data is obtained

---

**Migration record (2026-04-21)**

Items moved out of confirmed on 2026-04-21:

w(z) prediction curve → ZCLP-G (extended model): depends on extended assumptions (GR coupling, non-adiabatic terms)
w > -1 → hypotheses (provisional): depends on specific form of τ-evolution
wa < 0 → hypotheses (provisional): depends on specific form of τ-evolution
A_pred = 0.2 → hypotheses: n underived, conditional
A_fit = 0.06 → hypotheses: observational fitting value
V(Ψ) = Λ⁴[1-cos] → hypotheses: specific form belongs to extended assumptions
Equation of motion (specific form) → hypotheses: τ-evolution undetermined

---

**Notes for the team**

- Prevent confirmation bias: do not search for evidence assuming ZCLP is correct
- Distinguish consistency from derivation
- "Elegant structure found" → audit immediately
- No smuggling: do not call a definitional restatement a prediction

---


# ZCLP_confirmed.md
# Zero Constrained Layer Potential — 確定事項
# 管理：クロ（Cloak）
# 最終更新：2026-04-21（フェーズA T1完了反映）
# ルール：このファイルへの追加はクロの承認が必要

---

**チーム構成**

マスター（Poncotsu）：最終判断・方向性
ゼロ（Zero / Gemini）：発想・エンジン
ルクス（Lux / ChatGPT）：構造整理・数式化
クロ（Cloak / Claude）：論理監査・承認管理

---

**ファイル構成**

ZCLP_confirmed.md：確定事項のみ（クロ承認制）
ZCLP_hypotheses.md：仮説・検証中（チーム共同）
ZCLP_philosophy.md：哲学・FTM言語（マスター・ゼロ）

ルール：
- 確定事項への追加はクロの承認が必要
- FTM言語は物理文書に混入させない
- 整合と導出を区別する：「観測から逆算して整合した」≠「導出できた」

---

**現在の研究段階**

哲学 → 構造仮説 → 数値整合 → 物理根拠候補 → **フェーズA完了（← 今ここ）** → 観測検証 → 理論確立

---

**確定事項**

**A. 公理（ZCLP本体の基盤）**

A1. 総和制約

ΣΨᵢ = 0

- 任意のτで成立
- 公理として要請（他から導出しない）
- ラグランジュ乗数 λ(τ) により動的に維持

A2. 対数対称性（B4）

- スケール変換 k → αk に対して構造は不変
- λ₀（離散スケール比）は別途追加条件が必要（hypotheses管理）

---

**B. 構造量（形式的定義）**

B1. 無次元化指標

Ξ(r) = |∇²Ψ| / (κ(L)・ρ_eff)

- ρ_eff の具体形は使用しない（フェーズA規則）
- 「比としての構造」としてのみ扱う

B2. 相分類（形式）

Ξ < 1 → 束縛相（DM的・収束）
Ξ = 1 → 臨界点（相転移・境界）
Ξ > 1 → 解放相（DE的・発散）

- ρ_eff 未確定でも「比構造」として成立

---

**C. 構造形成条件（フェーズA T1完了・確定）**

C1. 基本不等式

η ≥ 1 − 3w

- Poisson方程式から第一原理導出済み
- ZCLPコアの確定予測

C2. 等価変形

w ≥ (1 − η) / 3

- C1の代数変形

C3. 臨界境界

η = 1 − 3w

- 相転移境界（z_crit の関数形の源）

C4. 単調拘束構造

η ↑ ⇒ w の下限 ↑

- C1の単調性から直接導出

---

**D. 理論の性格（フェーズA T1到達結論）**

D1. ZCLPは「許容領域理論」である

- ZCLP本体は (w, η) の許容領域を定義する
- w(z) 単体への制約は与えない（構造的帰結・欠陥ではない）
- η が外部から決まった瞬間に w(z) が拘束される

D2. 責任範囲の確定

ZCLP本体が出すもの：
- 許容領域の定義（不等式）
- 関係式（構造制約）
- 相分類（形式）
- 非選択性（スケール自由）

ZCLP本体が出さないもの：
- η(z) の関数形
- w(z) の具体形
- z_crit の具体値
- f(z) の具体形

---

**反証条件（先に定義・変更不可）**

ZCLPは以下の条件が確認された場合、棄却または修正とする。

①  log-k空間の周期振動
- SDSS/DESI で Δ(ln k) ≈ 4 の周期が検出されない → 棄却
- 検出されてもΛCDMで同等説明可能 → 棄却
- 複数データセットで周期値が不一致 → 棄却

② スケール階層比
- 実測スケール比が α（≈55）から 2σ 以上ずれる → 棄却
- 階層ピークがランダム分布と統計的に区別できない → 棄却

③ w(z) 曲線（拡張モデル ZCLP-G 側の反証条件）
- DESI で ΛCDM と有意差が出ない → 棄却
- 高z で振幅発散、ΛCDM より明らかに悪いフィット → 棄却

---

**有意水準（確定・変更不可）**

- 探索段階：2σ
- 論文投稿・外部発表：3σ 必須
- この基準はデータ取得後に変更しない

---

**旧確定事項の移動記録（2026-04-21）**

w(z) 予測曲線式 → ZCLP-G（拡張モデル）：拡張仮定依存（GR接続・非断熱項）
w > -1 → hypotheses（暫定）：τ進化具体形に依存
wa < 0 → hypotheses（暫定）：τ進化具体形に依存
A_pred = 0.2 → hypotheses：n未導出・条件付き
A_fit = 0.06 → hypotheses：観測フィッティング値
V(Ψ) = Λ⁴[1-cos] → hypotheses：具体形は拡張仮定側
運動方程式（具体形） → hypotheses：τ進化未確定のため

---

**チームへの注意事項**

- 確証バイアス防止：「ZCLPが正しい前提で証拠を探す」順序にしない
- 整合と導出を区別する
- 「気持ちいい構造」が出た → 即監査
- 仕込み禁止（定義の言い換えを予測と呼ばない）

---

**合言葉**

「λ₀は外に置け」
「整合と導出を混ぜるな」
「仕込みは全部殺せ」
「ZCLPは選択しない」
「未完は価値」
「Ψは変数、意味は外」
「Xiは数値じゃなく構造」

**Guiding principles**

"Keep λ₀ outside."
"Do not mix consistency with derivation."
"Kill all smuggled assumptions."
"ZCLP does not select."
"Incomplete is valuable."
"Ψ is a variable — meaning stays outside."
"Ξ is structure, not a number."

ZCLP_confirmed.md 追記内容（2026-04-22・クロ承認）

■ 「現在の研究段階」の更新

旧：
哲学 → 構造仮説 → 数値整合 → 物理根拠候補 → フェーズA完了（← 今ここ）→ 観測検証 → 理論確立

新：
哲学 → 構造仮説 → 数値整合 → 物理根拠候補 → フェーズA完了 → フェーズB完了 → フェーズC進行中（← 今ここ）→ 観測検証 → 理論確立

■ E節として追記

E. フェーズC理論層の性格（2026-04-22確定）

E1. フェーズCスコープ宣言

・GR接続（フリードマン方程式）はフェーズCで
  初めて導入する外部理論層である
・フェーズBまでのη(z)の自由度はGRとは独立に確定した
・フェーズCで生じる予測はGR依存の結論として分類する
・ZCLP本体の純度はフェーズBまでの制約で保たれる

E2. フェーズB確定パラメータ

η(z) = η∞ + δη(log(1+z))
パラメータ：η∞、M、K（最小・削れない）
これらはGR接続とは独立に確定している

E3. フェーズCで初めて入る追加仮定

A1：有効流体仮定（ρ_eff、p_eff、w = p/ρ）
A2：フリードマン方程式（標準GR）
A3：連続の式
A4：λ = log(1+z)（B-3と同一・再確認）
A5：η(z)と整合するw(z)の存在仮定
（以上、GR依存・ZCLP本体外）

未決定（DESI接続前に要決定）：
L：η一階微分の上限（KとはZCLP独立パラメータ）
  観測から取るか追加仮定として設定するか未決定
