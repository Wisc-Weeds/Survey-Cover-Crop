---
title: Survey of Cover Crop Management in Nebraska
author:
  - name: Maxwel C Oliveira 
    affil: 1
    orcid: 0000-0001-5398-1234
  - name: Liberty Butts
    affil: 2  
  - name: Rodrigo Werle *
    affil: 1
affiliation:
  - num: 1
    address: |
      Department of Agronomy -
      University of Wisconsin-Madison, 
      1575 Linden Drive, Madison, WI 53706, USA
#    email: leutnant@fh-muenster.de
  - num: 2
    address: |
      Department of Agronomy and Horticulture -
      University of Nebraska-Lincoln,
      West Central Research and Extension Center, North Platte, NE, USA
#    email: mail@mail.com
# firstnote to eighthnote
#firstnote: |
#  Current address: Updated affiliation
#secondnote: |
#  These authors contributed equally to this work.
correspondence: |
  rwerle@wisc.edu; Tel.: +1-608-262-7130.
journal: agriculture
type: article
status: submit
bibliography: cover.bib
#appendix: appendix.tex
#simplesummary: |
#  A Simple summary goes here.
abstract: |
  Adoption of cover crops has the potential to increase agriculture sustainability in the US and beyond. In 2017, a survey was conducted with Nebraska stakeholders in an attempt to evaluate current cover crop management strategies adopted in soybean (*Glycine max* M), field corn (*Zea mays* L), and seed corn production. Eighty-two Nebraska stakeholders answered the survey, of which 80% identified themselves as growers. Eight-seven % of respondents manage cover crops and the average cover crop ha planted per farm basis is 32%. The primary method of establishing cover crops following soybeans  and field corn is drilling. In seed corn, interseeding is the main seeding strategy for cover crop establishment. Cereal rye (*Secale cereale*) appeared as the most adopted cover crop species (either alone or in mixtures with radish [*Raphanus* spp.] or hairy vetch [*Vicia villosa*]). Over 95% of respondents utilize herbicides for cover crop termination in the spring before crop planting. Glyphosate is used by 100% of survey respondents that use herbicides for cover crop termination. The major observed impacts of incorporating cover crops into a production system according to survey respondents are reduced soil erosion and weed suppression. According to 93% of respondents, cover crop improved weed control by suppressing winter and summer annual weed species. The biggest challenge reported by cover crop adopters is planting and establishing a decent stand before winter. According to the results of this survey, there are different management strategies, positive outcomes, and challenges that accompany cover crop adoption in Nebraska. These results will help growers, agronomists, and researchers better guide cover crops adoption, management, and research needs in Nebraska and beyond.
keywords: |
  Cereal rye (*Secale cereale*), Corn (*Zea Mays* L); Conservation agriculture; Soybean (*Glycine max* M).
acknowledgement: |
  Thanks to the growers and consultants for participating, University of Nebraska-Lincoln (UNL) Extension Educator Keith Glewen for allowing us to conduct this survey, and UNL West Central Research and Extension Center Office Associate Jacqueline Herrick for processing the data.
authorcontributions: |
  R.W. and L.B. conceive and designed the survey; M.O. and R.W. analyzed the data; M.O. and R.W. wrote the paper.
conflictsofinterest: |
  The authors declare no conflict of interest.
#sampleavailability: |
#  Samples of the compounds ...... are available from the authors.
abbreviations:
  - short: US
    long: United States of America
  - short: N
    long: Nitrogen
#  - short: TLA
#    long: Three letter acronym
#  - short: LD 
#    long: linear dichroism
header-includes:
   - \usepackage{threeparttable}
output: rticles::mdpi_article
---

# Introduction

