Image building handled by singularity-hub.org

### Usage

```
singularity pull shub://photocyte/shournal_singularity
singularity shell shournal_singularity_latest.sif 
source /usr/share/shournal/SOURCE_ME.bash
SHOURNAL_ENABLE
```

Currently not working with error:
```
shournal-run: shournal-run seems to lack the suid-bit (SETUID) for root. You can correct that by
chown root shournal-run && chmod u+s shournal-run
```

The Singularity build does do that, but still doesn't work.
