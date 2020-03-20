# Apple-EFI-Extracts-for-Newer-Systems
Extracts of newer Apple EFI payloads from 2018 onwards. Folders are categorized into system identifiers, followed by apple code number, folled by EFI type. EFI type labels were categoriezed into Intel and MEFI. Intel refers to images that were standard Intel EFI images similar to systems from 2017 and earlier, and MEFI refers to a newer format used by Apple during 2018. Interstingly, in 2019 systems such as the MacBookPro15,4 and 16,1 stop using the new MEFI format and revert back to intel based images.

__Region Files:__

Region files were extracted "as is" using UEFITool and may require trimming. So don't just go flashing them without making sure that if required they've been properly trimmed / edited. (Can just use a hex editor).

__Note:__

These are raw payloads, meaning like reagular Apple EFI payloads, they may require Initialization / Serialization with an Fsys Block etc. Haven't worked too much with these newer images, so still some unknowns.
