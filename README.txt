From now on, after making website changes:

cd /var/www/wolfworks.tech

git status
git add .
git commit -m "Added known good PCB project page"
git push




See what changed:

git status
git diff

See commit history:

git log --oneline

Pull changes:

git pull


[4.0K]  .
├── [ 19K]  about.html
├── [1.3K]  contact.html
├── [4.0K]  css
│   └── [ 10K]  style.css
├── [4.0K]  downloads
│   └── [136K]  Wolfs_resume.pdf
├── [691K]  favicon.png
├── [4.0K]  images
│   
├── [4.1K]  index.html
├── [4.0K]  projects
│   ├── [7.4K]  arcade-control-deck.html
│   ├── [7.4K]  arcade-control-deck-interface.html
│   ├── [1.6K]  autonomous-lidar-terrain-mapping-drone.html
│   ├── [9.5K]  bench-power-supply-repair-program.html
│   ├── [9.8K]  bnp.html
│   ├── [6.6K]  brain-box-diagnostic-system.html
│   ├── [1.5K]  csharp-circuit-analyzer.html
│   ├── [1.5K]  custom-xbox-macro-controller.html
│   ├── [1.5K]  enterprise-unifi-network-deployments.html
│   ├── [6.7K]  fpga-tic-tac-toe.html
│   ├── [1.5K]  g-c-u.html
│   ├── [7.5K]  gcu.html
│   ├── [1.6K]  l-a-m-p.html
│   ├── [7.6K]  lamp.html
│   ├── [6.9K]  lidar-drone.html
│   ├── [1.4K]  msp432-pong-game.html
│   ├── [1.4K]  nas-and-media-server-builds.html
│   ├── [9.3K]  nixie-tube-clock.html
│   ├── [1.6K]  p-a-c-e.html
│   ├── [6.3K]  pace.html
│   ├── [1.5K]  pneumatic-briefcase.html
│   ├── [1.5K]  precision-ac-to-dc-power-supply.html
│   └── [7.3K]  precision-known-good-pcb-set.html
├── [ 11K]  projects.html
├── [2.2K]  resources.html
├── [2.0K]  shop.html
└── [1.5K]  wisdom.html
