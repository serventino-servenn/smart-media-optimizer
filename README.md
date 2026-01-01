# smart-media-optimizer

 **Status:** Architecture & Planning Phase
 
##  Project Goal
A modern Android app demonstrating background media processing using Android WorkManager. The app will optimize images through compression, EXIF cleaning, and format conversion in the background.

##  Current Status (January 1,2026)
**Foundation Established:** Project created with Jetpack Compose template, WorkManager dependencies added, and initial architecture planned.

## Expected completion
Jan 10,2026

**Completed:**
-  Android Studio project setup
-  WorkManager and Compose dependencies configured
-  Git repository initialized
-  Basic package structure planned

**Next Steps:**
1. Implement ImageCompressionWorker
2. Build Compose UI screens  
3. Add chained workflow logic
4. Integrate Pexels API for image sources

## Planned Architecture
app/  
├── workers/ # WorkManager workers  
│ ├── ImageCompressionWorker.kt  
│ ├── ExifCleanerWorker.kt  
│ └── FormatConverterWorker.kt  
├── ui/ # Jetpack Compose screens  
│ ├── OneTimeWorkScreen.kt  
│ ├── ChainedWorkScreen.kt  
│ └── GalleryScreen.kt   
├── viewmodels/ # State management  
└── manager/ # WorkManager coordination   


## Technologies  
- **Kotlin** with **Coroutines** for async operations
- **Jetpack Compose** for declarative UI
- **Android WorkManager** for background processing
- **Material Design 3** for theming

##  Contributing
This is a personal learning project focused on demonstrating WorkManager skills. Suggestions and feedback are welcome!

*Project started: January 1, 2026*  
*Last updated: January 1, 2026*

