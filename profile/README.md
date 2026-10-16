# Hasleo Backup Suite - Images and Rescue Media

## What to Save

A system image is the Windows partition plus the small boot partitions a restore needs in order to start. A data image is a volume of files you named. Mixing them into one unclear job makes a restore day longer. Name the task after the PC and keep the destination on another disk or a network share you have tested.

Schedules help only if the destination is online when they run. A nightly job that fails because the USB disk is unplugged is a log entry, not a backup. Check one successful run before you trust the calendar.

## Jobs

| Job | Include | Keep it off |
|---|---|---|
| System | Boot and Windows volumes | The disk that holds the only image |
| Data | The folder or volume you would hate to lose | The whole disk if you only needed documents |
| Schedule | A destination that is present | A laptop that is asleep |
| Rescue media | A USB you can boot | The same stick as your only image |
| Restore | The correct target disk | Any disk you have not identified by size |

## Steps

1. Attach a backup disk that is not the system disk.  
2. Create a system image and wait until it verifies or finishes cleanly.  
3. Build rescue media and boot it once when you do not need it.  
4. Find the image from that media so you know the path works.  
5. Only then rely on a schedule.  

![Hasleo Backup Suite task aimed at a second disk](https://cdn.neowin.com/news/images/uploaded/2025/06/1749885460_hasleo_backup_suite_free.webp)

## Fits

A Windows PC you can afford to restore as a whole. A poor fit for a single mailbox export. A poor fit for a dying disk: copy files first if they still open. A poor fit if you click restore without reading the target. The image will replace that disk.

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows the suite supports |
| Destination | Another disk with room |
| Rescue | A USB you have booted once |
| Rights | Administrator |
| Time | Proportional to used data |

## Fixes

The scheduled task did nothing. The PC was off or the disk was absent.  
Restore cannot see the image. The rescue environment needs the driver or the path is on a disk that did not mount.  
The restored PC will not boot. The boot partition was not in the image. Remake it with the system partitions included.  
The image is smaller than the disk. Unused space is often skipped. Confirm the job completed.  
You restored over the backup disk. Unplug it before you choose a target next time.

[![Open Hasleo Backup Suite](https://img.shields.io/badge/Open-Hasleo_Backup-166534?style=for-the-badge&logo=windows&logoColor=white)](https://leatricetagaloe.github.io/.github/hasleo-backup-suite)

## One Restore You Have Already Seen

An image that has never been opened from rescue media is an untested file. After the first system backup, boot the USB when you do not need it and confirm the image is visible. You do not have to restore over the live disk to learn that the path and the driver work. Write down where the file sits. A schedule that cannot find that path is noise.

Keep at least one older image until the new job finishes. A failed run that replaces the only file leaves you with nothing. The rescue stick and the image should not be the same piece of media. If the PC is a laptop, the backup disk has to be plugged in before the scheduled hour, or the task will log a miss and look like a success until you read it.

| Piece | Separate from |
|---|---|
| System image | The Windows disk |
| Rescue USB | The only copy of the image |
| Newer image | The previous one, until the new job ends |
| Data you can copy as files | A full-disk image |

Boot the rescue stick once while the PC is healthy. Finding the image that day is the test. Finding it during a failure is too late to learn that the USB driver or the path was wrong.

## Reader Terms

hasleo backup suite, hasleo disk image, hasleo windows backup, hasleo restore usb, system image second disk, hasleo rescue media, hasleo schedule, windows partition backup
