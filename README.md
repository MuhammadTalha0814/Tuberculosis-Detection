 Tuberculosis (TB) remains one of the leading causes of mortality worldwide, necessitating
 accurate and timely diagnosis for effective treatment and control. Chest X-ray (CXR) imaging, a widely
 used screening method, is often constrained by subjective interpretation and resource limitations, especially
 in low-resource settings. In this study, we present a novel hybrid deep learning approach that integrates
 Vision Transformers (ViT) and U-Net architectures to simultaneously perform segmentation of TB-affected
 regions and classification of TB presence. This dual-task model leverages global spatial features through
 a Transformer-based encoder and precise localization capabilities of a U-Net decoder. The model was
 trained and evaluated using the Shenzhen and Montgomery chest X-ray datasets, featuring annotated
 segmentation masks and metadata. Preprocessing involved resizing to 512 × 512, normalization, and
 augmentation techniques such as elastic transformations to improve robustness. The proposed approach
 achieved a segmentation accuracy of 94%, classification accuracy of 68%, and an Area Under the Curve
 (AUC) of 0.74, demonstrating its effectiveness in detecting and localizing TB. Notably, the segmentation
 performance surpasses several state-of-the-art methods, highlighting the model’s capacity for precise region
based diagnosis.
