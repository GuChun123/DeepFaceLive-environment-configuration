# DeepFaceLive-environment-configuration
Setting Up the DeepFaceLive (Face-Swapping) Environment with Conda

conda命令
conda env create -f .\environment.yml -p .\deepfacelive_virtual_environment

项目启动命令（提前在DeepFaceLive项目内新建userdata-dir文件夹
python main.py run DeepFaceLive --userdata-dir .
