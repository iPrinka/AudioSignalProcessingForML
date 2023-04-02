# notes

- [Sample Rate](https://crumplepop.com/what-sample-rate-should-i-record-at/)
  - Humans perceive the frequency of sound waves as pitch. Higher the frequency, higher the pitch.
  - We can hear sounds between 20 and 20,000 Hz and are most sensitive to frequencies between 2,000 and 5,000 Hz.
  - The sample rate is the number of times per second audio is sampled. For instance, at a sample rate of 44.1 kHz, the waveform is captured 44100 times per second.
  - The sample rate should be atleast two times the highest frequency we intend to capture to represent an audio signal accurately because if we want to measure, capture and recreate the frequency of a sound wave, we must identify its complete cycle meaning both it's negative and positive stage.
  - Since the max frequency humans can hear is 20,000 Hz, the standard sampling rate should ideally be 40,000 Hz. But it is 44,100 Hz (44.1 kHz) because the additional 4.1kHz acts like a buffer for the low-pass filter when converting the analog signal to digital signal.
  - Human Ear's time/temporal resolution: 10ms which means it takes us 10ms to register rapid changes in a sound.
