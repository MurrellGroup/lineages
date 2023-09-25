# SARS-CoV-2 Lineage Competition (2023-09-23)

Results from a model of global SARS-CoV-2 lineage competition

Estimates of multiplicative growth advantage (per week) for lineages are provided, both relative to the basal BA.2, and to the recently-dominant EG.5.1.1.

## Advantage Estimates

<img src="plots/top_100_lineages_MCMC_lineage_growths_relative_to_EG.5.1.1.svg" style="width: 2800px;">

<img src="plots/top_60_lineages_MCMC_lineage_growths_relative_to_EG.5.1.1.svg" style="width: 2800px;">

<img src="plots/N_MCMC_mutations.svg" style="width: 2800px;">

Inferred growth advantage mapped upon the Nextclade-curated phylogeny:

<img src="plots/tree.svg" style="width: 2800px;">

## Variant trajectories

For countries with more than 1100 genomes deposited in the last 50 days, we plot the model trajectory estimates and forecasts. Forecasts for variants where the sampled genomes fall off prior to variant emergence are driven by global pooled estimates and should be treated with caution.

Bayesian 95% Credible Intervals are shown for: DV.7.1, EG.1, EG.5.1, EG.5.1.1, EG.5.1.3, EG.5.1.4, EG.5.1.6, EG.6.1, FL.1.5.1, FL.4, FU.1, GE.1, GJ.1.2, GK.1.1, HF.1, HK.3, HV.1, XBB.1.16, XBB.1.16.1, XBB.1.16.11, XBB.1.16.15, XBB.1.16.6, XBB.1.5, XBB.1.5.10, XBB.1.5.72, XBB.1.9.1, XBB.2.3, XBB.2.3.13, XBB.2.3.2, XBC.1.6

Variants are colored (from blue to red) in order of the number (low to high) of convergent mutations they exhibit (ie. those in mutation plot above).

### Model Average

Averaging out the country-specific growth rate and intercept adjustments:

<img src="plots/variant_trajectories_model_avg.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_model_avg.svg" style="width: 2800px;">

### Australia

<img src="plots/sequence_volume_Australia.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Australia.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Australia.svg" style="width: 2800px;">

### Shanghai

<img src="plots/sequence_volume_Shanghai.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Shanghai.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Shanghai.svg" style="width: 2800px;">

### Spain

<img src="plots/sequence_volume_Spain.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Spain.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Spain.svg" style="width: 2800px;">

### England

<img src="plots/sequence_volume_England.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_England.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_England.svg" style="width: 2800px;">

### France

<img src="plots/sequence_volume_France.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_France.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_France.svg" style="width: 2800px;">

### Japan

<img src="plots/sequence_volume_Japan.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Japan.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Japan.svg" style="width: 2800px;">

### Canada

<img src="plots/sequence_volume_Canada.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Canada.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Canada.svg" style="width: 2800px;">

### USA

<img src="plots/sequence_volume_USA.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_USA.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_USA.svg" style="width: 2800px;">

### Sweden

<img src="plots/sequence_volume_Sweden.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Sweden.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Sweden.svg" style="width: 2800px;">

SARS-CoV-2 sequence data from GISAID EpiCov (bulk .fasta download, 2023-09-23). We gratefully acknowledge all data contributors, i.e. the Authors and their Originating Laboratories responsible for obtaining the specimens, and their Submitting Laboratories that generated the genetic sequence and metadata and shared via the GISAID Initiative the data on which part of this research is based. Lineage assignments were made by Nextclade.

Countries included in the model: Liaoning, Georgia, Taiwan, Norway, Anhui, Peru, Thailand, Gansu, Romania, Qinghai, Finland, Heilongjiang, Iceland, Mexico, Croatia, Fujian, Yunnan, Brazil, Luxembourg, Portugal, Switzerland, Sichuan, Hubei, Germany, Belgium, Israel, Scotland, Wales, Ireland, Denmark, Sweden, Italy, Australia, Shanghai, Spain, England, France, Japan, Canada, USA

