# SARS-CoV-2 Lineage Competition (2025-09-21)

Results from a model of global SARS-CoV-2 lineage competition

Estimates of multiplicative growth advantage (per week) for lineages are provided, both relative to the basal BA.2, and to the recently-dominant LP.8.1.1.

## Advantage Estimates

<img src="plots/all_lineages_MCMC_lineage_growths.svg" style="width: 2800px;">

<img src="plots/pruned_lineages_MCMC_lineage_growths.svg" style="width: 2800px;">

<img src="plots/N_MCMC_mutations.svg" style="width: 2800px;">

Inferred growth advantage mapped upon the Nextclade-curated phylogeny (pruned to keep only relatively competative variants):

<img src="plots/tree_pruned.svg" style="width: 2800px;">

## Variant trajectories

For countries with more than 200 genomes deposited in the last 50 days, we plot the model trajectory estimates and forecasts. Forecasts for variants where the sampled genomes fall off prior to variant emergence are driven by global pooled estimates and should be treated with caution.

Bayesian 95% Credible Intervals are shown for: BA.2, LP.8.1, LP.8.1.1, NB.1.8.1, PE.1.4, PF.2, PQ.1, PQ.17, PQ.2, XFG, XFG.14.1, XFG.2, XFG.3, XFG.3.1, XFG.3.15, XFG.3.4, XFG.3.4.1, XFG.3.4.2, XFG.3.4.3, XFG.4.1, XFG.5.1, XFG.5.2, XFG.6, XFG.8, XFG.9.1, XFG.9.3, XFV

Variants are colored (from blue to red) in order of the number (low to high) of convergent mutations they exhibit (ie. those in mutation plot above).

### Model Average

Averaging out the country-specific growth rate and intercept adjustments:

<img src="plots/variant_trajectories_model_avg.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_model_avg.svg" style="width: 2800px;">

### Italy

<img src="plots/sequence_volume_Italy.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Italy.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Italy.svg" style="width: 2800px;">

### Germany

<img src="plots/sequence_volume_Germany.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Germany.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Germany.svg" style="width: 2800px;">

### Japan

<img src="plots/sequence_volume_Japan.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Japan.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Japan.svg" style="width: 2800px;">

### Brazil

<img src="plots/sequence_volume_Brazil.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Brazil.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Brazil.svg" style="width: 2800px;">

### Wales

<img src="plots/sequence_volume_Wales.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Wales.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Wales.svg" style="width: 2800px;">

### England

<img src="plots/sequence_volume_England.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_England.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_England.svg" style="width: 2800px;">

### France

<img src="plots/sequence_volume_France.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_France.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_France.svg" style="width: 2800px;">

### Scotland

<img src="plots/sequence_volume_Scotland.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Scotland.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Scotland.svg" style="width: 2800px;">

### Australia

<img src="plots/sequence_volume_Australia.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Australia.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Australia.svg" style="width: 2800px;">

### Canada

<img src="plots/sequence_volume_Canada.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Canada.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Canada.svg" style="width: 2800px;">

### Spain

<img src="plots/sequence_volume_Spain.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Spain.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Spain.svg" style="width: 2800px;">

### USA

<img src="plots/sequence_volume_USA.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_USA.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_USA.svg" style="width: 2800px;">

### Sweden

<img src="plots/sequence_volume_Sweden.svg" style="width: 2800px;">

<img src="plots/muller_trajectories_country_Sweden.svg" style="width: 2800px;">

<img src="plots/variant_trajectories_Sweden.svg" style="width: 2800px;">

SARS-CoV-2 sequence data from GISAID EpiCov (bulk .fasta download, 2025-09-21). We gratefully acknowledge all data contributors, i.e. the Authors and their Originating Laboratories responsible for obtaining the specimens, and their Submitting Laboratories that generated the genetic sequence and metadata and shared via the GISAID Initiative the data on which part of this research is based. Lineage assignments were made by Nextclade.

Countries included in the model: Hubei, Romania, Taiwan, Sweden, Ukraine, Denmark, Singapore, Ireland, Netherlands, Italy, Germany, Japan, Brazil, Wales, England, France, Scotland, Australia, Canada, Spain, USA

