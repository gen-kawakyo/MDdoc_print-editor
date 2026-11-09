# 2025年度 神奈川県公立高校入試 数学 問3(ア)
**出典・単元**: 神奈川県公立高等学校入学者選抜学力検査問題（2025年） ｜ 円・相似の証明・三平方の定理・線分比と面積

---

### 【問題】

<div class="grid-2">
  <div class="col-box">
    <h4></h4>
    右の図 1 のように，線分 $AB$ を直径とする円 $O$ の周上に，2 点 $A, B$ とは異なる点 $C$ を，$AC > BC$ となるようにとる。
また，円 $O$ の周上に点 $D$ を，$angle CAD$ が鈍角となるようにとり，線分 $AB$ と線分 $CD$ との交点を $E$ とする。
さらに，線分 $CB$ の延長上に点 $F$ を，$CF = DF$ となるようにとり，線分 $DF$ と円 $O$ との交点を $G$，線分 $AG$ と線分 $BD$ との交点を $H$ とする。
  </div>
  <div class="col-box">
    <h4></h4>
    <svg viewBox="0 0 360 240" class="w-full max-w-[360px] mx-auto my-3 border border-slate-200 bg-slate-50/50 rounded-xl shadow-2xs"><circle cx="180" cy="120" r="74" fill="none" stroke="#64748b" stroke-width="1.5" stroke-dasharray="3 3"/><line x1="106" y1="120" x2="254" y2="120" stroke="#1e293b" stroke-width="1.5" /><line x1="190" y1="46" x2="153" y2="189" stroke="#1e293b" stroke-width="1.5" /><line x1="106" y1="120" x2="190" y2="46" stroke="#1e293b" stroke-width="1.5" /><line x1="106" y1="120" x2="153" y2="189" stroke="#1e293b" stroke-width="1.5" /><line x1="106" y1="120" x2="238" y2="165" stroke="#1e293b" stroke-width="1.5" /><line x1="254" y1="120" x2="153" y2="189" stroke="#1e293b" stroke-width="1.5" /><line x1="190" y1="46" x2="254" y2="120" stroke="#1e293b" stroke-width="1.5" /><line x1="254" y1="120" x2="285" y2="156" stroke="#1e293b" stroke-width="1.5" /><line x1="153" y1="189" x2="285" y2="156" stroke="#1e293b" stroke-width="1.5" /><line x1="190" y1="46" x2="285" y2="156" stroke="#1e293b" stroke-width="1.5" /><line x1="254" y1="120" x2="238" y2="165" stroke="#1e293b" stroke-width="1.5" /><circle cx="180" cy="120" r="3" fill="#2563eb" /><text x="186" y="116" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">O</text><circle cx="106" cy="120" r="3" fill="#2563eb" /><text x="112" y="116" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">A</text><circle cx="254" cy="120" r="3" fill="#2563eb" /><text x="260" y="116" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">B</text><circle cx="190" cy="46" r="3" fill="#2563eb" /><text x="196" y="42" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">C</text><circle cx="153" cy="189" r="3" fill="#2563eb" /><text x="159" y="185" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">D</text><circle cx="164" cy="120" r="3" fill="#2563eb" /><text x="170" y="116" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">E</text><circle cx="285" cy="156" r="3" fill="#2563eb" /><text x="291" y="152" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">F</text><circle cx="238" cy="165" r="3" fill="#2563eb" /><text x="244" y="161" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">G</text><circle cx="198" cy="151" r="3" fill="#2563eb" /><text x="204" y="147" font-size="12" font-family="system-ui, sans-serif" font-weight="bold" fill="#0f172a">H</text></svg>
<p class="text-[11px] text-slate-500">
  </div>
</div>



<div class="col-box bg-white my-3 border border-slate-300 shadow-2xs">

### ［証明の展開］

［証明］ $\triangle ACE$ と $\triangle AGD$ において，

まず，$\stackrel{\frown}{AD}$ に対する円周角は等しいから，
$\angle ACD = \angle AGD$
よって，$\angle ACE = \angle AGD$ ……①

次に，$\stackrel{\frown}{BD}$ に対する円周角は等しいから，
$[ ⒜ ]$ ……②

また，$CF = DF$ より，$\triangle FCD$ は二等辺三角形であり，その 2 つの底角は等しいから，
$\angle FCD = \angle FDC$
よって，$\angle BCD = \angle CDG$ ……③

さらに，$\stackrel{\frown}{CG}$ に対する円周角は等しいから，
$[ ⒝ ]$ ……④

②，③，④より，
$\angle CAB = \angle CAG - \angle BAG = \angle BAD - \angle BAG$ ……⑤
$\angle GAD = \angle BAD - \angle BAG$ ……⑥

⑤，⑥より，$\angle CAB = \angle GAD$
よって，$\angle CAE = \angle GAD$ ……⑦

①，⑦より，2 組の角がそれぞれ等しいから，
$\triangle ACE \sim \triangle AGD$

</div>

<div class="callout callout-solution">
  <div class="callout-title">💡 標準解法：平行線の錯角・正三角形の特定と三平方の定理</div>

**ステップ 1：平行線 BG // CD と正三角形の特定** <span class="bg-emerald-100 text-emerald-800 text-xs px-2 py-0.5 rounded font-bold mr-1">🏷️ 円周角と錯角</span> <span class="bg-emerald-100 text-emerald-800 text-xs px-2 py-0.5 rounded font-bold mr-1">🏷️ 平行線と相似比</span>

$BG // CD$ を導くことで、$\triangle FBG \sim \triangle FCD$ より $FB = 2 \text{ cm}$ が求まり、$\triangle FBG, \triangle FCD$ は共に正三角形であることがわかります。

> **思考ロジック**: $\stackrel{\frown}{BC}$ の円周角より $\angle CAB = \angle CDB$、$\stackrel{\frown}{DG}$ の円周角より $\angle GAD = \angle DBG$。したがって $\angle CDB = \angle DBG$（錯角が等しい）となり $BG // CD$ が成立します。

**［計算過程］**:
- $BG // CD$ より $\triangle FBG \sim \triangle FCD$
- 相似比 $BG : CD = FG : FD = 2 : (2 + DG)$
- $CF = DF$ かつ $CB = 4$ より $4 + FB = 2 + DG$
- $FB = FG = 2 \text{ cm}, \quad DG = BC = 4 \text{ cm}, \quad CD = CF = DF = 6 \text{ cm}$

</div>