Nebraska is a top field crop producer state in the US. In the last century, the diversity of crops in Nebraska was high in the 1950/60s with corn, sorghum (*Sorghum bicolor*), alfalfa (*Medicago sativa*), wheat (*Triticum aestivum*), oats (*Avena sativa*), and soybean comprising the landscape; however, crop diversity has decreased throughout the decades [@hiller_long-term_2009]. Corn has always been a dominant crop in Nebraska, the state is noticed for being amongst the largest field corn, seed corn, and popcorn producer in the US. Soybean is the second most grown crop in the state, soybean ha increased in Nebraska replacing sorghum and oats after the 1960s [@hiller_long-term_2009]. The summed planted area of corn and soybean in Nebraska was 6,1 million ha in 2018 [@usda-nass_national_2019], which represents 30% of the state territory. 

Corn and soybean rotation is a commonly adopted practice amongst growers, especially in eastern Nebraska. The dependence on corn and soybean rotation, in part, reduced crop diversity and imposed a strong selection pressure on Nebraska's agroecosystems. As a result, pests outbreaks and N runoff [@eghball_long-term_2002] are some of the issues of Nebraska agriculture. Integrated crop, nutrient and pest management strategies have been recommended to increase sustainability in agroecossystems [@wu_integrated_2015; @mcdaniel_does_2014]. Amongst the sustainable strategies, conservation practices, including no-till and cover crops, gained growers interest and adoption in the last decades [@knowler_farmers_2007; @baumgart-getz_why_2012].

The use of glyphosate and wide adoption of glyphosate resistant crops (e.g., corn and soybean) strongly contributed for the shift of conventional tillage to no-till cropping systems [@duke_glyphosate:_2008]. It is estimated that over 50% of growers in the US Midwest have adopted no-till as a standard practice [@givens_survey_2009]. The benefits of using conservation practices has led growers to increased interest in cover crops [@bergtold_demographic_2012]. However, in Nebraska and across the upper US Midwest, growers are facing challenges to implement cover crops in their systems. Some of the challenges for cover crops adoption include short growing season window, cover crop selection, planting, termination strategy, termination timing, and farm operational factors [@sarrantonio_role_2003; @dunn_perceptions_2016]. 

A well-established cover crops stand can provide several benefits to agroecosystems, including reduced soil erosion, increased soil health, and weed management [@blanco-canqui_cover_2015; @bergtold_review_2017]. For example, it is estimated that the use of cover crops in the Midwest has the potential to reduce 20% of NO~3~ in the Mississippi River [@kladivko_cover_2014]. On a recent survey, cover crops were listed as the fifth on priority weed research and extension in Nebraska [@sarangi_statewide_2018]. Therefore, there is a need to document Nebraska growers' experiences and perceptions regarding cover crops and surveys can be useful method for obtaining these informations. Also, survey results can demonstrate opportunities and challenges to guide future research, extension, education, and improve the grower decision making process. 

Surveys have become an important tool to evaluate and document trends in agriculture. For example, several surveys have documented the impact of tillage [@givens_survey_2009], pesticide application [@culpepper_glyphosate-induced_2006; @bish_survey_2017; @werle_survey_2018-1], and weed management [@werle_survey_2018; @sarangi_statewide_2018] in the US Midwest. Surveys have documented the adoption of cover crops in the US [@singer_are_2007; @singer_corn_2008]. For example, it was showed that crop diversity in a farm operation was the most important factor for cover crop adoption [@singer_are_2007]. Therefore, a cover crop survey focused on agronomic practices was conducted with Nebraska stakeholders (growers, agronomists, industry representatives, and crop consultants). The objective of the survey was to evaluate cover crop management strategies adopted by Nebraska soybean, field corn and seed corn stakeholders.


# Materials and Methods

A paper copy survey was handed out during the 2017 Cover Crops Conference at the Eastern Nebraska Research and Extension Center, Ithaca, NE on February 14, 2017. The survey comprised eight sections (Figure 1). Questions focused on the respondent demographics (Q1-4, Figure 1A); cover crop management during corn (Q5-7, Figure 1B), seed corn (Q8-10, Figure 1C), and soybean growing season (Q11-13, Figure 1D); cover crop management going into a corn (Q14-15, Figure 1E), seed corn (Q16-17, Figure 1F), and soybean (Q18-19, Figure 18-19) growing season; and general questions about cover crop management in Nebraska (Q20-24).

