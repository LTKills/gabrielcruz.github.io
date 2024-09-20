+++
public = "true"
date = "2024-09-20"
title = "LoRa Firefighting"
+++

## Fires in Brazil
2024 was a sad year for Brazilian forests, as wildfires decimated over 113,900 Km$^2$ of vegetation, not to mention the increase in pulmonary-related illnesses caused by the toxic smoke they generated.

![Brazil in flames](/images/brazil-fire-1.jpg)
Source: [Aljazeera](https://www.aljazeera.com/gallery/2024/9/17/firefighters-battle-wildfires-choking-brazilian-capital)

The main reasons behind the dynamic that are to blame for these catastrophic events are the record-hitting low relative air humidity across the entire country due to lack of rain; the wind gusts that several of the affected areas experience in the winter (which is from June 21 to September 23 in Brazil), which help spread the fire; and the criminal human-started fires, which account for over 90% of the fires across all regions right now.

![Burned forest in Brazil](/images/brazil-fire-2.jpg)
Source: [Aljazeera](https://www.aljazeera.com/gallery/2024/9/17/firefighters-battle-wildfires-choking-brazilian-capital)


## LoRa and LoRaWAN
LoRa stands for Long Range, a low-power, long-range (that much you should've guessed) radio technology that has been largely used in many applications of IoT (Internet of Things) since its release in 2016. The huge differential of LoRa is that it uses incredibly little power for its range. Depending on the settings used, LoRa could reach as far as 30 Km. However, more realistic applications usually report a maximum distance of 2 to 4 Km, which is still really good for many applications, especially considering that some areas are dense and thus make it difficult for the signal to propagate.

LoRaWAN (Long Range Wide Area Network) is the MAC (Media Access Control) layer for the LoRa stack. Think of it this way: if LoRa is the physical medium of the stack (i.e. how bits go from one place to the other), then LoRaWAN is _which_ messages (bits) need to go where and in what order to make communication effective.

## LoRa Firefighting
For the reasons outlined above, LoRa has been used for several applications, some of which involve aiding in catastrophic events such as landslides, floods, and, of course, wildfire detection and prediction. In my current research, I aim to identify methods for wildfire prediction and early detection. The latter is especially crucial for firefighters since these types of fires spread rapidly and containing them early on is critical.

---
Thank you for reading!

## References
- [TerraBrasilis - Official Wildfire Data](https://terrabrasilis.dpi.inpe.br/app/dashboard/fires/biomes/aggregated/)
- [LoRa (Semtech)](https://www.semtech.com/lora)
