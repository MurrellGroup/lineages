# SARS-CoV-2 Lineage Competition (2025-01-13)

Results from a model of global SARS-CoV-2 lineage competition

Estimates of multiplicative growth advantage (per week) for lineages are provided, both relative to the basal BA.2, and to the recently-dominant KP.3.1.1.

## Advantage Estimates

<img src="plots/all_lineages_MCMC_lineage_growths.svg" style="width: 2800px;">

<img src="plots/pruned_lineages_MCMC_lineage_growths.svg" style="width: 2800px;">

<img src="plots/N_MCMC_mutations.svg" style="width: 2800px;">

Inferred growth advantage mapped upon the Nextclade-curated phylogeny (pruned to keep only relatively competative variants):

<img src="plots/tree_pruned.svg" style="width: 2800px;">

## Variant trajectories

For countries with more than 200 genomes deposited in the last 50 days, we plot the model trajectory estimates and forecasts. Forecasts for variants where the sampled genomes fall off prior to variant emergence are driven by global pooled estimates and should be treated with caution.

Bayesian 95% Credible Intervals are shown for: JN.1, KP.1.1.3, KP.2.3, KP.3, KP.3.1, KP.3.1.1, KP.3.3, KP.3.3.1, LB.1.3.1, LF.7.1, LF.7.1.3, LP.8.1, MC.1, MC.1.3, MC.10, MC.10.1, MC.11, MC.13, MC.16, MC.19, MC.2, MC.24, MC.28, MC.6, MC.8.1, MC.9, MV.1, XDY, XEC, XEC.14, XEC.2, XEC.4, XEC.8, XEC.9, XEK

Variants are colored (from blue to red) in order of the number (low to high) of convergent mutations they exhibit (ie. those in mutation plot above).

### Model Average

Averaging out the country-specific growth rate and intercept adjustments:

<img src="plots/variant_trajectories_model_avg.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_model_avg.svg" style="width: 2800px;">

### Italy

<img src="plots/sequence_volume_Italy.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Italy.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Italy.svg" style="width: 2800px;">

### England

<img src="plots/sequence_volume_England.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_England.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_England.svg" style="width: 2800px;">

### Netherlands

<img src="plots/sequence_volume_Netherlands.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Netherlands.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Netherlands.svg" style="width: 2800px;">

### Wales

<img src="plots/sequence_volume_Wales.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Wales.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Wales.svg" style="width: 2800px;">

### Russia

<img src="plots/sequence_volume_Russia.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Russia.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Russia.svg" style="width: 2800px;">

### Denmark

<img src="plots/sequence_volume_Denmark.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Denmark.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Denmark.svg" style="width: 2800px;">

### Germany

<img src="plots/sequence_volume_Germany.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Germany.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Germany.svg" style="width: 2800px;">

### Japan

<img src="plots/sequence_volume_Japan.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Japan.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Japan.svg" style="width: 2800px;">

### Sweden

<img src="plots/sequence_volume_Sweden.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Sweden.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Sweden.svg" style="width: 2800px;">

### Australia

<img src="plots/sequence_volume_Australia.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Australia.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Australia.svg" style="width: 2800px;">

### France

<img src="plots/sequence_volume_France.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_France.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_France.svg" style="width: 2800px;">

### USA

<img src="plots/sequence_volume_USA.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_USA.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_USA.svg" style="width: 2800px;">

### Canada

<img src="plots/sequence_volume_Canada.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Canada.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Canada.svg" style="width: 2800px;">

SARS-CoV-2 sequence data from GISAID EpiCov (bulk .fasta download, 2025-01-13). We gratefully acknowledge all data contributors, i.e. the Authors and their Originating Laboratories responsible for obtaining the specimens, and their Submitting Laboratories that generated the genetic sequence and metadata and shared via the GISAID Initiative the data on which part of this research is based. Lineage assignments were made by Nextclade.

Countries included in the model: Chile, Liaoning, Luxembourg, Taiwan, Hubei, Finland, Shanxi, Heilongjiang, Israel, Slovenia, Ireland, Spain, Brazil, Scotland, Singapore, Italy, England, Netherlands, Wales, Russia, Denmark, Germany, Japan, Sweden, Australia, France, USA, Canada