For most questions, results are presented in two fashions: (1) percent of respondents answering, and (2) percent number of hectares represented. Survey data were sorted, filter and analyzed using the *pipe*, *select*, *filter*, *summarise*, and *count* of tidyverse [@wickham_tidyverse:_2017] package of R Core Team [@r_r:_2019]. 

\begin{figure}[H]
\centering
\includegraphics[width=14 cm]{Survey.png}
\caption{The survey questionnaire conducted with 82 individuals during the 2017 Cover Crops Conference (February 14, 2017), held at the Eastern Nebraska Research and Extension Center, Ithaca, NE.}
\end{figure}

# Results and Discussion

## Demographics

A total of 82 individuals primarily from eastern part of Nebraska where soybean and corn are the major crops participated in the survey. Sixty-six respondents identified themselves as growers (80%) and seven as consultants, industry representative or agronomists (9%). The majority (87%) of respondents integrate cover crops in their cropping systems (n=82). The total area managed by respondents in this survey was 149370 ha, with 24240 ha planted with cover crops, representing 16% of total managed area. 

Most of survey respondents manage cover crops in eastern Nebraska, with 18990 ha of cover crops managed by growers. Nearly 50% of cover crops ha managed by survey respondents indentified as growers are located in Butler County, Nebraska (Figure 2). Respondents reported managing cover crops on 32% on their ha basis, varying from 2.5 to 100% of their farm ha.

From 2001 to 2005, 11% of corn belt growers adopted cover crops [@singer_corn_2008]. In an early 2000s survey, over 50% of growers would have planted cover crops if cost-sharing was available [@singer_are_2007]. Recently, a survey with 2012 growers across the US indicated that 88% of respondents planted cover crops in 2016 [@ctic_report_2017]. The survey also showed that the area planted with cover crops increased nearly 60% from 2014 to 2016. Although these data originated from different surveys, there is a clear growing trend of cover crops adoption in the US. The rise of cover crop adoption is possible due to combination of several factors, such as increase crop diversity, popular pressure for adoption of sustainable production, cost reduction, and policy incentives (e.g. government cost-sharing and conservation programs). Further research is necessary to address the impacts of increase cover crops adoption in the US cropping-systems. 

\begin{figure}[H]
\centering
\includegraphics[width=15 cm]{map.png}
\caption{Map of Nebraska counties with the sum of total cover crops ha managed by survey respondents identified as growers. Dark purple color represents Butler County, where the Cover Crops Conference took place in Ithaca, NE.}
\end{figure}


## Cover Crops Establishment
 
According to survey respondents, cover crops establishment in Nebraska varied with cropping-system. In soybean seasons, 27% of survey respondents seed their cover crops prior to soybean harvest while 73% seed after crop harvest (n=56, Table 1A). Drilling after crop harvest is the main method of cover crops establishment in soybean years (72%, Table 1B), followed by aerial seeding (28%, n=53). No respondents interseed cover crops in soybean. Cereal rye (*Secale cereale*) is used by 43% while a cover crops mix (cereal rye plus oats [*Avena sativa*], radish [*Raphanus spp.*], and/or hairy vetch [*Vicia villosa*]) is used by 57% of the respondents (n=57, Table 1C). 

\begin{table}[H]
\caption{Cover crops management strategies in Nebraska according to survey respondents of Nebraska}
\centering
%%\tablesize{} %% You can specify the fontsize here, e.g.  \tablesize{\footnotesize}. If commented out \small will be used.
\footnotesize{\scriptsize}
\begin{threeparttable}
\begin{tabular}{lccc}
\toprule
\textbf{}	& \textbf{Soybean}	& \textbf{Field Corn} & \textbf{Seed Corn}\\
\midrule
              		  &     	  & \%	    &   \\ \cline{2-4}
\textbf{A. Seeding Time}		  &     	  &           &   \\
prior crop harvest	& 27			& 27        & 85\\
after crop harvest  & 73      & 73        & 15\\
n\tnote{1}                   & 56	    & 59	      & 13\\ \hline
\textbf{B. Seeding strategy} &     	  &           &   \\
      interseed	    & 0	      & 8	        & 77\\
      aerial	      & 28	    & 26	      & 15\\
      drill	        & 72	    & 66	      & 8\\
