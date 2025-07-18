```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/MasutaniLab/pymoveit2/jammy-humble-amd64/ ./" | sudo tee /etc/apt/sources.list.d/MasutaniLab_pymoveit2-jammy-humble-amd64.list
echo "yaml https://github.com/MasutaniLab/pymoveit2/raw/jammy-humble-amd64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-MasutaniLab_pymoveit2-jammy-humble-amd64.list
```
