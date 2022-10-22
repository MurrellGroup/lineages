# SARS-CoV-2 Lineage Competition (2022-10-20)

Results from a model of global SARS-CoV-2 lineage competition

Estimates of multiplicative growth advantage (per week) for lineages are provided, both relative to the basal BA.2, and to the recently-dominant BA.5.2.1.

## Advantage Estimates

<img src="plots/top_lineages_MCMC_lineage_growths_relative_to_BA.5.2.1.svg" style="width: 2800px;">

<img src="plots/N_MCMC_mutations.svg" style="width: 2800px;">

<img src="plots/N_MCMC_lineage_growths.svg" style="width: 2800px;">

<img src="plots/MCMC_lineage_growths_relative_to_BA.5.2.1.svg" style="width: 2800px;">

Inferred growth advantage mapped upon the Nextclade-curated phylogeny:

<img src="plots/tree.svg" style="width: 2800px;">

## Variant trajectories

For countries with more than 2500 genomes deposited in the last 50 days, we plot the model trajectory estimates and forecasts. Forecasts for variants where the sampled genomes fall off prior to variant emergence are driven by global pooled estimates and should be treated with caution.

Bayesian 95% Credible Intervals are shown for: BF.7, BQ.1, BQ.1.1, XBB.3, XBB.1

Variants are colored (from blue to red) in order of the number (low to high) of convergent mutations they exhibit (ie. those in mutation plot above).

### Germany

<img src="plots/sequence_volume_Germany.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Germany.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Germany.svg" style="width: 2800px;">

### Israel

<img src="plots/sequence_volume_Israel.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Israel.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Israel.svg" style="width: 2800px;">

### Italy

<img src="plots/sequence_volume_Italy.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Italy.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Italy.svg" style="width: 2800px;">

### Sweden

<img src="plots/sequence_volume_Sweden.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Sweden.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Sweden.svg" style="width: 2800px;">

### Belgium

<img src="plots/sequence_volume_Belgium.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Belgium.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Belgium.svg" style="width: 2800px;">

### Australia

<img src="plots/sequence_volume_Australia.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Australia.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Australia.svg" style="width: 2800px;">

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

### England

<img src="plots/sequence_volume_England.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_England.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_England.svg" style="width: 2800px;">

### Denmark

<img src="plots/sequence_volume_Denmark.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Denmark.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Denmark.svg" style="width: 2800px;">

### USA

<img src="plots/sequence_volume_USA.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_USA.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_USA.svg" style="width: 2800px;">

SARS-CoV-2 sequence data from GISAID EpiCov (bulk .fasta download, 2022-10-20). We gratefully acknowledge all data contributors, i.e. the Authors and their Originating Laboratories responsible for obtaining the specimens, and their Submitting Laboratories that generated the genetic sequence and metadata and shared via the GISAID Initiative the data on which part of this research is based. Lineage assignments were made by Nextclade.

Countries included in the model: Brunei, India, Slovakia, Mexico, Peru, Iceland, Russia, Turkey, Chile, Wales, Croatia, Indonesia, Slovenia, Spain, Ireland, Portugal, Luxembourg, Poland, Scotland, Switzerland, Germany, Israel, Italy, Sweden, Belgium, Australia, France, Japan, Canada, England, Denmark, USA