n                   & 53	    & 61	      & 13\\ \hline
\textbf{C. Cover crops selection} &     	  &       &   \\
cereal rye	        & 43	    & 47      	& 0\\
multiple species mix\tnote{2}	& 57	  & 53	      & 100\\
n                   & 47	    & 62	      & 13\\ \hline
\textbf{D. Cover crops termination time} &     	  &       &   \\
two weeks	          & 46	    & 73	      & 100\\
one week	          & 26      &	12	      & 0\\
at planting	        & 28	    & 15        &	0\\
n                   & 35	    & 40	      & 7\\ \hline
\textbf{E. Cover crops termination strategy} &     	&       &   \\
herbicides	        & 96	    & 95	      & 100\\
non-herbicides	    & 4	      & 5	        & 0\\
n                   & 46	    & 55	      & 11\\
\bottomrule
\end{tabular}
\begin{tablenotes}
\item[1]n: number of respondents. \\
\item[2]multiple species mix: cereal rye plus oats, radishes, turnips, and/or hairy vetch.
\end{tablenotes}
\end{threeparttable}
\end{table}


In field corn seasons, 27% of respondents seed cover crops prior to corn harvest while 73% seed after crop harvest (n=59, Table 1A). Drilling after corn harvest is the main strategy for planting cover crops (66%) followed by aerial seeding (26%, typically done when crop reaches maturity), and interseeding (8%, n=61, Table 1B). Cereal rye is used by 47% of the respondents, while a mix of species was used by 53% (cereal rye plus radishes, and/or vetch, n=62, Table 1C).

In field corn and soybean, drilling cover crops after crop harvest in the fall is a common management strategy amongst survey respondents in Nebraska. Drilling cover crops has long been a management strategy in the US Midwest. In the 2000s, a survey in Illinois, Indiana, Iowa and Minnesota showed that nearly 70% of cover crops growers establish cover crops using drill after crop harvest [@singer_corn_2008]. The desired seed and soil contact for plant germination is the main benefit of drilling cover crops after crop harvest [@richard_direct_1995].  Despite drilling after harvest being a common practice, researchers have demonstrated the value of aerial seeding or interseeding cover crops prior to crop harvest [@noland_establishment_2018; @youngerman_corn_2018]. A benefit of aerial seeding or interseeding is earlier cover crops establishment, especially brassicas and legume species, which require earlier planting to produce satisfactory amount of biomass.

Eighty-five percent of survey respondents seed cover crops prior to seed corn harvest while 15% plant after harvest (n=13, Table 1A), which is a different strategy from soybean and field corn seasons. Interseeding cover crops is the main seeding practice in seed corn years (77%), followed by aerial seeding (15%) and drilling (8%, n=13, Table 1B). Interseeding cover crops after field corn male rows destruction benefits the establishment of cover crops, especially legumes and brassicas. As a result, a mix of species is used by 100% of the respondents in seed corn systems (radishes, turnips [*Brassica rapa*] and cereal rye mix, n=13, Table 1C).

A standard practice amongst survey respondents is planting cereal rye alone or in mixtures with brassicas and/or legumes as cover crops in soybean, field corn, and seed corn. The use of cover crops mixtures is likely to increase agroecosystem diversity, but may not provide benefits beyond cover crops monocultures [@appelgate_cover_2017]. It was documented that cereal rye and cereal rye mixtures (brassicas and legumes) produced the highest biomass compared to other cover crops monocultures, and cereal rye in mixtures accounted for nearly 80% of spring biomass [@appelgate_cover_2017]. 

In general, cereals (e.g., oats and rye) and legumes (e.g., hairy vetch and crimson clover) are a good combination for producing large amounts of biomass cover and N-fixing, respectively. The seed mixture proportion would depend on the ultimate goal when managing cover crop. For example, with cereal rye/hairy vetch mixtures, it is recommended higher proportion of the cereal for soil cover and weed management but higher hairy vetch for N accumulation in the soil [@hayden_ryevetch_2014]. 

