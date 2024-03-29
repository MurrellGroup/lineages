# SARS-CoV-2 Lineage Competition (2023-11-25)

Results from a model of global SARS-CoV-2 lineage competition

Estimates of multiplicative growth advantage (per week) for lineages are provided, both relative to the basal BA.2, and to the recently-dominant EG.5.1.1.

## Advantage Estimates

<img src="plots/top_187_lineages_MCMC_lineage_growths_relative_to_EG.5.1.1.svg" style="width: 2800px;">

<img src="plots/top_60_lineages_MCMC_lineage_growths_relative_to_EG.5.1.1.svg" style="width: 2800px;">

<img src="plots/N_MCMC_mutations.svg" style="width: 2800px;">

Inferred growth advantage mapped upon the Nextclade-curated phylogeny (pruned to keep only relatively competative variants):

<img src="plots/tree_pruned.svg" style="width: 2800px;">

## Variant trajectories

For countries with more than 1100 genomes deposited in the last 50 days, we plot the model trajectory estimates and forecasts. Forecasts for variants where the sampled genomes fall off prior to variant emergence are driven by global pooled estimates and should be treated with caution.

Bayesian 95% Credible Intervals are shown for: BA.2.86.1, DV.7.1, EG.10.1, EG.5.1, EG.5.1.1, EG.5.1.3, EG.5.1.4, EG.5.1.6, EG.5.1.8, EG.6.1, FL.1.5.1, GE.1, GJ.1.2, GK.1.1, GK.2.1, GS.4, GS.4.1, HF.1, HK.2.1, HK.3, HK.6, HV.1, JD.1.1, JF.1, JG.3, JN.1, XBB.1.16, XBB.1.16.1, XBB.1.16.11, XBB.1.16.15, XBB.1.16.6, XBB.1.5, XCH.1

Variants are colored (from blue to red) in order of the number (low to high) of convergent mutations they exhibit (ie. those in mutation plot above).

### Model Average

Averaging out the country-specific growth rate and intercept adjustments:

<img src="plots/variant_trajectories_model_avg.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_model_avg.svg" style="width: 2800px;">

### Italy

<img src="plots/sequence_volume_Italy.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Italy.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Italy.svg" style="width: 2800px;">

### Japan

<img src="plots/sequence_volume_Japan.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Japan.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Japan.svg" style="width: 2800px;">

### Spain

<img src="plots/sequence_volume_Spain.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Spain.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Spain.svg" style="width: 2800px;">

### Denmark

<img src="plots/sequence_volume_Denmark.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Denmark.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Denmark.svg" style="width: 2800px;">

### Australia

<img src="plots/sequence_volume_Australia.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Australia.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Australia.svg" style="width: 2800px;">

### Sweden

<img src="plots/sequence_volume_Sweden.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Sweden.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Sweden.svg" style="width: 2800px;">

### France

<img src="plots/sequence_volume_France.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_France.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_France.svg" style="width: 2800px;">

### England

<img src="plots/sequence_volume_England.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_England.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_England.svg" style="width: 2800px;">

### USA

<img src="plots/sequence_volume_USA.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_USA.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_USA.svg" style="width: 2800px;">

### Canada

<img src="plots/sequence_volume_Canada.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Canada.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Canada.svg" style="width: 2800px;">

SARS-CoV-2 sequence data from GISAID EpiCov (bulk .fasta download, 2023-11-25). We gratefully acknowledge all data contributors, i.e. the Authors and their Originating Laboratories responsible for obtaining the specimens, and their Submitting Laboratories that generated the genetic sequence and metadata and shared via the GISAID Initiative the data on which part of this research is based. Lineage assignments were made by Nextclade.

Countries included in the model: Heilongjiang, Ukraine, Xinjiang, Shanxi, Henan, Bulgaria, Liaoning, Fujian, Gansu, Norway, Croatia, Taiwan, Portugal, Slovenia, Peru, Yunnan, Iceland, Luxembourg, Poland, Brazil, Chile, Hubei, Israel, Shanghai, Sichuan, Wales, Finland, Ireland, Scotland, Switzerland, Russia, Belgium, Germany, Italy, Japan, Spain, Denmark, Australia, Sweden, France, England, USA, Canada

