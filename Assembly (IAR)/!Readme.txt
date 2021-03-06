File Name                         Description
--------------------------------------------------------------------------------
MSP430G2x32_adc10_01.s43      ADC10, Sample A0, Set P1.0 if A0 > 0.5*AVcc
MSP430G2x32_adc10_02.s43     ADC10, Sample A1, 1.5V Ref, Set P1.0 if A1 > 0.2V
MSP430G2x32_adc10_03.s43      ADC10, ADC10, Sample A10 Temp, Set P1.0 if Temp ++ ~2C
MSP430G2x32_adc10_04.s43       ADC10, ADC10, Sample A1, Signed, Set P1.0 if A1 > 0.5*AVcc
MSP430G2x32_adc10_05.s43       ADC10, ADC10, Sample A11, Lo_Batt, Set P1.0 if AVcc < 2.3V
MSP430G2x32_adc10_06.s43       ADC10, ADC10, Output Internal Vref on P1.4 & ADCCLK on P1.3
MSP430G2x32_adc10_07.s43       ADC10, DTC Sample A1 32x, AVcc, Repeat Single, DCO
MSP430G2x32_adc10_08.s43       ADC10, ADC10, DTC Sample A1 32x, 1.5V, Repeat Single, DCO
MSP430G2x32_adc10_09.s43       ADC10, ADC10, DTC Sample A10 32x, 1.5V, Repeat Single, DCO
MSP430G2x32_adc10_10.s43       ADC10, ADC10, DTC Sample A3-01, AVcc, Single Sequence, DCO
MSP430G2x32_adc10_11.s43       ADC10, ADC10, Sample A1, 1.5V, TA1 Trig, Set P1.0 if > 0.5V
MSP430G2x32_adc10_12.s43       ADC10, Sample A7, 1.5V, TA1 Trig, Ultra-Low Pwr
MSP430G2x32_adc10_13.s43       ADC10, DTC Sample A1 32x, AVcc, TA0 Trig, DCO
MSP430G2x32_adc10_14.s43       ADC10, DTC Sample A1-0 16x, AVcc, Repeat Seq, DCO
MSP430G2x32_adc10_16.s43       ADC10, ADC10, DTC Sample A0 -> TA1, AVcc, DCO
MSP430G2x32_adc10_temp.s43   ADC10, Sample A10 Temp and Convert to oC and oF
MSP430G2x12_ca_01.s43             Comp_A, Output Reference Voltages on P1.1
MSP430G2x12_ca_02.s43             Comp_A, Detect Threshold, Set P1.0 if P1.1 > 0.25*Vcc
MSP430G2x12_ca_03.s43             Comp_A, Simple 2.2V Low Battery Detect
MSP430G2xx2_1.s43                 Software Toggle P1.0
MSP430G2xx2_1_vlo.s43             Software Toggle P1.0, MCLK = VLO/8
MSP430G2xx2_clks.s43              Basic Clock, Output Buffered SMCLK, ACLK and MCLK/10
MSP430G2xx2_dco_flashcal.s43        DCO Calibration Constants Programmer
MSP430G2xx2_flashwrite_01.s43     Flash In-System Programming, Copy SegC to SegD
MSP430G2xx2_LFxtal_nmi.s43        LFXT1 Oscillator Fault Detection
MSP430G2xx2_lpm3.s43              Basic Clock, LPM3 Using WDT ISR, 32kHz ACLK
MSP430G2xx2_lpm3_vlo.s43          Basic Clock, LPM3 Using WDT ISR, VLO ACLK
MSP430G2xx2_nmi.s43               Basic Clock, Configure RST/NMI as NMI
MSP430G2xx2_P1_01.s43             Software Poll P1.4, Set P1.0 if P1.4 = 1
MSP430G2xx2_P1_02.s43             Software Port Interrupt on P1.4 from LPM4
MSP430G2xx2_P1_03.s43             Poll P1 With Software with Internal Pull-up
MSP430G2xx2_P1_04.s43             P1 Interrupt from LPM4 with Internal Pull-up
MSP430G2xx2_ta_01.s43             Timer_A, Toggle P1.0, CCR0 Cont. Mode ISR, DCO SMCLK
MSP430G2xx2_ta_02.s43             Timer_A, Toggle P1.0, CCR0 Up Mode ISR, DCO SMCLK
MSP430G2xx2_ta_03.s43             Timer_A, Toggle P1.0, Overflow ISR, DCO SMCLK
MSP430G2xx2_ta_04.s43             Timer_A, Toggle P1.0, Overflow ISR, 32kHz ACLK
MSP430G2xx2_ta_05.s43             Timer_A, Toggle P1.0, CCR0 Up Mode ISR, 32kHz ACLK
MSP430G2xx2_ta_06.s43             Timer_A, Toggle P1.0, CCR1 Cont. Mode ISR, DCO SMCLK
MSP430G2xx2_ta_07.s43             Timer_A, Toggle P1.0-3, Cont. Mode ISR, DCO SMCLK
MSP430G2xx2_ta_08.s43             Timer_A, Toggle P1.0-2, Cont. Mode ISR, 32kHz ACLK
MSP430G2xx2_ta_10.s43             Timer_A, Toggle P1.1/TA0, Up Mode, DCO SMCLK
MSP430G2xx2_ta_11.s43             Timer_A, Toggle P1.1/TA0, Up Mode, 32kHz ACLK
MSP430G2xx2_ta_13.s43             Timer_A, Toggle P1.1/TA0, Up/Down Mode, DCO SMCLK
MSP430G2xx2_ta_14.s43             Timer_A, Toggle P1.1/TA0, Up/Down Mode, 32kHz ACLK
MSP430G2xx2_ta_16.s43             Timer_A, PWM TA1, Up Mode, DCO SMCLK
MSP430G2xx2_ta_17.s43             Timer_A, PWM TA1, Up Mode, 32kHz ACLK
MSP430G2xx2_ta_19.s43             Timer_A, PWM TA1, Up/Down Mode, DCO SMCLK
MSP430G2xx2_ta_20.s43             Timer_A, PWM TA1-2, Up/Down Mode, 32kHz ACLK
MSP430G2xx2_ta_uart2400.s43       Timer_A, Ultra-Low Pwr UART 2400 Echo, 32kHz ACLK
MSP430G2xx2_usi_01.s43            USICNT Used as a One-Shot Timer Function, DCO SMCLK
MSP430G2xx2_usi_02.s43            SPI full-Duplex 3-wire Master
MSP430G2xx2_usi_03.s43            SPI full-Duplex 3-wire Slave
MSP430G2xx2_usi_04.s43            USI SPI Interface to HC165/164 Shift Registers
MSP430G2xx2_usi_05.s43            USI SPI Interface to TLC549 8-bit ADC
MSP430G2xx2_usi_06.s43             USI I2C Master Receiver, single byte
MSP430G2xx2_usi_07.s43             USI I2C Master Transmitter, single byte
MSP430G2xx2_usi_08.s43             USI I2C Slave Receiver, single byte
MSP430G2xx2_usi_09.s43             USI I2C Slave Transmitter, single byte
MSP430G2xx2_wdt_01.s43            WDT, Toggle P1.0, Interval Overflow ISR, DCO SMCLK
MSP430G2xx2_wdt_02.s43            WDT, Toggle P1.0, Interval Overflow ISR, 32kHz ACLK
MSP430G2xx2_wdt_04.s43            WDT+ Failsafe Clock, DCO SMCLK
MSP430G2xx2_wdt_05.s43            Reset on Invalid Address fetch, Toggle P1.0
MSP430G2xx2_wdt_06.s43            WDT+ Failsafe Clock, 32kHz ACLK