/Users/pma/Dropbox/git_repos/mandelbrot_project/met_annot_enhancer

    Fetching the GNPS job: 71042c319fa444d088e3704141a96354
    
--2024-05-23 13:52:27--  https://gnps2.org/taskzip?task=71042c319fa444d088e3704141a96354
Resolving gnps2.org (gnps2.org)... 169.235.26.137
Connecting to gnps2.org (gnps2.org)|169.235.26.137|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘/Users/pma/Dropbox/git_repos/COMMONS_Lab/EMI/fibl-metabolomics/docs/fibl-pilot/pos/results/met_annot_enhancer/71042c319fa444d088e3704141a96354.tar’

/Users/pma/Dropbox/git_repos/COMMONS_Lab/EMI/f     [                                                <=>                                                  ]  29.08M  1.50MB/s    in 12s     

2024-05-23 13:52:40 (2.38 MB/s) - ‘/Users/pma/Dropbox/git_repos/COMMONS_Lab/EMI/fibl-metabolomics/docs/fibl-pilot/pos/results/met_annot_enhancer/71042c319fa444d088e3704141a96354.tar’ saved [30494720]


    Job successfully downloaded: results are in: /Users/pma/Dropbox/git_repos/COMMONS_Lab/EMI/fibl-metabolomics/docs/fibl-pilot/pos/results/met_annot_enhancer/71042c319fa444d088e3704141a96354
    

Parameters used are stored in /Users/pma/Dropbox/git_repos/COMMONS_Lab/EMI/fibl-metabolomics/docs/fibl-pilot/pos/results/met_annot_enhancer/fibl_pilot_pos/71042c319fa444d088e3704141a96354.yaml

    Proceeding to spectral matching ...
    
5667 spectra were found in the query file.
They will be matched against the 289429 spectra of the spectral library.
Cleaning the spectral database metadata fields ...
The spectral library is already cleaned.
Proceeding to the spectral match ...
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 40186/40186 [00:06<00:00, 6177.49it/s]
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 35317/35317 [00:03<00:00, 9599.29it/s]
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 43331/43331 [00:03<00:00, 13881.21it/s]
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 40611/40611 [00:03<00:00, 12741.74it/s]
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 45007/45007 [00:03<00:00, 12939.43it/s]
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 28866/28866 [00:02<00:00, 13248.90it/s]
Finished in 117.51603102684021 seconds.
You can check your results in here /Users/pma/Dropbox/git_repos/COMMONS_Lab/EMI/fibl-metabolomics/docs/fibl-pilot/pos/results/met_annot_enhancer/fibl_pilot_pos/fibl_pilot_pos_spectral_match_results.tsv

    Spectral matching done !
    
Number of features: 5667
Number of MS2 annotation: 54632

    Importing MS1 adducts file
    
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 5667/5667 [00:45<00:00, 125.49it/s]

    MS1 annotation done !
    
Number of annotated features at the MS1 level : 5520
Total number of unique MS1 and MSMS annotations: 536309
Total number of annotations with unique biosource per line: 2325320
21 unique species have been selected from the metadata table.

    Fetching the biosource contribution per feature ...
    

    Proceeding to taxonomically informed reponderation ...
    
Total number of annotations after filtering MS1 annotations not reweighted at the minimal taxonomical level: 282096
Number of annotations reweighted at the domain level: 252746
Number of annotations reweighted at the kingdom level: 219651
Number of annotations reweighted at the phylum level: 216818
Number of annotations reweighted at the class level: 199748
Number of annotations reweighted at the order level: 93855
Number of annotations reweighted at the family level: 90357
Number of annotations reweighted at the tribe level: 15033
Number of annotations reweighted at the genus level: 7473
Number of annotations reweighted at the species level: 1046

    Proceeding to chemically informed reponderation ...
    
Number of annotations reweighted at the NPClassifier pathway level: 170938
Number of annotations reweighted at the NPClassifier superclass level: 149672
Number of annotations reweighted at the NPClassifier class level: 65701
100%|███████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 98/98 [01:10<00:00,  1.39it/s]
Cynara
Arion
Solanum tuberosum
Poaceae
Triticum aestivum
Papaver
Euphorbia
Notiophilus
Angiospermae
Veronica hederifolia
Capsella bursa-pastoris
Cerastium fontanum
Deroceras
Veronica
Life
Euphorbia helioscopia
Poa annua
Annelida
Coleoptera
Pterygota
Cynara
Arion
Solanum tuberosum
Poaceae
Triticum aestivum
Papaver
Euphorbia
Notiophilus
Angiospermae
Veronica hederifolia
Capsella bursa-pastoris
Cerastium fontanum
Deroceras
Veronica
Life
Euphorbia helioscopia
Poa annua
Annelida
Coleoptera
Pterygota