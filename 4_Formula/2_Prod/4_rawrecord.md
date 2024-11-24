🧠 Description
🎬 Raw Recording Export Strategy
- Export footage for Canva compatibility
- Optimize video and audio quality
- Follow structured export workflow

🕰️ Previous Retro
- Audio normalization needs improvement
- Subtitle workflow effective
- File naming conventions updated

🔍 Required Inputs
- 📹 Raw video footage
- 🎙️ Audio recordings
- 📝 Transcripts and markers

🎯 Export Checklist

⏱️ DaVinci Tasks
1. 🎬 Initial Processing
   - Transcribe footage
   - Edit using transcript
   - Remove semantic errors
   - Fix subtitle timing
   - Bookmark in Drive

2. 🔊 Audio Optimization
   - Remove basic silence
   - Clean filler words
   - Delete unused tracks
   - Normalize audio levels
   - Convert to mono
   - Increase volume
   - Create nested timelines

3. 📝 Subtitle Integration
   - Add backdrop subtitles
   - Make basic audio cuts
   - Apply semantic transcript cuts
   - Burn in subtitles
   - Export subtitle files
   - Create backup copies

4. 📋 File Management
   - Create sub-clips
   - Apply YAML indexing
   - Compress and divide
   - Upload to Canva
   - Resort cut segments
   - Check 1080p quality
   - Clone to marker cut
   - Verify frame fill
   - Assign slide links

⚡ Quick Reference
- ⏱️ Allow 1 hour per week
- 🎥 15000 Kb/sec limit
- 📺 1080p resolution
- 🔄 FFmpeg command:
  ```
  ffmpeg -i input.mov -c copy -map 0:v -map 0:a -f segment -segment_time 00:04:00 -reset_timestamps 1 -segment_format_options movflags=+faststart output%03d.mp4
  ```

📊 Task Status

🔄 Backlog
- Audio optimization
- Subtitle integration
- Quality checks

⏳ In Progress
- Initial processing
- File management
- Documentation updates

✅ Completed
- Script for file division
- Basic workflow setup

 💭 Prompts:
    - 🎯 Add or update content with relevant emojis
    - 🎬 Adapt content for video production context
    - 📝 Document and optimize production workflow
    - 🔧 Update technical implementation mapping
    - 🔍 Review and fix markdown formatting gaps
    - ✨ Enhance headers, subheaders and list formatting
    - 📊 Validate content structure and flow
    - 🎨 Apply consistent styling guidelines