SARS-CoV-2 lineages included in the model: BA.2, BA.2.86.1, BN.1.2.7, CH.1.1, CK.1.1.2, DV.6.2, DV.7, DV.7.1, DV.7.1.2, EG.1, EG.1.2, EG.1.3, EG.1.4, EG.1.5, EG.1.6, EG.1.8, EG.10.1, EG.11, EG.13, EG.14, EG.2, EG.2.2, EG.4, EG.4.3, EG.4.4, EG.5, EG.5.1, EG.5.1.1, EG.5.1.2, EG.5.1.3, EG.5.1.4, EG.5.1.5, EG.5.1.6, EG.5.1.7, EG.5.1.8, EG.5.1.9, EG.5.2, EG.5.2.1, EG.5.2.3, EG.6.1, EG.6.1.1, EG.7, EU.1, EU.1.1, EU.1.1.1, EU.1.1.3, FD.1.1, FD.2, FD.4, FE.1, FE.1.1, FE.1.1.1, FE.1.1.4, FE.1.2, FK.1.1, FK.1.1.2, FK.1.3.2, FK.1.5, FL.1, FL.1.3, FL.1.5, FL.1.5.1, FL.1.5.2, FL.10, FL.10.1, FL.10.2, FL.11, FL.12, FL.13, FL.13.2, FL.13.3, FL.14, FL.15, FL.16, FL.18, FL.19.1, FL.2, FL.2.3, FL.2.4, FL.2.5, FL.20, FL.20.1, FL.21, FL.21.1, FL.22, FL.24, FL.25, FL.28, FL.29, FL.3, FL.3.1, FL.3.2, FL.4, FL.4.10, FL.4.11, FL.4.2, FL.4.3, FL.4.5, FL.4.6, FL.4.8, FL.4.9, FL.5, FL.5.1, FL.7, FR.1, FR.1.1, FR.1.4, FT.3.1, FT.3.1.1, FU.1, FU.2, FU.2.1, FV.1, FW.1.1, FY.1.1, FY.1.2, FY.2, FY.2.1, FY.3, FY.3.1, FY.3.2, FY.3.3, FY.4.1, FY.4.1.1, FY.4.1.2, FY.4.2, FY.5, FY.6, GB.1, GD.1, GE.1, GE.1.1, GE.1.3, GF.1, GJ.1.1, GJ.1.2, GJ.1.2.2, GJ.1.2.3, GJ.1.2.5, GJ.2, GJ.3, GJ.4, GK.1, GK.1.1, GK.1.3, GK.2, GK.2.1, GK.3.1, GK.4, GL.1, GM.3.1, GN.1, GN.1.1, GN.4, GR.1, GS.1, GS.3, GS.4, GS.4.1, GU.1, GV.1, GW.1, GW.5, GY.1, GY.2.1, GY.5, GY.6, GY.7, GY.8, GZ.1, HA.1, HA.2, HC.2, HE.1, HF.1, HF.1.1, HF.1.2, HG.2, HH.1, HH.1.1, HH.2, HK.1, HK.11, HK.2, HK.3, HK.3.1, HK.3.2, HK.4, HK.6, HK.7, HK.8, HK.9, HN.1, HP.1.1, HR.1, HS.1, HS.1.1, HT.1, HT.2, HU.1.1, HV.1, HW.1, HW.1.1, HY.1, HZ.1, HZ.2, JA.1, JC.1, JD.1, JD.1.1, JD.1.2, JF.1, JF.2, JG.1, JG.2, JG.3, JJ.1, JL.1, XBB.1.16, XBB.1.16.1, XBB.1.16.10, XBB.1.16.11, XBB.1.16.12, XBB.1.16.13, XBB.1.16.14, XBB.1.16.15, XBB.1.16.16, XBB.1.16.17, XBB.1.16.18, XBB.1.16.19, XBB.1.16.2, XBB.1.16.20, XBB.1.16.21, XBB.1.16.22, XBB.1.16.23, XBB.1.16.3, XBB.1.16.4, XBB.1.16.5, XBB.1.16.6, XBB.1.16.7, XBB.1.16.8, XBB.1.16.9, XBB.1.17.1, XBB.1.18.1, XBB.1.22, XBB.1.22.1, XBB.1.22.2, XBB.1.22.3, XBB.1.33, XBB.1.4.2, XBB.1.41, XBB.1.41.1, XBB.1.41.2, XBB.1.42, XBB.1.42.1, XBB.1.42.2, XBB.1.5, XBB.1.5.1, XBB.1.5.10, XBB.1.5.100, XBB.1.5.102, XBB.1.5.103, XBB.1.5.104, XBB.1.5.105, XBB.1.5.106, XBB.1.5.12, XBB.1.5.13, XBB.1.5.15, XBB.1.5.16, XBB.1.5.17, XBB.1.5.18, XBB.1.5.24, XBB.1.5.27, XBB.1.5.28, XBB.1.5.30, XBB.1.5.31, XBB.1.5.35, XBB.1.5.37, XBB.1.5.4, XBB.1.5.44, XBB.1.5.49, XBB.1.5.5, XBB.1.5.51, XBB.1.5.59, XBB.1.5.66, XBB.1.5.67, XBB.1.5.7, XBB.1.5.70, XBB.1.5.71, XBB.1.5.72, XBB.1.5.73, XBB.1.5.77, XBB.1.5.86, XBB.1.5.89, XBB.1.5.90, XBB.1.5.95, XBB.1.9.1, XBB.1.9.2, XBB.2.3, XBB.2.3.10, XBB.2.3.11, XBB.2.3.13, XBB.2.3.2, XBB.2.3.3, XBB.2.3.5, XBB.2.3.6, XBB.2.3.7, XBB.2.3.8, XBC.1.3, XBC.1.6, XBC.1.6.1, XBC.1.6.2, XBC.1.6.3, XBC.1.6.4, XBL.3, XCF, XCH, XCH.1, XCJ, XCL

## HMC Diagnostics

We show Effective Sample Size (ESS) and plot chains for the global lineage advantage parameters, as well as the inferred frequencies for some time points and some countries.

<img src="plots/ESS_growth_rates.svg" style="width: 2800px;">

<img src="plots/growth_rate_chains.svg" style="width: 2800px;">

<img src="plots/ESS_props_USA_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_USA_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_USA_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time100.png" style="width: 2800px;">

<img src="plots/ESS_props_Denmark_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_Denmark_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_Denmark_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_Denmark_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_Denmark_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_Denmark_time100.png" style="width: 2800px;">

<img src="plots/ESS_props_Sweden_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_Sweden_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_Sweden_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_Sweden_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_Sweden_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_Sweden_time100.png" style="width: 2800px;">

<img src="plots/ESS_props_England_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_England_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_England_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_England_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_England_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_England_time100.png" style="width: 2800px;">