SARS-CoV-2 lineages included in the model: BA.2, BA.2.86, BA.2.86.1, BA.2.86.2, BA.2.86.3, CK.1.1.2, DV.7.1, DV.7.1.1, DV.7.1.2, DV.7.1.3, DV.7.1.4, DV.7.1.5, EG.1, EG.1.6, EG.10.1, EG.2, EG.2.2, EG.4.3, EG.4.5, EG.5, EG.5.1, EG.5.1.1, EG.5.1.10, EG.5.1.2, EG.5.1.3, EG.5.1.4, EG.5.1.5, EG.5.1.6, EG.5.1.7, EG.5.1.8, EG.5.1.9, EG.5.2, EG.5.2.1, EG.5.2.3, EG.6.1, EG.6.1.1, EG.6.1.2, EG.7, EU.1.1, EU.1.1.3, FD.1.1, FD.4, FD.5.1, FE.1.1, FE.1.1.1, FE.1.1.5, FE.1.2, FK.1.1, FK.1.1.2, FK.1.3.2, FL.1, FL.1.5, FL.1.5.1, FL.1.5.2, FL.10.1, FL.10.2, FL.13.2, FL.13.4.1, FL.14, FL.15, FL.15.1.1, FL.15.2, FL.15.3, FL.16, FL.19.1, FL.2, FL.2.3, FL.2.5, FL.20, FL.20.1, FL.20.2, FL.21, FL.24, FL.25, FL.31.1, FL.32.1, FL.33.1, FL.36, FL.4, FL.4.6, FL.4.8, FL.5, FT.3.1.1, FU.1, FU.1.1.1, FU.2, FU.2.1, FW.1.1, FY.1.2, FY.1.4.1, FY.2, FY.2.1, FY.3, FY.3.1, FY.3.2, FY.3.3, FY.4.1, FY.4.1.1, FY.4.1.2, FY.4.2, FY.5, FY.5.1, FY.5.1.1, FY.6.1, FY.6.2, FY.8, GA.4.1, GB.1, GD.1, GE.1, GE.1.1, GE.1.2, GE.1.3, GE.1.4, GE.1.5, GE.1.6, GJ.1.1, GJ.1.2, GJ.1.2.1, GJ.1.2.2, GJ.1.2.4, GJ.1.2.5, GJ.1.2.6, GJ.1.2.8, GJ.3, GJ.4, GJ.5, GJ.5.1, GK.1, GK.1.1, GK.1.1.1, GK.1.2, GK.1.2.1, GK.1.5, GK.1.6, GK.1.6.1, GK.1.8, GK.2, GK.2.1, GK.2.1.1, GK.2.3, GK.2.4, GK.3.1, GK.4, GK.6, GK.7, GK.8.1, GL.1, GN.1, GN.1.1, GS.1, GS.3, GS.4, GS.4.1, GS.4.1.1, GS.5, GS.6, GS.7, GV.1, GW.5, GW.5.1, GW.5.1.1, GW.5.2, GW.5.3, GW.5.3.1, GY.1, GY.5, GY.6, GY.7, GY.8, GZ.1, HC.3, HF.1, HF.1.1, HF.1.2, HG.2, HH.1, HH.1.1, HH.2.1, HH.5, HH.7, HK.1, HK.1.2, HK.11, HK.11.1, HK.12, HK.13, HK.13.1, HK.13.2, HK.14, HK.15, HK.16, HK.17, HK.19, HK.2, HK.2.1, HK.3, HK.3.1, HK.3.2, HK.3.3, HK.3.4, HK.3.5, HK.3.6, HK.3.7, HK.4, HK.6, HK.7, HK.8, HK.9, HN.1, HN.2, HN.2.1, HN.3, HN.3.1, HN.4, HN.5, HN.6, HP.1.1, HR.1, HS.1, HS.1.1, HT.2, HU.1.1, HV.1, HV.1.1, HV.1.2, HV.1.3, HV.1.4, HW.1, HW.1.1, HW.1.2, HY.1, HZ.1, HZ.2, JA.1, JC.1, JC.2, JC.5, JD.1, JD.1.1, JD.1.1.1, JD.1.1.2, JD.1.1.3, JD.1.2, JE.1, JE.1.1, JF.1, JF.2, JG.1, JG.2, JG.3, JG.3.1, JG.4, JJ.1, JL.1, JM.1, JM.2, JN.1, JN.2, JN.3, JQ.1, JR.1.1, JS.1, JS.2, JT.1, JU.1, JV.1, JV.2, JY.1, JY.1.1, JZ.1, KA.1, XBB.1.16, XBB.1.16.1, XBB.1.16.11, XBB.1.16.12, XBB.1.16.13, XBB.1.16.14, XBB.1.16.15, XBB.1.16.16, XBB.1.16.17, XBB.1.16.18, XBB.1.16.19, XBB.1.16.2, XBB.1.16.20, XBB.1.16.21, XBB.1.16.23, XBB.1.16.24, XBB.1.16.3, XBB.1.16.5, XBB.1.16.6, XBB.1.16.7, XBB.1.16.8, XBB.1.16.9, XBB.1.22, XBB.1.22.1, XBB.1.41.1, XBB.1.41.2, XBB.1.41.3, XBB.1.42, XBB.1.42.1, XBB.1.42.2, XBB.1.5, XBB.1.5.10, XBB.1.5.103, XBB.1.5.28, XBB.1.5.37, XBB.1.5.44, XBB.1.5.49, XBB.1.5.5, XBB.1.5.59, XBB.1.5.66, XBB.1.5.70, XBB.1.5.71, XBB.1.5.72, XBB.1.5.73, XBB.1.5.89, XBB.1.9.1, XBB.1.9.2, XBB.2.3, XBB.2.3.11, XBB.2.3.15, XBB.2.3.19, XBB.2.3.2, XBB.2.3.3, XBB.2.3.5, XBB.2.3.8, XBC.1.3, XBC.1.6, XBC.1.6.5, XCF, XCH, XCH.1, XCJ, XCK, XCL, XCM, XCP, XCQ, XCR, XCT, XCV, XCW, XCZ, XDA, XDB

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

