![Logo](https://deftware.org/cdn/shop/products/logo_sq_nb_360x.png)

This is SnapMaker's post-processing configuration file for the Deftware PixelCNC software. Motto: "By artists, for artists."
Includes postprocessing configuration for the 50- and 200-watt modules.

**The official website is**
- [https://deftware.org/pages/pixelcnc](https://deftware.org/pages/pixelcnc)

**How to add the snapmaker post-processing to PixelCNC?**

0. Firstly, Deftware mentioned that they may add Snapmaker postprocessing configurations in a future update. Please check whether they have done so before manually installing these files yourself.
1. If they haven't, then copy the Snapmaker*.txt files you need to `C:\Program Files\Deftware\PixelCNC\posts`.
2. You can verify they are installed when you choose File -> Export G-code and click "Post-Processor."

#### <span style="color:red">Warn !!!</span>
1. While the post-processing files do specify the maximum feed rates and spindle speeds, they are not appropriate for all materials so you should still set them according to the material of each project.