SARS-CoV-2 lineages included in the model: BA.2, BA.2.10, BA.2.10.2, BA.2.12.1, BA.2.12.2, BA.2.13, BA.2.13.1, BA.2.18, BA.2.24, BA.2.29, BA.2.3, BA.2.3.1, BA.2.3.11, BA.2.3.13, BA.2.3.2, BA.2.3.20, BA.2.36, BA.2.38, BA.2.38.1, BA.2.38.2, BA.2.40.1, BA.2.42, BA.2.56, BA.2.65, BA.2.74, BA.2.75, BA.2.75.1, BA.2.75.10, BA.2.75.2, BA.2.75.3, BA.2.75.4, BA.2.75.5, BA.2.75.6, BA.2.75.7, BA.2.76, BA.2.9, BA.2.9.3, BA.4, BA.4.1, BA.4.1.1, BA.4.1.10, BA.4.1.3, BA.4.1.4, BA.4.1.5, BA.4.1.6, BA.4.1.8, BA.4.1.9, BA.4.2, BA.4.3, BA.4.4, BA.4.5, BA.4.6, BA.4.6.1, BA.4.6.2, BA.4.6.4, BA.4.7, BA.5, BA.5.1, BA.5.1.1, BA.5.1.10, BA.5.1.11, BA.5.1.12, BA.5.1.15, BA.5.1.16, BA.5.1.17, BA.5.1.18, BA.5.1.19, BA.5.1.2, BA.5.1.20, BA.5.1.21, BA.5.1.22, BA.5.1.23, BA.5.1.24, BA.5.1.25, BA.5.1.26, BA.5.1.27, BA.5.1.28, BA.5.1.3, BA.5.1.4, BA.5.1.5, BA.5.1.6, BA.5.1.7, BA.5.1.8, BA.5.1.9, BA.5.10.1, BA.5.2, BA.5.2.1, BA.5.2.12, BA.5.2.13, BA.5.2.14, BA.5.2.16, BA.5.2.18, BA.5.2.19, BA.5.2.2, BA.5.2.20, BA.5.2.21, BA.5.2.22, BA.5.2.23, BA.5.2.24, BA.5.2.25, BA.5.2.26, BA.5.2.27, BA.5.2.28, BA.5.2.29, BA.5.2.3, BA.5.2.30, BA.5.2.31, BA.5.2.33, BA.5.2.34, BA.5.2.35, BA.5.2.36, BA.5.2.37, BA.5.2.4, BA.5.2.5, BA.5.2.6, BA.5.2.7, BA.5.2.8, BA.5.2.9, BA.5.3, BA.5.3.1, BA.5.3.2, BA.5.3.3, BA.5.3.4, BA.5.5, BA.5.5.1, BA.5.5.2, BA.5.5.3, BA.5.6, BA.5.6.1, BA.5.6.2, BA.5.6.3, BA.5.7, BA.5.8, BA.5.9, BE.1, BE.1.1, BE.1.1.1, BE.1.1.2, BE.1.2, BE.1.2.1, BE.1.3, BE.1.4, BE.1.4.1, BE.1.4.2, BE.1.4.4, BE.2, BE.3, BE.4, BE.4.1, BE.5, BF.1, BF.10, BF.11, BF.11.1, BF.11.3, BF.11.4, BF.11.5, BF.12, BF.13, BF.14, BF.15, BF.16, BF.17, BF.18, BF.19, BF.2, BF.21, BF.22, BF.23, BF.24, BF.25, BF.26, BF.27, BF.28, BF.29, BF.3, BF.3.1, BF.4, BF.5, BF.6, BF.7, BF.7.1, BF.7.2, BF.7.4, BF.7.5, BF.7.6, BF.7.7, BF.7.8, BF.8, BF.9, BG.2, BG.5, BH.1, BJ.1, BK.1, BL.1, BL.2, BL.3, BL.4, BM.1, BM.1.1, BM.1.1.1, BM.1.1.3, BM.4.1.1, BN.1, BN.1.3, BN.2, BN.5, BN.6, BQ.1, BQ.1.1, BQ.1.1.1, BQ.1.10, BQ.1.10.1, BQ.1.11, BQ.1.12, BQ.1.13, BQ.1.14, BQ.1.16, BQ.1.2, BQ.1.3, BQ.1.5, BQ.1.6, BQ.1.8, BR.1, BT.1, BT.2, BU.1, BU.2, BV.1, BV.2, BY.1, BZ.1, CA.1, CA.3, CC.1, CE.1, CF.1, CG.1, CK.1, CM.2, CN.1, CR.1, XAN, XAS, XAZ, XBB.1, XBB.3

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

