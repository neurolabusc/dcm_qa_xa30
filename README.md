## About

This is a simple DICOM to NIfTI validator script and dataset based on Siemens XA30 enhanced DICOM images.

## Details

Images were acquired by Hu Cheng, Isaiah Innis, and Daniel Levitas using a Siemens Prisma Fit running XA30 at Indiana University. Additional sequence details are provided in the included PDF-format file.

* Common Parameters 
  * Manufacturer: Siemens
  * Model: Prisma Fit
  * Software Versions: MR XA30

| Series | Sequence name            |
| ------ | ------------------------ |
| 5-6    | anat-T1w_acq-tfl         |
| 7      | func-bold_task-fa_run-1  |
| 8-9    | gre_field_mapping        |
| 10-16  | DWI_dir80_PA             |
| 17-24  | DWI_dir80_AP             |
| 25-28  | asl_2d_tra               |

## Running

Assuming that the executable dcm2niix is in your path, you should be able to simply run the script `batch.sh` from the terminal.

## Links

 - [dcm_qa_enh](https://github.com/neurolabusc/dcm_qa_enh) provides enhanced DICOMs from other manufacturers.
