- 👋 Hi, I’m @Zhangx819
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Zhangx819/Zhangx819 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
pip install copulas
conda install -c conda-forge copulas
from copulas.datasets import sample_trivariate_xyz

real_data = sample_trivariate_xyz()
real_data.head()
