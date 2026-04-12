# NekoEmpireGame için 3D Asset Prompt Paketi (TR)

Aşağıdaki promptlar; **karakter, yatak, mutfak, yemek, kapı, TV, oda ve bahçe** dahil tüm sahneyi 3D üretmek için hazırlandı.

## 1) Stil ve Teknik Standart (Tüm Promptlara Eklenecek)

```text
Stylized semi-realistic 3D game asset, clean topology, quad-dominant mesh, game-ready, PBR textures, UV unwrapped, no overlapping UV islands, consistent texel density, optimized for mobile, soft rounded edges, readable silhouette, no text watermark, no logo.
Scale: real-world centimeters.
Engine target: Unity URP.
Texture sets: BaseColor, Roughness, Metallic, Normal, AO.
Poly budget: low-mid poly.
```

---

## 2) Ana Karakter (Neko) – 3D Model Prompt

```text
Create a stylized chibi cat-humanoid character for a cozy life simulation game.
Height 120 cm, big head small body proportions, friendly face, cat ears, short tail, neutral A-pose.
Clothing: white top with small red badge, light blue skirt/shorts, white socks, simple shoes.
Face: large eyes, small mouth, soft blush, cute and readable from top-down 3/4 camera.
Rig-ready mesh with clean edge loops for shoulders, elbows, hips, knees.
Include blendshapes for blink, smile, sad, surprised.
Material style: matte pastel, slight roughness variation.
Deliver: FBX + textures, separate material IDs (skin, hair/fur, clothes, accessories).
```

### Karakter Animasyon Promptu

```text
Generate animation set for the chibi cat-humanoid character:
Idle (breathing), Walk loop, Run loop, Sit on chair, Sit on bench, Sleep on bed, Cook at kitchen counter, Wash hands at sink, Watch TV standing, Eating animation.
All loops seamless, root motion disabled, in-place animations, 30 FPS.
Export each clip separately and as one master FBX with named clips.
```

---

## 3) Oda (Main Room) – 3D Environment Prompt

```text
Create a cozy small apartment interior room for a life-sim game.
Layout: one wall with two interior doors (WC and OUT), one window, bed corner, kitchen counter + fridge, TV stand, rug, small table, armchair, potted plant.
Style: warm wood + soft neutral walls, realistic proportions, no exaggerated cartoon distortion.
Use modular pieces aligned to grid.
Lighting-friendly materials for day/night cycle.
No road, no car, no city traffic elements.
```

---

## 4) Yatak – 3D Prop Prompt

```text
Create a single bed game-ready 3D prop.
Dimensions: 200x100x90 cm (LxWxH with headboard).
Components: wooden frame, mattress, pillow, folded blanket.
Style: cozy semi-realistic, rounded corners, soft fabric folds, clean UVs.
Poly target: 2k-4k tris.
Texture size: 1024 or 2048.
```

---

## 5) Mutfak + Buzdolabı + Tezgah + Evye Prompt

```text
Create a compact kitchen module with fridge, lower cabinet, countertop, sink, and simple hood.
Realistic proportions for a small apartment.
Fridge door seam and handle details, sink basin depth visible, subtle edge wear.
Game-ready low-mid poly, PBR textures, separate meshes for interactive parts.
Include optional VFX anchors: steam_anchor, sink_water_anchor.
```

---

## 6) Yemek/Obje Seti Promptu

```text
Create a stylized food prop pack for life-sim cooking interactions.
Include: plate, bowl, sandwich, rice plate, soup bowl, cutlery, cup.
Readable from distance, slightly exaggerated silhouettes.
Low poly with clean UVs and one shared atlas texture.
Provide clean and dirty plate variants.
```

---

## 7) Kapılar (WC/OUT) – 3D Prop Prompt

```text
Create two interior door variants with frame and handle.
Door A label: WC, Door B label: OUT (label as separate editable mesh).
Apartment style, white painted surface, wooden frame.
Pivot correctly placed on hinge side for open/close animation.
Game-ready and modular.
```

---

## 8) TV + TV Sehpası Prompt

```text
Create a compact CRT-like modern hybrid TV prop with a small stand cabinet.
Stylized cozy look, dark screen with slight glass reflection.
Separate emissive material for screen-on state.
Poly target: 1.5k-3k tris.
```

---

## 9) Bahçe Sahnesi Prompt (Ağaç/Çit/Çiçek)

```text
Create a small cozy garden area with grass ground, wooden fence, one stylized tree, and simple flowers.
No road, no crosswalk, no vehicles.
Tree should have balanced canopy volumes and natural trunk thickness.
Use modular fence segments and low-poly flower variations.
```

---

## 10) VFX Promptları (Yemek, Lavabo, Ortam)

