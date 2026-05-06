# SID Calculator：公式與步驟
## Step 1. 輸入需要的數值
- pH
- PaCO2, mmHg
- Na, mmol/L
- K, mmol/L
- Cl, mmol/L
- Lactate, mmol/L
- Ionized Ca, mmol/L
- Mg, mmol/L
- Albumin, g/dL
- Phosphate, mmol/L
## Step 2. 計算 bicarbonate
公式：
HCO3 = 0.0301 × PaCO2 × 10^(pH - 6.1)
解釋：
這是 Henderson-Hasselbalch equation 推回來的 HCO3。
用途是計算 SIDe。
## Step 3. 計算 SIDa
公式：
SIDa = Na + K + 2×iCa + 2×Mg - Cl - Lactate
解釋：
SIDa 代表「實際測得到的 strong ions 差值」。
Na、K、Ca、Mg 是 strong cations。
Cl、lactate 是 strong anions。
Ca 和 Mg 是二價陽離子，所以要乘以 2。
臨床判讀：
SIDa 下降 → strong ion acidosis
常見原因：hyperchloremia、lactic acidosis
SIDa 上升 → strong ion alkalosis
常見原因：hypochloremia、volume contraction、diuretics
## Step 4. 計算 albumin charge
公式：
Albumin charge = Albumin(g/L) × (0.123 × pH - 0.631)
注意：
如果 albumin 輸入是 g/dL，要先乘以 10 變成 g/L。
解釋：
Albumin 是 weak acid，會帶負電。
低白蛋白會減少 weak acid effect，造成 alkalinizing effect。
## Step 5. 計算 phosphate charge
公式：
Phosphate charge = Phosphate(mmol/L) × (0.309 × pH - 0.469)
解釋：
Phosphate 也是 weak acid，尤其在 renal failure 時可能增加。
Phosphate 上升會增加 acidifying effect。
## Step 6. 計算 SIDe
公式：
SIDe = HCO3 + Albumin charge + Phosphate charge
解釋：
SIDe 代表「由 bicarbonate、albumin、phosphate 解釋掉的 effective strong ion difference」。
它反映血漿中 weak acids 和 bicarbonate 所對應的電荷平衡。
## Step 7. 計算 SIG
公式：
SIG = SIDa - SIDe
解釋：
SIG = strong ion gap。
代表未被 Na/K/Ca/Mg/Cl/lactate/HCO3/albumin/phosphate 解釋的 unmeasured ions。
臨床判讀：
SIG 正常約 0–5 mEq/L。
SIG 上升 → unmeasured anions 增加。
常見原因：
- uremia
- ketoacidosis
- toxins，例如 methanol、ethylene glycol、salicylate
- sepsis-related unmeasured anions
## Step 8. 統整判讀
先看 pH：
pH < 7.35 → acidemia
pH > 7.45 → alkalemia
pH 7.35–7.45 → pH roughly normal，但仍可能有 mixed disorder
再看 SIDa：
SIDa < 38 → strong ion acidosis
SIDa 38–42 → roughly normal
SIDa > 42 → strong ion alkalosis
再看 SIG：
SIG > 5 → unmeasured anion acidosis
SIG ≤ 5 → 不支持明顯 unmeasured anions
## 一句話記憶
Low SIDa = chloride/lactate-driven acidosis
High SIG = hidden anions
Low albumin = alkalinizing effect
High phosphate = acidifying effect