SARS-CoV-2 lineages included in the model: BA.2, JN.1, KP.1.1.3, KP.2.2, KP.2.3, KP.2.3.12, KP.2.3.4, KP.3, KP.3.1, KP.3.1.1, KP.3.2.3, KP.3.2.6, KP.3.3, KP.3.3.1, KP.3.3.2, KP.3.3.3, KP.3.3.5, KS.1, KS.1.1, KS.1.1.2, LB.1, LB.1.2.2, LB.1.3, LB.1.3.1, LB.1.4, LB.1.7, LF.7, LF.7.1, LF.7.1.3, LF.7.2.1, LF.7.3, LP.1, LP.5, LP.8.1, LP.8.1.1, MC.1, MC.1.1, MC.1.2, MC.1.3, MC.1.3.1, MC.10, MC.10.1, MC.10.2, MC.11, MC.13, MC.13.1, MC.13.2, MC.14, MC.15, MC.16, MC.17, MC.19, MC.2, MC.2.1, MC.20, MC.21, MC.21.1, MC.22, MC.23, MC.24, MC.25, MC.26, MC.26.1, MC.27, MC.28, MC.3, MC.6, MC.8.1, MC.9, MK.1, MV.1, MV.1.1, NB.1, NF.1, NL.2, NL.3, NL.4, NL.5, NP.1, NV.1, XDV.1, XDY, XEC, XEC.1, XEC.11, XEC.12, XEC.13, XEC.14, XEC.15, XEC.16, XEC.2, XEC.2.1, XEC.2.2, XEC.3, XEC.4, XEC.5, XEC.6, XEC.8, XEC.9, XEF, XEK, XEK.1, XEK.1.1, XEK.2, XEK.4, XEL, XEM, XEN, XEQ

## HMC Diagnostics

We show Effective Sample Size (ESS) and plot chains for the global lineage advantage parameters, as well as the inferred frequencies for some time points and some countries.

<img src="plots/ESS_growth_rates.svg" style="width: 2800px;">

<img src="plots/growth_rate_chains.svg" style="width: 2800px;">

<img src="plots/ESS_props_England_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_England_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_England_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_England_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_England_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_England_time100.png" style="width: 2800px;">

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

<img src="plots/ESS_props_USA_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_USA_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_USA_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time100.png" style="width: 2800px;">

Inferred growth advantage mapped upon the Nextclade-curated phylogeny (full tree):

<img src="plots/tree.svg" style="width: 2800px;">

## Methods summary

Lineage competition is modelled using a Bayesian multinomial regression approach. Briefly the global GISAID SARS-CoV-2 dataset (downloaded as a bulk .fasta file) is filtered for any sequences with collection dates within the previous 100 days. NextClade (with the BA.2.86 reference set, “nextstrain/sars-cov-2/BA.2.86”) is used for lineage assignment, and assignments are compiled into counts per country per lineage per day. If a sub-lineage is too infrequent to be included in the model, its count is added into its most recent included ancestor.

We model growth rates using a hierarchical approach. The growth rate for a lineage in a country is the sum of two components: a global rate, and a country-specific random effect. The global rate for each lineage is itself a sum of : i) branch-specific terms, for each branch ancestral to that lineage, plus ii) the sum of terms for "convergent" spike mutations (those occurring on multiple branches of the phylogeny) possessed by that lineage, plus iii) a lineage specific parameter. The rationale for this parameterization is that the contributions of a set of mutations that only occur on a single branch cannot be separated from each other, so those are just bundled into the branch-specific term, but evidence is shared when mutations occur on multiple branches. Further, growth rates are heritable over the phylogeny, and the model's expectation for a new lineage (which may not yet have large sequence volumes) is strongly informed by that of its ancestor's growth rate, since all-but-one of the branch-specific terms are in common, as are (typically) most of the convergent mutation terms. Practically, this is implemented by constructing a large sparse design matrix that encodes which lineages share branches and convergent mutations. Through this, we also allow recombinants to inherit a weighted mixture of their multiple parent's growth terms.

Introduction times are controlled by lineage-specific intercept terms, which have a global shared term per lineage, and country-specific random effects. Each "kind" of parameter has a Gaussian prior, centered on zero, and we use a Gaussian hyperprior over the log of the standard deviations of these priors. Posterior distributions for all parameters are sampled, via Hamiltonian Monte Carlo with the "No-U-Turn sampler" by AdvancedHMC.jl in Julia.

The "Model average" frequency plot intends to provide a "global" image of variant competition, and is produced using the posterior mean (over all post-burnin HMC samples) over all frequency trajectories but with the country-specific terms (including the country-specific growth rate random effects and the country-specific intercepts) set to their averages, no longer reflecting the details of any specific country, but also not being too strongly biased by unevenly distributed sequencing volumes for any specific country.


