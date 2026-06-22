# June 22 2026

First, I decided what the project's scope was going to look like.
High-powered transformers are usually driven through Zero-Voltage Switching or ZVS. However, when you want to adjust frequency and duty cycle, or if you just want to make a cheaper driver, you can use a 555 oscillator as the core.
However, this is more inefficient and creates more heat. However, it's what I went with because it is easier to modulate frequency of the arc based on audio signals.

First, I made the 'power supply' for the logic components. Some people limit the primary voltage to the max the interrupter can handle, which is 16V. However, I wanted to drive my transformers at 24V. This meant I had to make my own mini regulator for 12V so that the logic components wouldn't get fried.

<img width="179" height="125" alt="Screenshot 2026-06-22 at 11 00 02 AM" src="https://github.com/user-attachments/assets/982ffa6f-cd11-422f-9062-5861ee72c5c0" />

After that, I made a 555 timer based oscillator that took in input from an RCA jack.

<img width="486" height="274" alt="Screenshot 2026-06-22 at 11 00 57 AM" src="https://github.com/user-attachments/assets/152d9842-51a9-44fb-b6b3-9d260ab282c8" />

I then put it all together and assigned footprints.

<img width="616" height="508" alt="Screenshot 2026-06-22 at 11 02 44 AM" src="https://github.com/user-attachments/assets/3fdf88e1-0186-4024-8d85-848b3932679f" />

<img width="631" height="574" alt="Screenshot 2026-06-22 at 11 03 03 AM" src="https://github.com/user-attachments/assets/e7bdb98f-bf7c-45a6-b81c-96b5f9fbfdb5" />

I imported the footprints in, organized it, and routed it. This was kinda a pain due to high currents through thick traces while also routing delicate signals.

<img width="614" height="694" alt="Screenshot 2026-06-22 at 11 03 25 AM" src="https://github.com/user-attachments/assets/590c45af-36a1-4987-adc7-ee9a5c207fcb" />

<img width="762" height="850" alt="Screenshot 2026-06-22 at 11 04 23 AM" src="https://github.com/user-attachments/assets/e303de74-45a8-4dae-9265-bcad258afafc" />

Time Spent: 5 Hours
