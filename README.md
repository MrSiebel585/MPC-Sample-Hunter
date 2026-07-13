# MPC-Sample-Hunter


venv) jeremy@omniscient:~/Music/MPC_Sample_Hunter $ mpc-sample-hunter
mpc-sample-hunter

Legal-first YouTube sample helper for finding sliceable drums, bass, keys,
guitar, synths, vocals, FX, and textures for MPC workflows.

How to use:

  mpc-sample-hunter doctor
  mpc-sample-hunter legal
  mpc-sample-hunter menu

Search:
  mpc-sample-hunter search "royalty free drum break" 20
  mpc-sample-hunter search-pack drums 25
  mpc-sample-hunter crate dusty 25
  mpc-sample-hunter crate boom-bap 25
  mpc-sample-hunter crate house 25
  mpc-sample-hunter crate jungle 25
  mpc-sample-hunter queries

Preview metadata:
  mpc-sample-hunter info "ytsearch1:royalty free drum break"

Download:
  mpc-sample-hunter download "ytsearch1:royalty free drum break" drums
  mpc-sample-hunter download "https://youtube.com/watch?v=VIDEO_ID" drums 600
  mpc-sample-hunter playlist "PLAYLIST_URL" drums 20 600
  mpc-sample-hunter batch-download urls.txt drums

Convert:
  mpc-sample-hunter convert

Clean audio:
  mpc-sample-hunter normalize
  mpc-sample-hunter trim

BPM:
  mpc-sample-hunter bpm break.wav
  mpc-sample-hunter bpm-dir
  mpc-sample-hunter sort-bpm

Slice:
  mpc-sample-hunter slice break.wav
  mpc-sample-hunter slice break.wav 0.5% 0.10
  mpc-sample-hunter slice-dir
  mpc-sample-hunter rechop break.wav 0.5% 0.08
  mpc-sample-hunter extract-hits break.wav 1% 0.06
  mpc-sample-hunter slice-fixed break.wav 4

Build pack:
  mpc-sample-hunter pack dusty_drums
  mpc-sample-hunter pack dusty_drums ~/Music/MPC_Sample_Hunter/slices
  mpc-sample-hunter pad-map ~/Music/MPC_Sample_Hunter/packs/dusty_drums

Export:
  mpc-sample-hunter export-mpc dusty_drums

Defensible evidence:
  mpc-sample-hunter evidence-pack dusty_drums
  mpc-sample-hunter manifest
  mpc-sample-hunter report ~/Music/MPC_Sample_Hunter/packs/dusty_drums

Preview:
  mpc-sample-hunter preview-pack dusty_drums
  mpc-sample-hunter preview-pack ~/Music/MPC_Sample_Hunter/packs/dusty_drums

Dedupe:
  mpc-sample-hunter fingerprint break.wav
  mpc-sample-hunter dedupe

Sample operations:
  mpc-sample-hunter crate-status
  mpc-sample-hunter audition
  mpc-sample-hunter audition ~/Music/MPC_Sample_Hunter/wav 10
  mpc-sample-hunter random-pack random_drums drums 32
  mpc-sample-hunter rename-mpc ~/Music/MPC_Sample_Hunter/wav
  mpc-sample-hunter flatten-pack dusty_drums
  mpc-sample-hunter zip-pack dusty_drums
  mpc-sample-hunter find-long ~/Music/MPC_Sample_Hunter/wav 30
  mpc-sample-hunter find-short ~/Music/MPC_Sample_Hunter/wav 2.5
  mpc-sample-hunter make-oneshots ~/Music/MPC_Sample_Hunter/wav 2.5

Crate intelligence:
  mpc-sample-hunter quality-check
  mpc-sample-hunter auto-organize
  mpc-sample-hunter build-drum-kit my_drum_kit
  mpc-sample-hunter build-loop-pack my_loops
  mpc-sample-hunter build-texture-pack my_textures
  mpc-sample-hunter daily-report
  mpc-sample-hunter open-folders

Output folders:
  ~/Music/MPC_Sample_Hunter/raw
  ~/Music/MPC_Sample_Hunter/wav
  ~/Music/MPC_Sample_Hunter/slices
  ~/Music/MPC_Sample_Hunter/packs
  ~/Music/MPC_Sample_Hunter/exports
  ~/Music/MPC_Sample_Hunter/evidence
  ~/Music/MPC_Sample_Hunter/reports
  ~/Music/MPC_Sample_Hunter/previews

Best MPC workflow:

  mpc-sample-hunter crate dusty 25
  mpc-sample-hunter info "ytsearch1:creative commons drum break no talking"
  mpc-sample-hunter download "ytsearch1:creative commons drum break no talking" drums 600
  mpc-sample-hunter convert
  mpc-sample-hunter trim
  mpc-sample-hunter bpm-dir
  mpc-sample-hunter slice-dir
  mpc-sample-hunter pack dusty_drums
  mpc-sample-hunter export-mpc dusty_drums
  mpc-sample-hunter evidence-pack dusty_drums
(venv) jeremy@omniscient:~/Music/MPC_Sample_Hunter $ 