SARS-CoV-2 lineages included in the model: BA.2, JN.1.16.5, LP.8.1, LP.8.1.1, LP.8.1.4, NB.1.8.1, NW.1.2, NW.1.2.1, NW.1.2.2, NY.13, NY.15, NY.15.1, NY.16, NY.18, NY.20, NY.24, NY.3, NY.3.3, NY.7.1, NY.9, PD.1, PE.1.4, PF.2, PG.3.1, PQ.1, PQ.1.2, PQ.1.5, PQ.10, PQ.10.1, PQ.11, PQ.12, PQ.13, PQ.14, PQ.17, PQ.17.1, PQ.17.2, PQ.2, PQ.2.1, PQ.2.4, PQ.2.5, PQ.3, PQ.31, PQ.4, PQ.5, PQ.6, PQ.7, PQ.8, PQ.8.1, PY.1.1.1, QF.1, QK.1, XFC, XFC.1, XFC.1.1, XFC.3, XFG, XFG.1, XFG.10, XFG.10.1, XFG.14, XFG.14.1, XFG.16, XFG.2, XFG.2.2, XFG.21, XFG.22, XFG.23.1, XFG.26, XFG.28, XFG.29, XFG.3, XFG.3.1, XFG.3.1.1, XFG.3.10, XFG.3.12.1, XFG.3.13, XFG.3.15, XFG.3.16, XFG.3.17, XFG.3.4, XFG.3.4.1, XFG.3.4.2, XFG.3.4.3, XFG.3.6, XFG.3.7, XFG.3.8, XFG.3.9, XFG.30, XFG.31, XFG.4, XFG.4.1, XFG.4.2, XFG.5, XFG.5.1, XFG.5.2, XFG.6, XFG.7, XFG.8, XFG.9, XFG.9.1, XFG.9.3, XFG.9.4, XFJ, XFJ.1, XFJ.3, XFN.1, XFV

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

<img src="plots/ESS_props_USA_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_USA_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_USA_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_USA_time100.png" style="width: 2800px;">

<img src="plots/ESS_props_Sweden_time1.svg" style="width: 2800px;">

<img src="plots/Chain_props_Sweden_time1.png" style="width: 2800px;">

<img src="plots/ESS_props_Sweden_time50.svg" style="width: 2800px;">

<img src="plots/Chain_props_Sweden_time50.png" style="width: 2800px;">

<img src="plots/ESS_props_Sweden_time100.svg" style="width: 2800px;">

<img src="plots/Chain_props_Sweden_time100.png" style="width: 2800px;">

Inferred growth advantage mapped upon the Nextclade-curated phylogeny (full tree):

<img src="plots/tree.svg" style="width: 2800px;">

## Methods summary

Lineage competition is modelled using a Bayesian multinomial regression approach. Briefly the global GISAID SARS-CoV-2 dataset (downloaded as a bulk .fasta file) is filtered for any sequences with collection dates within the previous 100 days. NextClade (with the BA.2.86 reference set, “nextstrain/sars-cov-2/BA.2.86”) is used for lineage assignment, and assignments are compiled into counts per country per lineage per day. If a sub-lineage is too infrequent to be included in the model, its count is added into its most recent included ancestor.

We model growth rates using a hierarchical approach. The growth rate for a lineage in a country is the sum of two components: a global rate, and a country-specific random effect. The global rate for each lineage is itself a sum of : i) branch-specific terms, for each branch ancestral to that lineage, plus ii) the sum of terms for "convergent" spike mutations (those occurring on multiple branches of the phylogeny) possessed by that lineage, plus iii) a lineage specific parameter. The rationale for this parameterization is that the contributions of a set of mutations that only occur on a single branch cannot be separated from each other, so those are just bundled into the branch-specific term, but evidence is shared when mutations occur on multiple branches. Further, growth rates are heritable over the phylogeny, and the model's expectation for a new lineage (which may not yet have large sequence volumes) is strongly informed by that of its ancestor's growth rate, since all-but-one of the branch-specific terms are in common, as are (typically) most of the convergent mutation terms. Practically, this is implemented by constructing a large sparse design matrix that encodes which lineages share branches and convergent mutations. Through this, we also allow recombinants to inherit a weighted mixture of their multiple parent's growth terms.

Introduction times are controlled by lineage-specific intercept terms, which have a global shared term per lineage, and country-specific random effects. Each "kind" of parameter has a Gaussian prior, centered on zero, and we use a Gaussian hyperprior over the log of the standard deviations of these priors. Posterior distributions for all parameters are sampled, via Hamiltonian Monte Carlo with the "No-U-Turn sampler" by AdvancedHMC.jl in Julia.

The "Model average" frequency plot intends to provide a "global" image of variant competition, and is produced using the posterior mean (over all post-burnin HMC samples) over all frequency trajectories but with the country-specific terms (including the country-specific growth rate random effects and the country-specific intercepts) set to their averages, no longer reflecting the details of any specific country, but also not being too strongly biased by unevenly distributed sequencing volumes for any specific country.


