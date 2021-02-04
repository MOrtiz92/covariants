import { Link } from 'src/components/Link/Link'
import { LinkExternal } from 'src/components/Link/LinkExternal'

## Mutation Information

- <AaMut mut="S:N501"/> has appeared multiple times independently: each can be associated with different accompanying mutations
- Amino-acid changes are <AaMut mut={'S:N501Y'}/> (nucleotide mutation <NucMut mut={'A23063T'}/>), <AaMut mut={'S:N501T'}/> (nucleotide mutation <NucMut mut={'A23064C'}/>), and <AaMut mut={'S:N501S'}/> (nucleotide mutation <NucMut mut={'A23064G'}/>)

### S:N501
This mutation is in the receptor binding domain (RDB), important to ACE2 binding and antibody recognition.

- May be associated with adaptation to rodents and mustelids: <AaMut mut={'S:N501T'}/> in ferrets (<LinkExternal href="https://www.nature.com/articles/s41467-020-17367-2">Richard et al., Nature Comm.</LinkExternal>) and mink (<LinkExternal href="https://academic.oup.com/ve/advance-article/doi/10.1093/ve/veaa094/6025194?searchresult=1">Welkers et al., Virus Evolution</LinkExternal>); <AaMut mut={'S:N501Y'}/> in mice ([Gu et al. Science](https://science.sciencemag.org/content/369/6511/1603)). 
    - Some have speculated on the risk of a possible persistent reservoir in wild rodents/mustelids  
- May increase ACE2 binding ([Bloom Lab ACE2 binding website](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/), [Nelson et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2021.01.13.426558v1)) - in particular it is predicted to do this by increasing the time spent in the 'open' conformation ([Teruel et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2020.12.16.423118v2))
- ACE2 binding may be further increased by the presence of <AaMut mut="S:E484K"/>, and stabilized by the presence of <AaMut mut="S:K417N"/> ([Nelson et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2021.01.13.426558v1))
- <AaMut mut={'S:N501Y'}/> was found in longitudinally-collected samples from an immunocompromised patient (<LinkExternal href="https://www.nejm.org/doi/full/10.1056/NEJMc2031364?query=featured_coronavirus">Choi et al., NEJM</LinkExternal>)
- In one study, sera from previously infected patients neutralised viruses with <AaMut mut="S:501N"/> and <AaMut mut="S:501Y"/> equally ([Xie et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2021.01.07.425740v1))
- Tests in people vaccinated with the Moderna and Pfizer-BioNTech vaccines suggest <AaMut mut={'S:N501Y'}/> and <AaMut mut={'S:E484K'}/> individually, and both together in combination with <AaMut mut={'S:K417N'}/>, cause a small but significant reduction in neutralization ([Wang et al., bioRxiv])(https://www.biorxiv.org/content/10.1101/2021.01.15.426911v2)
- _In vitro_ evolution to select for greater ACE2 binding resulted in mutations <AaMut mut={'S:N501Y'}/>, <AaMut mut={'S:E484K'}/> and <AaMut mut={'S:S477N'}/> to be among the first selected ([Zahradnik et al., bioRxiv](https://doi.org/10.1101/2021.01.06.425392)).

The specific mutation <AaMut mut="S:N501Y"/> is found in 3 variants reported at the end of 2020/beginning of 2021, in:
- the UK (20I/501Y.V1)
- South Africa (20H/501Y.V2)
- Brazil (20J/501Y.V3) 

See a <Link href="/shared-mutations">list of shared mutations</Link> for these variants.

More information on each of these variants can be found below. Smaller clusters of sequences with <AaMut mut="S:N501"/> mutations are also found in Wales, the USA, & Australia.

---

### 20I/501Y.V1
Also known as `B.1.1.7`
Announced on the 14 Dec 2020, appears to have arisen and/or initially expanded in the South East of England.

501Y.V1 is associated with multiple mutations in Spike, including: <AaMut mut={'S:N501Y'}/>, a deletion at 69/70 (as seen in <Var name="S:N439K"/> and <Var name="S:Y453F"/> (<LinkExternal href="https://www.biorxiv.org/content/10.1101/2020.12.14.422555v3">Kemp et al., bioRxiv</LinkExternal>) (<Link href="/variants/S.H69-">see <Var name="S:H69-"/> page</Link>)), as well as <AaMut mut={'S:Y144-'}/> (deletion), and <AaMut mut={'S:P681H'}/> (adjacent to the furin cleavage site).
There is also a notable truncation of <code>ORF8</code>, with <AaMut mut={'ORF8:Q27*'}/> (becomes a stop codon) (deletion of <code>ORF8</code> was previously associated with reduced clinical severity (<LinkExternal href="https://www.thelancet.com/article/S0140-6736(20)31757-8/fulltext">Young et al., Lancet</LinkExternal>)), and mutations in Nucleocapsid: <AaMut mut={'N:D3L'}/> and <AaMut mut={'N:S235F'}/>, as well as a deletion in <code>ORF1a</code>(<code>Nsp6</code>) 3675-3677  (also seen in 501Y.V2 and 501Y.V3).

The 69/70 deletion in this variant causes the S-assay within TaqPath tests to give a negative result, which can provide a useful proxy for prevalence of this variant (a phenomenon referred to as S-gene target failure or SGTF). 

A [small number](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/957504/Variant_of_Concern_VOC_202012_01_Technical_Briefing_5_England.pdf) of 501Y.V1 genomes have been observed in the UK featuring the <AaMut mut={'S:E484K'}/> mutation (see these on the focal <Var name="S:E484"/> Nextstrain build [here](https://nextstrain.org/groups/neherlab/ncov/S.E484?c=gt-S_484&gt=S.484K&label=clade:20I/501Y.V1)). 

Links to papers and reports on 501Y.V1:
- Sera from individuals vaccined with the Moderna vaccine showed no significant reduction of neutralization against 501Y.V1 and a 6-fold reduction in 501Y.V2, but titers remained above levels expected to be protective [Moderna website](https://investors.modernatx.com/news-releases/news-release-details/moderna-covid-19-vaccine-retains-neutralizing-activity-against)
- 40 participants vaccinated with the mRNA BTN162b2 vaccine had "slightly reduced but overall largely preserved neutralizing titers" against 501Y.V1 ([Muik et al., Science](https://science.sciencemag.org/content/early/2021/01/28/science.abg6105.full))
- 501Y.V1 has little reduced neutralization by mAbs and a small reduction to convalescent sera ([Wang et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2021.01.25.428137v2))
- [COG-UK Report](https://www.cogconsortium.uk/news_item/update-on-new-sars-cov-2-variant-and-how-cog-uk-tracks-emerging-mutations/), [Rambaut et al.](https://virological.org/t/preliminary-genomic-characterisation-of-an-emergent-sars-cov-2-lineage-in-the-uk-defined-by-a-novel-set-of-spike-mutations/563), [PHE Technical Briefings 1-5](https://www.gov.uk/government/publications/investigation-of-novel-sars-cov-2-variant-variant-of-concern-20201201)
- Early work suggests a possible increase risk of death with the 501Y.V1 variant ([SAGE Meeting paper 2021/01/21](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/955239/NERVTAG_paper_on_variant_of_concern__VOC__B.1.1.7.pdf))

See a [focal `S.N501` build filtered & zoomed to 501Y.V1](https://nextstrain.org/groups/neherlab/ncov/S.N501?c=gt-S_501&f_clade_membership=20I/501Y.V1&label=clade:20I/501Y.V1&p=grid&r=country)

---

### 20H/501Y.V2
Also known as `B.1.351`
Announced in December 2020, 501Y.V2 originated and/or initially expanded in South Africa ([Tegally et al., medRxiv](https://www.medrxiv.org/content/10.1101/2020.12.21.20248640v1)).

501Y.V2 is associated with multiple mutations in Spike, including: <AaMut mut={'S:N501Y'}/>, <Link href="/variants/S.E484"> <AaMut mut={'S:E484K'}/></Link> (<Link href="/variants/S.E484">see <Var name="S:E484"/> page</Link>), <AaMut mut={'S:K417N'}/>, and <AaMut mut={'S:D80A'}/>.
Additionally, there is a deletion at 242-245.<br/>
There is also a mutation in Nucleocapsid: <AaMut mut={'N:T205I'}/> and a deletion in <code>ORF1a</code>(<code>Nsp6</code>) at positions 3675-3677 (also seen in 501Y.V1 and 501Y.V3).
It does _not_ have the deletion at 69/70.

See a [focal `S.N501` build filtered & zoomed to 501Y.V2](https://nextstrain.org/groups/neherlab/ncov/S.N501?c=gt-S_501&f_clade_membership=20H/501Y.V2&label=mlabel:20C/C23664T&p=grid&r=country)

- Sera from individuals vaccined with the Moderna vaccine showed no significant reduction of neutralization against 501Y.V1 and a 6-fold reduction in 501Y.V2, but titers remained above levels expected to be protective [Moderna website](https://investors.modernatx.com/news-releases/news-release-details/moderna-covid-19-vaccine-retains-neutralizing-activity-against)
- 20H/501Y.V2 is reported to have resistance to monoclonal antibodies and convalescent plasma, with one study finding 93% of 44 plasma samples showed a reduction in titer and 48% had no detectable neutralization activity ([Wibmer et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2021.01.18.427166v1)). A further study also detected reduction in neutralization by convalescent plasma ([Cele et al., medRxiv](https://www.medrxiv.org/content/10.1101/2021.01.26.21250224v1)).
- 501Y.V2 has larger reduction to both mAbs and convalescent sera than 501Y.V1 ([Wang et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2021.01.25.428137v2))

---

### 20J/501Y.V3
Also known as `P.1`
Announced in January 2021, 501Y.V3 originated and/or initially expanded in Brazil ([Faria et al., Virological](https://virological.org/t/genomic-characterisation-of-an-emergent-sars-cov-2-lineage-in-manaus-preliminary-findings/586)), and was particularly associated with Manaus, Amazonas.
It has also been identified in travellers arriving in Japan from Brazil ([English Translation of Japanese NIID report](https://translate.google.com/translate?sl=ja&tl=en&u=https://www.niid.go.jp/niid/ja/diseases/ka/corona-virus/2019-ncov/10107-covid19-33.html), [Naveca et al., Virological](https://virological.org/t/phylogenetic-relationship-of-sars-cov-2-sequences-from-amazonas-with-emerging-brazilian-variants-harboring-mutations-e484k-and-n501y-in-the-spike-protein/585)).

501Y.V3 is associated with multiple mutations in Spike, including: <AaMut mut={'S:N501Y'}/>, <AaMut mut={'S:E484K'}/> (<Link href="/variants/S.E484">see <Var name="S:E484"/> page</Link>), <AaMut mut={'S:K417T'}/>  and <AaMut mut={'S:H655Y'}/>. <br/>
There is also a mutation in Nucleocapsid: <AaMut mut={'N:P80R'}/> and the deletion in <code>ORF1a</code>(<code>Nsp6</code>) at positions 3675-3677 (also seen in 501Y.V1 and 501Y.V2).
It does _not_ have the deletion at 69/70.

See a [focal `S.N501` build filtered & zoomed to 501Y.V3](https://nextstrain.org/groups/neherlab/ncov/S.N501?f_subclade_membership=20J/501Y.V3&label=clade:20J/501Y.V3&p=grid&r=country)

<!--
- N501Y is associated with recently reported 'new variants' in the UK, South Africa, and Brazil:
    - '20B/501Y.V1' (B.1.1.7) was announced in the South East of England on 14 Dec 2020 ([COG-UK Report](https://www.cogconsortium.uk/news_item/update-on-new-sars-cov-2-variant-and-how-cog-uk-tracks-emerging-mutations/), [Rambaut et al.](https://virological.org/t/preliminary-genomic-characterisation-of-an-emergent-sars-cov-2-lineage-in-the-uk-defined-by-a-novel-set-of-spike-mutations/563), [PHE report](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/947048/Technical_Briefing_VOC_SH_NJL2_SH2.pdf)), [PHE Technical Report 2](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/949639/Technical_Briefing_VOC202012-2_Briefing_2_FINAL.pdf), [PHE Technical Report 3](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/950823/Variant_of_Concern_VOC_202012_01_Technical_Briefing_3_-_England.pdf))
        - This particular variant is associated with multiple mutations in Spike, including: `N501Y`, a deletion at 69/70 (as seen in `S:N439K` & `S:Y453F`) ([Kemp et al. bioRxiv (21 Dec)](https://www.biorxiv.org/content/10.1101/2020.12.14.422555v3)), `Y144` deletion, and `P681H` (adjacent to the furin cleavage site).
        - There is also a notable truncation of `ORF8`, with `Q27*` (becomes a stop codon) (deletion of `ORF8` was previously associated with reduced clinical severity ([Young et al. Lancet](https://www.thelancet.com/article/S0140-6736(20)31757-8/fulltext))), and mutations in `N`: `N:D3L` and `S235F`.
    - '20C/501Y.V2' (B.1.351) is found in South Africa and was also announced in December 2020 ([Tegally et al., medRxiv](https://www.medrxiv.org/content/10.1101/2020.12.21.20248640v1))
        - This variant is associated with multiple mutations in Spike, including: `N501Y`, `K417N`, and `D80A`.
        - There is also an `N` mutation: `T205I`.
        - It does _not_ have the deletion at 69/70.
- Smaller clusters also seen in Wales, USA, & Australia
- May be associated with adaptation to rodents and mustelids: `N501T` in ferrets ([Richard et al. Nature Comm.](https://www.nature.com/articles/s41467-020-17367-2)) and mink ([Welkers et al. Virus Evolution](https://academic.oup.com/ve/advance-article/doi/10.1093/ve/veaa094/6025194?searchresult=1)); `N501Y` in mice ([Gu et al. Science](https://science.sciencemag.org/content/369/6511/1603))
    - Some have speculated of risk of a persistent reservoir in wild rodents/mustelids
- May increase ACE2 binding [Bloom Lab ACE2 binding website](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/) - in particular it is predicted to do this by increasing the time spent in the 'open' conformation ([Teruel et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2020.12.16.423118v2))
- `N501Y` was found in longitudinally-collected samples from an immunocompromised patient ([Choi et al. NEJM](https://www.nejm.org/doi/full/10.1056/NEJMc2031364?query=featured_coronavirus))
- In one study, sera from previously infected patients neutralised patients with `S:501N` and `S:501Y` equally ([Xie et al., bioRxiv](https://www.biorxiv.org/content/10.1101/2021.01.07.425740v1))
-->
