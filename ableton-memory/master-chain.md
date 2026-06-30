# Master Chain Template

## Default Chain (VST3 preferred)

| # | Slot | Plugin | URI | Notes |
|---|------|--------|-----|-------|
| 1 | Console / Channel Strip | Arturia Pre 1973 | `query:Plugins#VST3:Arturia:Pre%201973` | Neve 1073 emulation, analog console character |
| 2 | Corrective EQ | FabFilter Pro-Q 3 | `query:Plugins#VST3:FabFilter:Pro-Q%203` | HP filter, cut problem frequencies |
| 3 | Compression / Glue | Arturia Comp FET-76 | `query:Plugins#VST3:Arturia:Comp%20FET-76` | 2-4dB GR, slow attack, fast-medium release |
| 4 | Saturation / Tape | Arturia Dist TUBE-CULTURE | `query:Plugins#VST3:Arturia:Dist%20TUBE-CULTURE` | Tube saturation, warmth, harmonics |
| 5 | Tonal EQ | UADx Pultec EQP-1A EQ | `query:Plugins#VST3:Universal%20Audio%20(UADx):UADx%20Pultec%20EQP-1A%20EQ` | Air boost, warmth |
| 6 | Exciter / Enhancer | Slate Digital Fresh Air | `query:Plugins#VST3:Slate%20Digital:Fresh%20Air` | Subtle sparkle |
| 7 | Stereo Imaging | Polyverse Wider | `query:Plugins#VST3:Polyverse%20Music:Wider` | Widen highs, keep bass mono |
| 8 | Limiter | FabFilter Pro-L 2 | `query:Plugins#VST3:FabFilter:Pro-L%202` | True peak, -1 to -0.3 dBTP ceiling |

## Alternative Options By Slot

### 1. Console / Channel Strip
| Plugin | URI | Notes |
|--------|-----|-------|
| Arturia Pre TridA | `query:Plugins#VST3:Arturia:Pre%20TridA` | Trident A-Range character |
| Arturia Pre V76 | `query:Plugins#VST3:Arturia:Pre%20V76` | Telefunken V76 tube |
| Arturia Bus FORCE | `query:Plugins#VST3:Arturia:Bus%20FORCE` | Bus compressor/console |
| AnalogObsession LALA | `query:Plugins#VST3:AnalogObsession:LALA` | LA-2A style |
| AnalogObsession BUSTERse | `query:Plugins#VST3:AnalogObsession:BUSTERse` | SSL bus style |
| AnalogObsession dBComp | `query:Plugins#VST3:AnalogObsession:dBComp` | FET compressor |
| AnalogObsession VariMoon | `query:Plugins#VST3:AnalogObsession:VariMoon` | Vari-mu style |

### 2. Corrective / Subtractive EQ
| Plugin | URI | Notes |
|--------|-----|-------|
| TDR VOS SlickEQ | `query:Plugins#VST3:Tokyo%20Dawn%20Labs:TDR%20VOS%20SlickEQ` | Musical, three-band |
| Melda MEqualizer | `query:Plugins#VST3:MeldaProduction:MEqualizer` | Full-featured parametric |

### 3. Compression / Glue
| Plugin | URI | Notes |
|--------|-----|-------|
| FabFilter Pro-C 2 | `query:Plugins#VST3:FabFilter:Pro-C%202` | Clean, versatile |
| FabFilter Pro-MB | `query:Plugins#VST3:FabFilter:Pro-MB` | Multiband |
| Arturia Comp VCA-65 | `query:Plugins#VST3:Arturia:Comp%20VCA-65` | VCA bus style |
| Arturia Comp TUBE-STA | `query:Plugins#VST3:Arturia:Comp%20TUBE-STA` | Tube bus (has Fairchild preset) |
| Arturia Comp DIODE-609 | `query:Plugins#VST3:Arturia:Comp%20DIODE-609` | Diode bridge character |
| Arturia Bus FORCE | `query:Plugins#VST3:Arturia:Bus%20FORCE` | Bus compressor |
| Leapwing DynOne3 | `query:Plugins#VST3:Leapwing%20Audio:DynOne3` | Multiband dynamics |
| Sonnox Oxford Inflator | `query:Plugins#VST3:Sonnox:Oxford%20Inflator` | Character/inflation |
| Melda MCompressor | `query:Plugins#VST3:MeldaProduction:MCompressor` | Clean compressor |

### 4. Saturation / Tape
| Plugin | URI | Notes |
|--------|-----|-------|
| FabFilter Saturn 2 | `query:Plugins#VST3:FabFilter:Saturn%202` | Multi-band, extremely versatile |
| Arturia Tape MELLO-FI | `query:Plugins#VST3:Arturia:Tape%20MELLO-FI` | Tape emulation |
| Soundtoys Decapitator | VST only | Classic saturation |
| Soundtoys Radiator | VST only | Tube character |
| iZotope Vinyl | `query:Plugins#VST3:iZotope:Vinyl` | Lo-fi/vinyl warmth |
| Melda MSaturator | `query:Plugins#VST3:MeldaProduction:MSaturator` | Multi-saturation |
| FabFilter One | `query:Plugins#VST3:FabFilter:One` | Simple saturator |

### 5. Tonal / Musical EQ
| Plugin | URI | Notes |
|--------|-----|-------|
| FabFilter Pro-Q 3 | `query:Plugins#VST3:FabFilter:Pro-Q%203` | Second instance if needed |
| UADx Pultec MEQ-5 EQ | `query:Plugins#VST3:Universal%20Audio%20(UADx):UADx%20Pultec%20MEQ-5%20EQ` | Midrange Pultec |
| UADx Pultec HLF-3C EQ | `query:Plugins#VST3:Universal%20Audio%20(UADx):UADx%20Pultec%20HLF-3C%20EQ` | Low/high pass Pultec |

### 6. Exciter / Enhancer
| Plugin | URI | Notes |
|--------|-----|-------|
| iZotope Ozone Imager 2 | `query:Plugins#VST3:iZotope:Ozone%20Imager%202` | Stereo/exciter combo |
| FabFilter Saturn 2 | `query:Plugins#VST3:FabFilter:Saturn%202` | Harmonic drive as exciter |

### 7. Stereo Imaging
| Plugin | URI | Notes |
|--------|-----|-------|
| iZotope Ozone Imager 2 | `query:Plugins#VST3:iZotope:Ozone%20Imager%202` | Full stereo toolkit |
| Xfer Dimension Expander | `query:Plugins#VST3:Xfer%20Records:Dimension%20Expander` | Simple widener |
| FabFilter Pro-Q 3 | `query:Plugins#VST3:FabFilter:Pro-Q%203` | Mid/side EQ imaging |
| Melda MStereoExpander | `query:Plugins#VST3:MeldaProduction:MStereoExpander` | Advanced stereo tools |
| ValhallaSpaceModulator | `query:Plugins#VST3:Valhalla%20DSP:ValhallaSpaceModulator` | Spatial modulation |

### 8. Limiter / Maximizer
| Plugin | URI | Notes |
|--------|-----|-------|
| Sonnox Oxford Inflator | `query:Plugins#VST3:Sonnox:Oxford%20Inflator` | Character limiter |
| Melda MLoudnessAnalyzer | `query:Plugins#VST3:MeldaProduction:MLoudnessAnalyzer` | Analysis only |
