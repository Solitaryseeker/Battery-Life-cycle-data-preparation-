# Battery-Life-cycle-data-preparation- 

[View Interactive Plot](photo/battery_cycle_life_distribution.html)

# about data 
 The dataset is study of 124 commercial lithium-ion batteries
 (APR18650M1A) manufactured by A123 Systems. They have
 a nominal voltage of 3.3 V and nominal capacity of 1.1 Ah and
 uses lithium iron phosphate (LFP)/graphite chemistry. They
 support fast charging and high-rate discharging, which are
 appropriate for the application for the study of early-cycle
 markers for battery degradation and cycle life estimation [2] .
 All tests were carried out in 48-channel Arbin LBT po
tentiostats within a temperature-controlled chamber at 30 °C,
 with cells held in horizontal cylindrical fixtures. Temperature
 was monitored using Type T thermocouples cemented to
 the exposed cell can with thermal epoxy and Kapton tape,
 although slight variability in thermal contact at times impacted
 readings. IR measurements were taken at 80% state-of-charge
 (SOC) with ten ±3.6C pulses of 30–33 ms duration, depending
 on batch.
 Three experimental batches’ worth of data are combined in
 this dataset performed on 2017-05-12 (Batch 1), 2017-06-30
 (Batch 2), and 2018-04-12 (Batch 3). All the batches employed
 fast-charging schemes, that is, one-step or two-step constant
current (CC) policies, termed as C1(Q1)-C2, where C1 and
 C2 are the first and second CC steps, and Q1 is the SOC at
 which the change occurs in the current. After the fast-charge
 procedures, 1C CC-CV charging to 80% SOC and discharging
 at 4C were executed.
 Experimental batch-to-batch variations included charg
ing/rest times, CV step cutoff currents, IR pulse times, and
 replication per policy. Specifically:
 * Batch 1 (2017-05-12) employed 8–13.3 minute charging
 cycles (0–80% SOC) with 1-minute and 1-second rest times,
 C/50 CV cutoff, and 30 ms IR pulses.
 * Batch 2 (2017-06-30) also tested some of the Batch 1
 cells, with fixed charge times of 10 minutes, rests of 5 minutes,
 C/50 CV cutoff, and IR pulses of 30 ms.
 * Batch 3 (2018-04-12) charged two-step charging only, 10
minute fixed charge, four pauses of 5 seconds, C/20 CV limit,
 and 33 ms IR pulses, with 3–8 cells per rule.
 For this work, the data from all three batches were col
lated into a single dataset. The cells that were carried over
 between batches were treated as continuous experiments, and
 all the early-cycle, mid-cycle, and end-of-life measurements
 were coaxed into alignment into an organized dataset. The
 integrated dataset contains cell voltage, current, SOC, internal
 resistance, and temperature measurements, along with meta
data explaining any experiment anomalies such as computer
 crashes, misplacement of thermocouples, or early cutting off
 of individual cells.
 The combined dataset allows for detailed examination of
 early-cycle measures in order to predict battery cycle life using
 machine learning methods and present a good reference for
 charging conditions at high rates.
