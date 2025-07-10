
# Decision Tree Classification: Klasifikasi Tingkat Kesejahteraan

Proyek ini membahas implementasi dan visualisasi algoritma Decision Tree menggunakan dua pendekatan:
1. **ID3** (berbasis Entropy)
2. **CART** (berbasis Gini Index)

Dengan dataset fiktif mengenai status kesejahteraan penduduk berdasarkan variabel seperti pendapatan, bantuan sosial, dan kepesertaan BPJS.

---

## Tujuan Proyek

- Membangun pohon keputusan untuk mengklasifikasikan tingkat kesejahteraan
- Membandingkan pendekatan ID3 dan CART
- Menghitung information gain (entropy dan gini)
- Menampilkan visualisasi pohon keputusan
- Menghasilkan confusion matrix untuk evaluasi model

---

## Dataset

Berisi 13 data observasi dengan variabel:
- **Pendapatan** (`Rendah`, `Sedang`, `Tinggi`)
- **Penerima Raskin**
- **Penerima BLT**
- **Peserta BPJS**
- **Kesejahteraan** (target: `Sejahtera`, `Tidak Sejahtera`)
Sumber: Damanik, S. F., Wanto, A., & Gunawan, I. (2022). Penerapan Algoritma Decision Tree C4.5 untuk Klasifikasi Tingkat Kesejahteraan Keluarga pada Desa Tiga Dolok. Jurnal Krisnadana, 1(2), 21–32. https://doi.org/10.58982/krisnadana.v1i2.108

---

## Tools & Library

- `pandas`, `numpy`, `collections`
- `scikit-learn`: `DecisionTreeClassifier`, `LabelEncoder`, `metrics`
- `matplotlib.pyplot`: visualisasi pohon CART
- `graphviz`: visualisasi ID3 manual

---

## Hasil & Visualisasi

- Pohon ID3 divisualisasikan dengan `graphviz`
- Pohon CART divisualisasikan dengan `plot_tree` dari scikit-learn
- Confusion matrix digunakan untuk mengevaluasi hasil prediksi model

---

## Struktur File

```
📂 decision-tree-classification/
├── 📄 README.md
├── 📄 decision_tree_classification.ipynb
├── 📄 id3_visualization.png  
├── 📄 cart_visualization.png     
└── 📄 confusion_matrix.png 
```

---

## Akurasi & Evaluasi

Confusion matrix menunjukkan akurasi tinggi karena dataset kecil dan model dilatih & diuji pada data yang sama.

---

## 📫 Contact

Saskia – [https://linkedin.com/in/saskiaiqlimab]  
Email: [saskiabilhaq@gmail.com]  
Portofolio lainnya: [https://github.com/saskiaab]
