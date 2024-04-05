# Lidar_ObjDet_Robustness
Quick Note about Workspace setup
# Run the pip after build conda environment
`pip install torch==1.10.0+cu113 torchvision==0.11.1+cu113 torchaudio==0.10.0+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html`
# Quick notes about potential conda error
1. Run the `python setup.py develop` after you update the environment
2. If facing 'THC' error, delete them one-by-one using vscode
3. If facing cpp_extension error, delete the error line
