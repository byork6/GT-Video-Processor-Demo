# Video-Processor-Demo

This is a desktop application that was developed for **internal company use**. It demonstrates batch video annotation using YOLOv8/YOLO11 models. The source code for this application was designed to allow easy integration with various models, upon creation of a wrapper that bridges a given model's outputs with the core functionality of the application. Of course there are some limitations with what models can be integrated with the app but so far two different YOLO models have been used successfully. This GUI-based tool allows you to process raw video into frames, with either bounding *boxes* or segmentation masks. It includes a responsive interface, progress tracking, and an output data format that is compatible with the [Label Me](https://github.com/wkentaro/labelme) application. NOTE: Examples of source code are not included as the application was developed for internal use only.

---

## Features

- **Object Detection & Segmentation:** Supports both bounding box and mask-based annotations
- **Dynamic Model Selection:** Users can select from supported models at runtime
- **Batch Video Processing:** Annotate frames from individual videos or entire folders
- **LabelMe JSON Format:** Annotations are saved in LabelMe-compatible format
- **Progress Indicator:** Real-time feedback during batch processing
- **ImGui Front-End:** Use of [ImGui](https://github.com/ocornut/imgui) for the interface develoopment.

---

## GUI Examples

<p align="center">
   <img src="https://github.com/user-attachments/assets/652cff17-f5f5-4638-8187-b074c2706b65" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/c6548a88-f6df-4822-a704-b2f880a32a1b" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/16c1e6f4-941c-47f2-9a7a-6f60d98bb072" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/e4df2400-d2a8-4aee-978c-0de42dae4b19" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/ff1452cc-090a-4552-85f3-b85ec0f56367" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/90b25043-21dc-4071-af85-66f3486a59db" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/30c033e9-8d3f-4391-b5e7-42ee889ab3e2" width="750">
</p>

---

## Output Data Examples

<p align="center">
   <img src="https://github.com/user-attachments/assets/088c9c38-6416-439a-a012-3856b134a3d9" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/b7b932bd-8c19-442c-9f41-152cff6793ad" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/508af815-5e4b-4acf-b760-992194f9382c" width="750">
   <br><br>
   <img src="https://github.com/user-attachments/assets/8f2f0833-d902-4c43-bc24-71aecd2105de" width="750">
</p>

---

> **Note:** This project is a feature-limited demo. Internal models, configurations, and proprietary logic have been removed. The original version was created for internal company use.
