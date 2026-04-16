ZCLP Confirmed Results
Manager: Cloak | Last updated: 2026-04-16
Rule: Additions to this file require Cloak's approval.
Mathematically Confirmed (Proven)
Core Constraint
コード
Proof structure:
Variation w.r.t. λ → ΣΨᵢ = 0 emerges as a constraint
Sum of equations of motion for all modes → λ is determined automatically
λ = -(1/n) ΣV'(Ψᵢ)
Center of mass of the field system is fixed → ΣΨᵢ(t) = 0 holds at all times
Lagrangian
コード
Equation of Motion (per mode)
コード
The "mean-gradient subtraction" term is the physical core of ZCLP.
This structure does not appear in standard scalar field theory.
Degrees of Freedom
コード
Potential (confirmed)
コード
Small-amplitude approximation: m² = Λ⁴/f², f = H₀⁻¹, Λ ≈ H₀, m ≈ H₀
Physically Confirmed (Demonstrated)
Result
Basis
w > -1
Phase-space measure-zero argument
wₐ < 0
Follows from damped oscillation
λ determined automatically
From sum of equations of motion
Log oscillation in w(z) emerges naturally
DE-dominated expansion: a(t) ∝ e^{H₀t} → t ∝ ln(1+z)
Interference term Ψ̇ᵢΨ̇ⱼ emerges naturally
Follows from ΣΨᵢ = 0
Relation Ω = 2π/ln α
From definition
Ω = π/2 when ln α ≈ 4
Identity
Structure formation condition: η ≥ 4, z_crit ≈ 1.13
From dimensionless boundary definition Ξ (2026-04-16)
Predicted w(z) Curve (confirmed form)
コード
A ≈ 0.2 (from n ≈ 25 modes)
Ω ≈ π/2 (Ω_space) or 2π/3 (Ω_mass)
Which Ω is the true value is not yet determined → see ZCLP_hypotheses.md
Amplitude Hierarchy (confirmed)
Symbol
Value
Origin
A₀ ≈ 1
Initial amplitude
Normalization of V(Ψ) (confirmed 2026-04-13)
A_pred = 0.2
Predicted amplitude
Statistical variance of n ≈ 25 modes under ΣΨᵢ = 0 constraint
A_fit = 0.06
Fitted value
Observational fit — mechanism unknown, unresolved
Derivation structure: A ≈ A₀/√n
Note: requires phase-randomness assumption and equal-amplitude assumption → managed as conditional values in hypotheses.md
Falsification Conditions (defined before data)
Test ①: Periodicity in log-k space
Period not detected in SDSS/DESI → rejected
Period detected but equally explainable by ΛCDM → rejected
Period values inconsistent across multiple datasets → rejected
Test ②: Scale hierarchy ratio
Observed ratio deviates from α ≈ 55 by more than 2σ → rejected
Hierarchy peaks statistically indistinguishable from random distribution → rejected
Test ③: w(z) curve
No significant difference from ΛCDM in DESI → rejected
Ω matches neither Ω_space nor Ω_mass → rejected
Amplitude diverges at high z; fit clearly worse than ΛCDM → rejected
Significance Thresholds (fixed, not to be changed after data)
Stage
Threshold
Exploration
2σ
Publication / external presentation
3σ (required)
These thresholds are not to be revised after data collection.

ZCLP 確定事項
管理：クロ（Cloak）｜更新：2025-04-09深夜統合版
ルール：このファイルへの追加はクロの承認が必要
数学的確定（証明済み）
基本拘束
ΣΨᵢ(t) = 0　（任意のtで成立・初期条件ではなく運動方程式）
証明構造：
λの変分 → ΣΨᵢ = 0 が拘束として出る
各モードの運動方程式の和 → λが自動決定
λ = -(1/n) ΣV'(Ψᵢ)
全体の重心が固定される → ΣΨᵢ(t) = 0 が常に保たれる
ラグランジアン
L = Σᵢ(½Ψ̇ᵢ² - V(Ψᵢ)) + λΣᵢΨᵢ
運動方程式（各モード）
Ψ̈ᵢ + 3HΨ̇ᵢ + V'(Ψᵢ) - (1/n)ΣV'(Ψⱼ) = 0
「平均勾配 subtraction」がある形。これがZCLPの物理的本体。
自由度
dof = n - 1
周期ポテンシャル（確定）
V(Ψ) = Λ⁴[1 - cos(Ψ/f)]
小振幅近似：m² = Λ⁴/f²、f = H₀⁻¹、Λ ≈ H₀、m ≈ H₀
物理的確定（論証済み）
結論
根拠
w > -1
相空間測度ゼロ論証
wₐ < 0
減衰振動から
λ自動決定
運動方程式の和から
ログ振動は自然に出る
DE支配下 a(t) ∝ e^{H₀t} → t ∝ ln(1+z)
干渉項 Ψ̇ᵢΨ̇ⱼ は自然に出る
ΣΨᵢ = 0 から
Ω = 2π/lnα の関係式
定義から
lnα ≈ 4 のとき Ω = π/2
恒等式
予測曲線（確定式）
w(z) ≈ -1 + A(1+z)^{3/2} cos[Ω ln(1+z)]

A ≈ 0.2（n≈25から）
Ω ≈ π/2（Ω_space）〜 2π/3（Ω_mass）※どちらが真のΩかは未確定
反証条件（先に定義）
検証①：log-k空間の周期振動
周期が検出されない → 棄却
周期が検出されてもΛCDMで同等説明可能 → 棄却
SDSS・DESIで周期値が不一致 → 棄却
検証②：スケール階層比
実測スケール比がαから2σ以上ずれる → 棄却
階層ピークがランダム分布と統計的に区別できない → 棄却
検証③：w(z)曲線
DESIでΛCDMと有意差が出ない → 棄却
Ωの値がΩ_spaceにもΩ_massにも一致しない → 棄却
高zで振幅発散、ΛCDMより明らかに悪いフィット → 棄却
有意水準（確定・変更不可）
探索段階：2σ
論文投稿・外部発表：3σ必須
この基準はデータ取得後に変更しない

振幅の階層構造（確定）
A₀ ≈ 1：V(Ψ)の正規化から出る初期振幅（2026-04-13確認済み）
A_pred = 0.2：ΣΨᵢ=0拘束・n≈25モードの統計分散から導出
              導出構造：A ≈ A₀/√n
              ※位相ランダム仮定・等振幅仮定を要する条件付き値
              → hypotheses.md管理
A_fit = 0.06：実測フィッティング値、未解決継続