## Cover Crops Termination and Herbicide Program

Survey respondents were asked when and how they terminate cover crops when soybean, field corn, and seed corn are planted as the subsequent crop. One-hundred percent terminate cover crops two weeks prior seed corn planting (n=7, Table 1D), whereas 73% and 46% of respondents adopt such practice when field corn and soybeans are planted as the subsequent crop, respectively. Terminating cover crops at least two weeks prior to planting is a commonly recommended practice [@nascente_cover_2013]. For example, herbicide applications early April rather than early May provided the best control of winter wheat (*Triticum aestivum*), cereal rye, annual ryegrass (*Lolium multiflorum*), crimson clover (*Trifolium incarnatum*), hairy vetch, and Austrian winter pea (*Pisum sativum*) cover crops [@cornelius_herbicide_2017]. However, early terminated cover crops may not yield significant amounts of biomass in the spring. High cover crops biomass is needed for weed suppression and for proving N to the agroecosystem [@marcillo_corn_2017]. It was reported that delaying extra two weeks for spring termination of hairy vetch in late April produced significantly increased N for the subsequent crop [@sainju_tillage_2001]. Therefore, there is trade-off when deciding the timing for cover crops termination, which depends on grower's primary goal for the cover crops.

Termination is an important component for integrating cover crops in cropping-systems. Despite non-chemical strategies for terminating cover crops, including tillage and roller crimper [@mirsky_control_2009; @wortman_optimizing_2012; @bavougian_cover_2018; @frasconi_combining_2019], more than 95% of survey respondents use herbicides (Table 1E). Therefore, it is likely the majority of survey respondents manage conventional cropping-systems (e.g., no organic farmers represented in the survey). When herbicides are used, 100% of survey respondents spray glyphosate, alone (44%) or in mixtures (56%; n=66, Figure 3A). Glyphosate tank mixes with 2,4-D, 2,4-D + paraquat (e.g., Gramoxone\textsuperscript \textregistered), glufosinate (e.g., Liberty\textsuperscript \textregistered), and other herbicides (e.g., saflufenacil [Sharpen\textsuperscript \textregistered], carfentrazone [Aim\textsuperscript \textregistered]) are used by 41%, 9%, 3%, and 3% of the survey respondents, respectively. 

\begin{figure}[H]
\centering
\includegraphics[width=15 cm]{Combined.png}
\caption{Herbicide programs used for cover crops termination (\textbf{A}) and timing for preemergence herbicide application (\textbf{B}) according to Nebraska survey respondents.}
\end{figure}

Our survey shows a strong reliance of Nebraska growers on glyphosate for cover crops termination. The use of glyphosate alone may not provide effective cover crops termination, especially cover crops at advanced stages and when cover crops mixtures are present. It was documented that glyphosate alone provided nearly complete cereal rye control, but poor Austrian winterpea, crimson clover, and hairy vetch control [@palhano_evaluation_2018]. The enhanced control of cover crop mixtures occur when glyphosate is tank-mixed with other herbicides. For example, glyphosate tank-mixed with 2,4-D or dicamba provided nearly 30% higher hairy vetch control than glyphosate alone [@cornelius_herbicide_2017]. These results highlight that when growers use herbicide for terminating cover crops, glyphosate is a excellent option for cereal rye monoculture, but glyphosate tank-mixes with other herbicide site of action is a better option when legumes and other species (e.g., winter annual weed species) are established.

