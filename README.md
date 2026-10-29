# Sürü Laboratuvarı

Sürü zekâsını ve sürü robotiğini **oynayarak öğrenmek** için etkileşimli, Türkçe bir web sitesi.

Kuş sürüleri, parçacık sürüsü (PSO), karıncalar, bakteriler, robot sürüleri, lidersiz anlaşma ve görev paylaşımı tarayıcıda canlı çalışıyor. Her sekmede:

- **Anlatımlı mod:** Her adım altyazıyla, 3 aşamada gösterilir.
- **Hesap kartı:** Seçtiğin bireyin o adımda yaptığı hesap sayılarla yazılır.
- **Deneyler:** Tek tıkla bir ayarı boz, ne olduğunu gör.
- **Adil karşılaştırma:** Her ayar aynı 30 başlangıçla çalıştırılır, sonuç tabloya yazılır.

👉 **Siteyi aç:** https://helalilal.github.io/Suru-Laboratuvari/

## Sekmeler

| Sekme | Konu |
| --- | --- |
| Başla | Sürü zekâsı ve sürü robotiği nedir, algoritma haritası, kendini yoklama soruları |
| Kuşlar | Ayrıl, hizalan, birleş: üç kuraldan sürü (Boids) |
| Dağda hazine | Tepe tırmanma ve benzetilmiş tavlama: yerel en iyiye takılmak |
| Parçacıklar (PSO) | Parçacık sürüsü optimizasyonu |
| Karıncalar & bakteriler | Karınca kolonisi (ACO) ve bakteri yiyecek arama (BFO) |
| Robot sürüsü | Çekim–itme kuralı, sürü boyutu sınırı ve yiyecek arama |
| Anlaşma | Lidersiz anlaşma (consensus), gecikme ve kopuk bağlantılar |
| Görev pazarı | Açık artırma ve dedikoduyla görev paylaşımı |
| Arena | Algoritmaların adil yarışı ve sürü hareket testi |

## Kullanım

Kurulum gerekmez. `index.html` dosyasını tarayıcıda açman yeterli; bütün kod bu tek dosyanın içinde.

## Kaynaklar

**Temel kitaplar**
- J. Kennedy, R. C. Eberhart, Y. Shi, *Swarm Intelligence*, Morgan Kaufmann, 2001.
- V. Gazi, K. M. Passino, *Swarm Stability and Optimization*, Springer, 2011.
- H. Hamann, *Swarm Robotics: A Formal Approach*, Springer, 2018.

**Klasik makaleler**
- S. Kirkpatrick, C. D. Gelatt, M. P. Vecchi, “Optimization by Simulated Annealing”, *Science* 220, 1983.
- R. Olfati-Saber, J. A. Fax, R. M. Murray, “Consensus and Cooperation in Networked Multi-Agent Systems”, *Proceedings of the IEEE* 95(1), 2007.
- H.-L. Choi, L. Brunet, J. P. How, “Consensus-Based Decentralized Auctions for Robust Task Allocation”, *IEEE Transactions on Robotics* 25(4), 2009.
- M. Brambilla, E. Ferrante, M. Birattari, M. Dorigo, “Swarm robotics: a review from the swarm engineering perspective”, *Swarm Intelligence* 7(1), 2013.
- M. Rubenstein, A. Cornejo, R. Nagpal, “Programmable self-assembly in a thousand-robot swarm”, *Science* 345, 2014.

**Güncel çalışmalar**
- M. Schranz, M. Umlauft, M. Sende, W. Elmenreich, “Swarm Robotic Behaviors and Current Applications”, *Frontiers in Robotics and AI* 7, 2020.
- E. Tolstaya vd., “Learning Decentralized Controllers for Robot Swarms with Graph Neural Networks”, *CoRL*, PMLR 100, 2020.
- M. Dorigo, G. Theraulaz, V. Trianni, “Reflections on the future of swarm robotics”, *Science Robotics* 5(49), 2020.
- M. Dorigo, G. Theraulaz, V. Trianni, “Swarm Robotics: Past, Present, and Future”, *Proceedings of the IEEE* 109(7), 2021.
- X. Zhou vd., “Swarm of micro flying robots in the wild”, *Science Robotics*, 2022.
- C. Aranha vd., “Metaphor-based metaheuristics, a call for action: the elephant in the room”, *Swarm Intelligence* 16, 2022.
- C. L. Camacho-Villalón, M. Dorigo, T. Stützle, “Exposing the grey wolf, moth-flame, whale, firefly, bat, and antlion algorithms”, *International Transactions in Operational Research* 30(6), 2023.
- V. Strobel, M. Dorigo, M. Fritz, “LLM2Swarm: Robot Swarms that Responsively Reason, Plan, and Collaborate through LLMs”, NeurIPS 2024 Workshop, arXiv:2410.11387.
- Eser, Yılmaz, “A Gossip-Based Auction Algorithm for Decentralized Task Rescheduling in Heterogeneous Drone Swarms”, *IEEE Transactions on Aerospace and Electronic Systems* 61(3), 2025 (görev pazarı sekmesi bu çalışmanın sadeleştirilmiş hâlidir).
- A. F. T. Winfield, M. Swana, J. Ives, S. Hauert, “On the ethical governance of swarm robotic systems in the real world”, *Philosophical Transactions of the Royal Society A* 383, 2025.

Sitedeki modeller öğretmek için sadeleştirilmiştir; ayrıntılar ve farklar her sekmede yazılıdır.

## Lisans

- **Kod:** [MIT](LICENSE)
- **Anlatım metinleri:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.tr). Kaynak göstererek kullanabilir, paylaşabilir ve uyarlayabilirsin.