Inferred growth advantage mapped upon the Nextclade-curated phylogeny (full tree):

<img src="plots/tree.svg" style="width: 2800px;">

## Methods summary

Lineage competition is modelled using a Bayesian multinomial regression approach. Briefly the global GISAID SARS-CoV-2 dataset (downloaded as a bulk .fasta file) is filtered for any sequences with collection dates within the previous 100 days. NextClade (with the BA.2 reference set, “sars-cov-2-21L”) is used for lineage assignment, and assignments are compiled into counts per country per lineage per day. If a sub-lineage is too infrequent to be included in the model, its count is added into its most recent included ancestor.

We model growth rates using a hierarchical approach. The growth rate for a lineage in a country is the sum of two components: a global rate, and a country-specific random effect. The global rate for each lineage is itself a sum of : i) branch-specific terms, for each branch ancestral to that lineage, plus ii) the sum of terms for "convergent" spike mutations (those occurring on multiple branches of the phylogeny) possessed by that lineage, plus iii) a lineage specific parameter. The rationale for this parameterization is that the contributions of a set of mutations that only occur on a single branch cannot be separated from each other, so those are just bundled into the branch-specific term, but evidence is shared when mutations occur on multiple branches. Further, growth rates are heritable over the phylogeny, and the model's expectation for a new lineage (which may not yet have large sequence volumes) is strongly informed by that of its ancestor's growth rate, since all-but-one of the branch-specific terms are in common, as are (typically) most of the convergent mutation terms. Practically, this is implemented by constructing a large sparse design matrix that encodes which lineages share branches and convergent mutations. Through this, we also allow recombinants to inherit a weighted mixture of their multiple parent's growth terms.

Introduction times are controlled by lineage-specific intercept terms, which have a global shared term per lineage, and country-specific random effects. Each "kind" of parameter has a Gaussian prior, centred on zero, and we use a Gaussian hyperprior over the log of the standard deviations of these priors. Posterior distributions for all parameters are sampled, via Hamiltonian Monte Carlo with the "No-U-Turn sampler" by AdvancedHMC.jl in Julia.

The "Model average" frequency plot intends to provide a "global" image of variant competition, and is produced using the posterior mean (over all post-burnin HMC samples) over all frequency trajectories but with the country-specific terms (including the country-specific growth rate random effects and the country-specific intercepts) set to their averages, no longer reflecting the details of any specific country, but also not being too strongly biased by unevenly distributed sequencing volumes for any specific country.


