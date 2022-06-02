# Project

stm32l496g disco video demo

<em>[TODO.md spec & Kanban Board](https://bit.ly/3fCwKfM)</em>

### Todo

- [ ] 播放器（wav,mp3,...）,播放存储在 SD 卡里的音频  
  - [ ] 熟悉 cs42l51 codec，参考例程了解如何播放，暂停，停止这些功能  
  - [ ] 熟悉 wav 文件格式  
  - [ ] Zephyr dts binding，对接 I2S 和 Codec 外设  
  - [ ] 播放器 demo  
- [ ] 麦克风，识别声音并通过耳机孔播放  
  - [ ] 熟悉 STM32 DFSDM 接口，并指定如何配置，DMA 使用  
  - [ ] Zephyr dts binding，对接 DMIC 外设  
  - [ ] 麦克风 demo  

### In Progress

  - [ ] 熟悉 STM32 SAI 接口，并知道如何配置成 I2S，PCM，DMA 使用  

### Done ✓


