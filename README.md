# Cara Install Tools
pkg update && pkg upgrade   
pkg install git python   
pip install cython   
rm -rf Trial-Prem   
git clone https://github.com/NaldiFanxmoody/Trial-Prem

# Install Bahan Tools
cd Trial-Prem   
git pull   
pip install -r requirements.txt   

# Cara Menjalankan Tools
python run_gacor.py
