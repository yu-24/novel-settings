# ダンジョンシステム設計

## 1. ダンジョンの基本構造

- ダンジョンは **複数階層** で構成され、進むごとに難易度が上昇。
- 各階層には **モンスターエリア / 宝箱エリア / 罠エリア / 隠し部屋** などのゾーンが存在。
- **特定の階層ごとにボスモンスター** が配置されている。
- 階層ごとに環境が変化（例：炎の階層、氷の階層、闇の階層など）。

## 2. ダンジョンの探索方法

- **マップ機能**：

  - 主人公は **ダンジョンのマップを把握可能**（通常の探索者は地図を持ち帰らないと把握できない）。
  - **隠し扉や隠し通路** の位置も確認できる。

- **ギルドの役割**：

  - ギルドメンバーと連携しながら探索が可能。
  - 生産職がダンジョン内で採掘やアイテム採集を行える。

## 3. ダンジョンの敵モンスター

- **通常モンスター**：

  - 階層ごとに出現するモンスターの強さが変動。
  - 種族ごとに特徴があり、相性の良い職業で対処可能。

- **ボスモンスター**：

  - 一定階層ごとに登場し、**撃破で報酬アイテム** を獲得可能。
  - ボスの討伐条件を満たすことで**次の階層へ進む扉が解放** される。

- **レアモンスター・レアボス**：
  - 通常のモンスターよりも強力だが、**撃破すると特別なアイテムをドロップする可能性がある**。
  - 出現率が低く、遭遇には一定の条件を満たす必要がある場合もある。

## 4. ダンジョンの報酬とアイテム

- **レアアイテムの獲得**：
  - モンスター討伐や宝箱から **武器・防具・ポーション・特殊アイテム** を入手可能。
  - **ボス討伐報酬は特に強力な装備が含まれる（スキルブックはなし）**。
- **素材の採集・収集**：
  - 生産職が **鉱石・魔法素材・薬草などの資源を採集可能**。
  - 採集品は **鍛冶や錬金に使用できるため、探索のモチベーションになる**。

## 5. ダンジョンの危険要素

- **罠エリア**：

  - 毒・落とし穴・幻覚・モンスター召喚などの罠が仕掛けられている。
  - **索敵スキルが高いキャラがいると罠を事前に発見可能**。

- **脱出方法**：

  - **非常口** となる魔法陣が設置されており、危険時には撤退可能。
  - **ダンジョン奥に進むほど脱出が困難になる**（魔法陣の数が減少）。

---

このダンジョンシステムを基に、さらなる調整や探索バランスの最適化が可能！

