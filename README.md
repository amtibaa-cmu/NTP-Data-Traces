# NTP_Data_Traces
The datasets consisting of the raw timestamps and servers probed from multiple NTP client locations

We deployed NTP clients--two in North America (in Missouri, US and in New Mexico, US) and two in Europe (in Zurich, Switzerland and in Athens, Greece). We configured the NTP clients to use NTP pool for time synchronization. Each client queries four NTP pool servers and collects four time samples from each of these servers (the default configuration options for NTP) every minute over a 24-hour period.
