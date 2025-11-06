# Medi×3D  
2D X-Ray → 3D Mesh Reconstruction Pipeline (MiDaS + Trimesh)

Medi×3D is a lightweight and practical pipeline that converts standard 2D medical X-ray images into 3D mesh models.  
It avoids heavy platforms like Open3D (unless needed) and instead relies on MiDaS for depth estimation and trimesh for final mesh generation.

---

## 🚀 Features
- ✅ 2D X-ray → Depth map using MiDaS  
- ✅ Depth → Point cloud conversion  
- ✅ Mesh reconstruction using trimesh  
- ✅ Mesh cleanup (smoothing, decimation, watertight fixes)  
- ✅ Streamlit UI for real-time inference  
- ✅ Supports Python **3.10–3.13**

---

## 🔧 Installation

```bash
git clone https://github.com/<yourusername>/Medix3D.git
cd Medix3D
pip install -r requirements.txt
