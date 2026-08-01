Supplementary Material
======================

Open index.html in any modern web browser to browse all results.
No server or installation required — all videos are loaded locally.

If videos do not play, serve the folder over HTTP:
  python -m http.server 8080
then open http://localhost:8080 in your browser.

Contents
--------
index.html                      Main viewer (open this)
effect_comparison_videos/       Main comparison: Ours vs. VACE vs. CogVideoX vs. GT (6 effects)
comparison_videos3/             Additional comparisons, all five methods
zoom_comparison/                Focal-length zoom vs. ReCamMaster dolly
ood_results/                    Out-of-distribution 3-effect combinations
supplementary_mixed_style/      Two-effect combination samples
style_transfer_results_supp/    Camera style transfer demos
full_cam_control/               Real camera trajectory control (pan, tilt, etc.)
bokeh_match_results_realbokeh/  Real bokeh matching — before/after fine-tuning
exposure_match_results/         Real exposure matching — before/after fine-tuning
applications/                   Application demos (deblur, correction, reversal, zoom-out)
