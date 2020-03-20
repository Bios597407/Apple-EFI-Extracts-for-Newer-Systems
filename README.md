# Apple-EFI-Extracts-for-Newer-Systems
Extracts of newer Apple EFI payloads from 2018 onwards. Folders are categorized into system identifiers, followed by apple code number, followed by EFI type. EFI type labels were categoriezed into Intel and MEFI. Intel refers to images that were standard Intel EFI images similar to systems from 2017 and earlier, and MEFI refers to a newer format used by Apple during 2018. The new MEFI format is just an additional header, that once stripped and reformatted produces a standard Intel EFI file capable of being parsed correctly in UEFITool. Folders marked MEFI will contain both the original EFI file with the MEFI header, as well as a modified file that contians the reformatted Intel style header. Interstingly, in 2019 systems such as the MacBookPro15,4 and 16,1 stop using the new MEFI format and revert back to intel based images.

__Region Files:__

Region files were extracted "as is" using UEFITool and may require trimming. So don't just go flashing them without making sure that if required they've been properly trimmed / edited. (Can just use a hex editor).

__Note:__

These are raw payloads, meaning like regular Apple EFI payloads, they are likely uninitialized and may require Initialization / Serialization with an Fsys Block etc. Haven't worked too much with these newer images, so still some unknowns.