### Yemek Buharı
```text
Create stylized steam VFX for cooking.
Soft white translucent particles, upward drift, looping 1-2 seconds.
Mobile-friendly particle count, URP compatible.
```

### Lavabo Su Efekti
```text
Create sink water VFX: short burst and loop versions.
Clear water material, small splash decals, low-cost particles.
```

### Gece Ambiyans
```text
Create subtle night ambient VFX for room and garden.
Low intensity cool-toned volumetric feel without heavy post-processing.
```

---

## 11) Tek Parça “Hepsini Üret” Master Prompt

```text
Build a complete stylized 3D cozy life-sim scene with one chibi cat-humanoid character and modular apartment + garden environment.
Include assets: character (rig-ready), bed, kitchen with fridge/sink, two doors (WC/OUT), TV stand, table, armchair, rug, plant, window, garden fence/tree/flowers.
No road and no cars.
Provide clean topology, PBR textures, UV unwrapped meshes, optimized for mobile Unity URP.
Character animation clips: idle, walk, sit, sleep, cook, wash, watch TV, eat.
Scene should be readable from side/3/4 perspective and maintain coherent scale.
Deliver organized folder structure with FBX, textures, materials, and prefabs.
```

---

## 12) Negatif Prompt (Kaliteyi Korumak İçin)

```text
Do not generate broken anatomy, distorted proportions, floating props, intersecting meshes, noisy topology, high-frequency texture artifacts, text watermark, logos, blurry textures, non-manifold geometry, or inconsistent scale.
```


---

## 13) Bedava/Ücretsiz Denenebilen Siteler (2026 Nisan kontrol)

> Not: Ücretsiz kredi/paket ve ticari lisans koşulları sık değişir; üretim öncesi pricing ve license sayfasını tekrar kontrol et.

- **Meshy** — Text/Image to 3D, ücretsiz planla başlangıç mümkün.
- **Tripo Studio** — Ücretsiz başlangıç planı + aylık kredi modeli.
- **Sloyd** — Ücretsiz planla template tabanlı 3D üretim/edit.

Öneri: İlk denemeleri ücretsiz planda yap, final üretimde lisans gereksinimine göre ücretli plana geç.

---

## 14) “Tek Prompt Ver, Anime Stil Olsun” Süper Prompt (Karakter + Oda + Eşyalar + Aksiyon)

Aşağıdaki promptu tek parça kullan:

```text
Create a complete anime-style cozy life-sim 3D scene for a mobile game (Unity URP), with one stylized chibi cat-humanoid character and a full apartment room + small garden module.

ART DIRECTION:
- Anime style, clean cel-shaded look, soft pastel palette, readable silhouettes.
- Cozy, warm, cute, slightly semi-realistic proportions for furniture.
- No horror, no photoreal grime, no over-detailed noisy textures.

CHARACTER:
- Chibi cat-humanoid, 120 cm tall, large head, short body, cat ears and short tail.
- Outfit: white top with small red emblem, light blue skirt/shorts, white socks, simple shoes.
- Face: large anime eyes, subtle blush, friendly expression.
- Rig-ready topology with proper loops on shoulders/elbows/hips/knees.
- Include blendshapes: blink, smile, sad, surprised.

ROOM LAYOUT (MAIN ROOM):
- One interior wall with two doors labeled WC and OUT.
- One window with simple frame.
- Bed area, compact kitchen (counter + sink + fridge + hood), TV + stand, small table, armchair, rug, potted plant.
- Correct real-world scale and spacing (no floating, no intersections).

GARDEN MODULE:
- Grass ground, wooden fence, one stylized tree, simple flowers.
- No road, no crosswalk, no cars.

INTERACTION ASSETS:
- Food props set: plate, bowl, sandwich, rice plate, soup bowl, cup, cutlery.
- Plate states: clean and dirty variants.
- VFX anchors: cooking steam anchor, sink water anchor, ambient anchor.

ANIMATION CLIPS (in-place, loop-ready, 30 FPS):
- idle, walk, run, sit-chair, sit-bench, sleep-bed, cook-kitchen, wash-sink, watch-tv, eat.

TECHNICAL REQUIREMENTS:
- Game-ready low-mid poly, quad-dominant clean mesh.
- PBR texture workflow: BaseColor, Roughness, Metallic, Normal, AO.
- UV unwrapped, non-overlapping UV islands, consistent texel density.
- Optimized for mobile performance.
- Export: FBX + textures + materials + organized prefab-ready folder structure.

NEGATIVE CONSTRAINTS:
- No broken anatomy, no distorted limbs, no non-manifold geometry, no stretched UVs,
  no intersecting meshes, no floating props, no watermark/logo/text artifacts,
  no unreadable tiny details, no inconsistent scale.
```
