# gaussian-quest-experiments
Experiments with 3d gaussian splats and Meta Quest VR viewer

Convert your SPZ to PLY with [Storysplat](https://storysplat.com/editor), cleanup the splat with [Supersplat](https://superspl.at/editor), convert back to SPZ wirh [Storysplat](https://storysplat.com/editor), copy to your Quest and open it with [Wakufactory](https://wakufactory.jp/wxr/splats/splatview.html) viewer.


## Software

### Viewers

- [Scaniverse official](https://scaniverse.8thwall.app/model-viewer/) (SPZ, PLY)
- [Wakufactory VR](https://wakufactory.jp/wxr/splats/splatview.html) (AR/VR, Quest compatible; also **loads remote urls**, just append link after "?") (PLY, SPZ, SPLAT, KSPLAT) ([Source code](https://github.com/mkkellogg/GaussianSplats3D))
- [BabylonJS sandobx](https://sandbox.babylonjs.com/) (PLY, SPZ, SPLAT)
- [Playcanvas](https://playcanvas.com/model-viewer) (PLY)
- [Niujinshuchong](https://niujinshuchong.github.io/mip-splatting-demo/index.html) (PLY, SPLAT, KSPLAT) (also converter)
- [webgl-gaussian-splatting.vercel.ap](https://webgl-gaussian-splatting.vercel.app/)p ([Source code](https://github.com/kishimisu/Gaussian-Splatting-WebGL))
- [Storysplat](https://storysplat.com/editor) (PLY, SPZ, SPLAT) (editor and converter, but it also **loads from remote urls**, look in "File" menu)

### Editors

- [Supersplat](https://superspl.at/editor) (PLY, SPLAT) (splats selection/deletion, converter) (no .SPZ)
- [Storysplat](https://storysplat.com/editor) (PLY, SPZ, SPLAT) (also converter; also loads from remote url, look in "File" menu)
- [Niantic studio](https://www.8thwall.com/docs/studio/) (login required)
- [Playcanvas](https://playcanvas.com/products/editor) (login required)

## Splats

### Relaxing places

It's winter, it's raining, but you want to relax outside under the sun, reading a book? Try these virtual places (experimental): save them to your Meta Quest viewer, then open them in [Wakufactory](https://wakufactory.jp/wxr/splats/splatview.html) viewer, then select "AR"; then move to the hollow area: there you can "sit", and your hands and your books hould be visible in passthrough, allowing you to read.

#### A tree on the beach
  
![image](https://github.com/user-attachments/assets/7c802939-259d-4203-8ea4-959145f1e583)

  -  [Original](https://github.com/jumpjack/gaussian-quest-experiments-/raw/refs/heads/main/vrGaussians-albero.spz) (not suitable for reading)
  -  [Cleaned up and with deleted area for passthrough](https://github.com/jumpjack/gaussian-quest-experiments-/blob/main/vrGaussians-albero-libro4.spz) (for reading books)

#### In the forest

- (upcoming)