The use of pre-emergent (PRE) herbicides is a commonly strategy for weed management in Nebraska. The most common PRE herbicide treatment used by Nebraska growers at planting is atrazine + mesotrione + *S*-metolachor and cloransulan-methyl + sulfentrazone for corn and soybean, respectively [@sarangi_statewide_2018]. Forty-four percent of survey respondents apply PRE herbicides at cover crops termination and crop planting, 33% at cover crops termination, 21% at crop planting, and only 2% do not use PRE herbicides (n=48, Figure 3B). However, cover crop residue may intercept PRE herbicides, reducing their effectiveness [@christoffoleti_conservation_2007]. For example, when not reaching the soil, any herbicide may dissipate (volatilization), and/or degrade (photo or microorganisms). When using cover crops and PRE-herbicides, a timely rainfall is needed for herbicide incorporation and activation in soils [@khalil_rainfall_2019]. Nonetheless, well established cover crops supress weeds and PRE herbicides with rainfall may provide long soil residual activity, which aid to control early and late germinating weed species. 

## Impact of Cover Crops in Production Systems

Cover crops have the potential to provide direct and indirect benefits to cropping-systems (e.g., increase soil organic matter and soil erosion reduction). However, measuring the cover crops services to agroecosystems is difficult [@bergtold_review_2017]. In Nebraska, most of survey respondents reported that the major benefit of cover crops is soil erosion reduction (45%, n=42, Figure 4). Cover crop roots and aboveground biomass function as a physical barrier against rainfall and wind, which reduce soil erosion [@blanco-canqui_cover_2015; @lu_cover_2000]. The cover crops residue on cropland production areas is likely the main visible benefit provided by cover crops.

\begin{figure}[H]
\centering
\includegraphics[width=12 cm]{Majorchangeflip.png}
\caption{Major observed change(s) after adoption of cover crops in agroecosystems according to Nebraska survey respondents.}
\end{figure}

The increased soil organic matter (24%), increased soil tilth (19%), and increased soil water infiltration (10%) are also perceived services that cover crops provide to Nebraska cropping-systems (Figure 4). These services increase soil health, but their benefits would occur with the long-term adoption of cover crops [@bergtold_review_2017]. Although legume cover crops can provide significant amounts of N-enriched biomass [@blanco-canqui_summer_2012], only five percent of survey respondents mentioned that cover crops improved soil fertility in their operations. The N accumulation is strongly correlated to the amount of legume biomass [@blanco-canqui_cover_2015], which depends on stand, winter overkill, and termination timing. 

After reduced soil erosion, weed suppression was the second most common reported benefit of cover crops according to survey respondents in Nebraska (29%, Figure 4). A meta-analysis reported that cover crops can provide early season weed control comparable to chemical and mechanical weed control strategies [@osipitan_cover_2018]. For example, cereal rye used as cover crops reduced density and biomass of henbit (*Lamium amplexicaule*) and horseweed (*Conyza canadensis*) by 90% in Nebraska [@werle_cereal_2017]. Also, cereal rye provided near 85% suppression of Palmer amaranth (*Amaranthus palmeri*) in cotton [@palhano_cover_2018]. Horseweed and Palmer amaranth represent two of the most difficult to control weed species, mostly because of herbicide resistance evolution [@oliveira_interspecific_2018]. Therefore, well established cover crops have the potential to suppress hard to control weed species in Nebraska and beyond. Additional described benefits were reduced pesticide use, increased grazing, and uniform yields (2%). A few respondents reported reduced crop yields and increased erosion where cover crops have been adopted as negative impacts of cover crops adoption (2%; Figure 4). 

Ninety-three percent of survey respondents answered that cover crop adoption improved weed control in their operations (n=54, Figure 4A). According to survey respondents, the most effective weeds that cover crops enchanced control were winter annual (79%), followed by late-season summer annual (55%), and early-season summer annual (26%, n=38, Figure 4B). Cover crops promote direct competition with winter annuals and suppression of summer annual weed species via residue. Therefore, cover crops have the potential to supress common weed species present in Nebraska cropping-systems, including downy brome (*Bromus tectorum*), horseweed, waterhemp (*Amranthus tuberculatus*), Palmer amaranth, and giant ragweed (*Ambrosia trifida*) [@werle_predicting_2014; @werle_environmental_2014].

\begin{figure}[H]
\centering
\includegraphics[width=15 cm]{Combined2.png}
\caption{Cover crops improved weed control (\textbf{A}) and groups of annual weed species supressed by cover crops (\textbf{B}) according to Nebraska survey respondents.}
\end{figure}

