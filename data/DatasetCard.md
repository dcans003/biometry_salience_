
# Dataset Title
Biometry Salience and Arthropod Community Dataset

## Dataset Summary
This dataset integrates arthropod community data and plant salience data from ranch sites in San Juanico, Baja California Sur, Mexico. It is designed to evaluate whether culturally relevant plant indicators align with patterns in arthropod abundance across sites.

 ## Data Files
- sample_taxa_matrix_by_ranch_WEIGHTED_REL.csv: Arthropod community data aggregated at the ranch level.
- sample_taxa_matrix_by_trap_WEIGHTED_REL.csv: Arthropod community data aggregated at the trap level.
- salience_plants_personal_use_3_1.csv: Plant salience data derived from interview-based free lists, including salience scores and frequency of mention.

## Data Description
The arthropod datasets contain weighted relative abundance matrices derived from metabarcoding data. Weighting was applied to account for differences in primer performance and to reduce amplification bias across taxa. Data are organized at multiple levels, including by ranch and by individual trap, allowing comparison of community composition across spatial scales.  
The salience dataset contains plant taxa with salience scores, frequency of mention, and normalized salience values (Smith's S).

## Variables
- list: Plant taxon name  
- salience_sum: Total salience score across respondents  
- frequency: Number of respondents mentioning the taxon  
- smith_s: Normalized salience index  

## Data Collection
Arthropods were collected using malaise traps across ranch sites, with two traps per ranch. Samples were processed using metabarcoding techniques, and abundance matrices were generated and weighted to account for primer-specific biases.  
Plant salience data were generated from interview-based free lists, where participants listed culturally relevant plant species. Salience metrics were calculated based on frequency and order of mention across respondents.


 ## Limitations
This dataset represents a single sampling period and may not capture temporal variation. Arthropod data are derived from metabarcoding and may still reflect some methodological bias, even after weighting. Aggregation at the ranch level may obscure fine-scale variation in arthropod communities observed between individual traps, even though trap-level data are available. Salience data reflect currently processed interview responses and will be expanded as additional data are incorporated.
