# Introduction-to-Optiperformer


## Aim
Download and install OptiPerformer software on your computer and run a sample file.

## Software required
Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.

The system is *instrumented* with:
- An optical power meter at the input to the receiver (or the output of the fiber)  
- A bit error rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from the [optiwave.com](https://optiwave.com) website.
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.
3. Start OptiPerformer.
4. Use either the **File menu** or the **Open File** button to open the Fiber Optic System File.
5. Study the layout, which includes text and boxes identifying the three components of the fiber optic system:
   - **Transmitter section**: binary source (PRBS generator), electrical pulse generator, laser diode, external modulator  
   - **Receiver section**: photodiode, low-pass filter, decision circuit (with BER analyzer)  
   *(These components will be covered in more detail later in the course.)*
6. Run the simulation by pressing the **Start** button.  
   - Progress will be displayed.  
   - The message *“Calculation Finished!”* will appear when complete.
7. Double-click on the optical power meter and BER analyzer.  
   - Move the windows as necessary for clarity.  
   - In the BER window, check the box **Show Eye Diagram**.  
   - The optical power meter shows power at the photodiode input in both watts and dBm.  
   - The BER window displays the eye diagram and quantities including **Max Q Factor** and **Min BER**.
8. The simulation runs **5 iterations**, with fiber length varying from 50 km to 150 km in 5 steps.  
   - The index is displayed in the upper right corner of the layout.  
   - Use the forward/reverse buttons in the lower left to step through iterations.  
   - Note changes in received power and BER display (eye diagram, Q factor, BER) with fiber length.
## Tabulation
![WhatsApp Image 2026-01-24 at 1 35 43 PM](https://github.com/user-attachments/assets/02e156db-f34f-4aca-a20b-146e826c8ab6)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e92031bc-9d1b-4c07-b938-7b59202ac088" />
## Description:
This OptiPerformer simulation displays the performance of a 90 km fiber link operating at a bit rate of 2.5 Gbps and a frequency of 193.1 THz. The results show a high-quality signal with a Max Q Factor of 44.545 and a wide-open eye diagram, which indicates minimal noise and jitter. At this specific distance, the optical power of -21.079 dBm is sufficient to maintain a zero Bit Error Rate (BER), ensuring successful data recovery without errors.

## Result:
 Thus the experimtent is completed successfully.
---