## Challenges With Cover Crops Incorporation 

According to survey respondents that adopt cover crops, the biggest challenge has been planting and establishing stands before winter due to short growing season, time and/or equipment availability (56%, Figure 5). In the upper US Midwest, the lack of growing season left after crop harvest, timely rainfall events, and winter kill are the main constraints for cover crops establishment in the fall. Moreover, planting cover crops often requires extra equipments [@bergtold_review_2017], especially when incorporating cover crops before crop harvest. For example, the absence of adequate planting method (e.g., lack of reliance, cost for flying, and poor seed and soil contact) that provide good cover crops stand without cash crops damage are the main challenges implementing cover crops during the growing season.  

\begin{figure}[H]
\centering
\includegraphics[width=12 cm]{Challenge.png}
\caption{Challenges for adopting cover crops according to survey respondents of Nebraska.}
\end{figure}

Termination of cover crops in the spring was ranked as the second biggest challenge (37%, Figure 5). A poorly controlled cover crop could become a weed problem, reducing subsequent crop establishment and yield potential. In addition, late terminated cover crops are likely to increase insect pest pressure [@mcmechan_wheat_2018-1] and host seedling pathogens [@timper_reproduction_2006; @bakker_potential_2016]. The incidence of seedling disease (e.g., *Pythium* spp.) and low corn emergence occurred when cover crops (winter rye) was late terminated [@acharya_time_2017].

The use of soil residual herbicides for weed control in Nebraska is a barrier for cover crop (eg., brassica and radish) establishment in the fall according to 7% of survey respondents (Figure 4B). For enhancing waterhemp and Palmer amaranth control, growers are advised to overlap soil residual tank mixed with other POST herbicides. Depending on weather, some herbicides can have extended residual activity in the soil and cause cover crops failure. For example, herbicide products commonly used in corn and/or soybeans, such as pyroxasulfone, imazethapyr, fomesafen, and flumetsulan, are likely to cause negative impact on cover crops establishment in the fall [@cornelius_carryover_2017]. 

The costs for incorporating cover crops is a challeng for 5% of survey respondents. The cost is mostly linked to cover crops seeds. Nearly 50% of cover crop growers paid from $25 to 50 ha^-1^ for cover crop seeds [@ctic_report_2017]. Higher seed costs are associated with the inclusion of legume species in the mix. However, growers can obtain a return on the investment by using cover crops as forages, reduce the amount of fertilizer by using cover crops to cycle nutrients, and to suppress weeds in their operation (e.g., reduced herbicide reliance). It is documented that growers that received government cost-share and used cover crops for livestock grazing or forage tipically derived positive net returns from cover crops [@plastina_perceived_2018]. Other benefts such as increased soil health and reducing farming inputs are difficult to measure and likely to be viewed as long-term investiment [@bergtold_review_2017]. The profitability of cover crops weights according to the ultimate goal of cover crops growers. 

Two percent of survey respondents reported crop yield reduction when adopting cover crops (Figure 6). A meta-analysis over 65 years of research showed that if properly managed, fall-seeded cover crops do not reduce corn yields [@marcillo_corn_2017]. For example, the incorporation of fall planted cereal rye after corn harvested in rotation with soybean resulted in comparable soybean yields where no cover crops were grown [@de_bruin_use_2005]. Therefore, cover crops should not reduce yields if managed according to the best management practices, especially the timely termination prior to crop establishment. 

# Conclusion

The adoption of cover crops is increasing across Nebraska and the US. There are many ways cover crops can be incorporated in cropping-systems and the results of this survey highlight the main strategies, benefits, and challenges observed by cover crops adopters in Nebraska. When deciding how best to use cover crops, it is important to consider the ultimate goal. The goal could be increased soil organic matter, increased nutrient availability to subsequent crops, reduce soil compaction, supply forage for livestock, and/or suppress weeds. Answering these questions will help identify the cover crops strategies that offer the best chance of success for meeting the goal.
