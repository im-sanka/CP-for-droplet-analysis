Here, we provide a pipeline for CellProfiler (version 3.1.8) to identify and measure the relative fluorescence of droplets in droplet microfluidic assays. We use the default pipeline (Images, Metadata, NamesAndTypes, and Groups) and combined it with the following modules: IdentifyPrimaryObjects, MeasureObjectIntensity, ExportToSpreadsheet, and ExportToDatabase.

**Important** notes:
1. The settings suit best with the naming format of **our example image data**. If you want to use this the pipeline, _remember to change the default pipeline and put the setting which suits your format_.
2. This pipeline should be able to be used in CellProfiler ver. 3 or later.
3. If you need clear guideline, we have put the full guideline in our publication's supplementary (see page 5 onwards): http://www.rsc.org/suppdata/d0/ay/d0ay00031k/d0ay00031k1.pdf
4. For full publication, you can find it at Bartkova et al. 2020. Droplet image analysis with user-friendly freeware CellProfiler. Anal. Methods, 2020,12, 2287-2294
5. If you still have issue with this pipeline, please add the issue here with the details or image example: https://github.com/taltechmicrofluidics/CP-for-droplet-analysis/issues/new

Thanks!
