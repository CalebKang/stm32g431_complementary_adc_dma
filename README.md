# stm32g431_complementary_adc_dma

ADC Multi trigger – Discontinuous mode enable

- DISCEN Enable
- 4 Channel Scan 
- 1st Group : Channel1, Channe2  
- 2nd Group : Channel1, Channe2 
- DISCNUM 2 Channels 로설정
- DMA_CNDTRx 의 길이를 4로 변경
- Trigger2 이후 ADC Conversion 완료 시 Transfer Complete Callback IRQ 발생

