```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/MasutaniLab/pymoveit2/noble-rolling-amd64/ ./" | sudo tee /etc/apt/sources.list.d/MasutaniLab_pymoveit2-noble-rolling-amd64.list
echo "yaml https://github.com/MasutaniLab/pymoveit2/raw/noble-rolling-amd64/local.yaml rolling" | sudo tee /etc/ros/rosdep/sources.list.d/1-MasutaniLab_pymoveit2-noble-rolling-amd64.list
```
