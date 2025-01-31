Pre-training techniques have been verified successfully in a variety of NLP tasks in recent
years. Despite the widespread use of pre-training models for NLP applications, they almost
exclusively focus on text-level manipulation, while neglecting layout and style information
that is vital for document image understanding. This project proposed LayoutLMv3 to pre-
train multimodal Transformers for Document AI with unified text and image masking which
is beneficial for a great number of real-world document image understanding tasks such as
information extraction from scanned documents. Furthermore, this model leverage image
features to incorporate words visual information into LayoutLMv3. The simple unified
architecture and training objectives make LayoutLMv3 a general-purpose pretrained model
for both text-centric and image-centric Document AI tasks.
Experimental results show that LayoutLMv3 achieves state-of-the-art performance not only
in text-centric tasks, including form understanding, receipt understanding, and document
visual question answering, but also in image-centric tasks such as document image
classification and document layout analysis. Using this model it achieves an increase in
accuracy in various downstream tasks, including form understanding (from 70.72 to 79.27),
receipt understanding (from 94.02 to 95.24) and document image classification (from 93.07
to 94.42).
