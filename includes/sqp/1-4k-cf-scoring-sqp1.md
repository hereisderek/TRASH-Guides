#### Custom Formats and scores

??? abstract "Audio - [Click to show/hide]"
    | Custom Format                                                                                                 |           Score            | Trash ID                                          |
    | ------------------------------------------------------------------------------------------------------------- | :------------------------: | ------------------------------------------------- |
    | [{{ radarr['cf']['truehd-atmos']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#truehd-atmos)       | :warning: -10000 :warning: | {{ radarr['cf']['truehd-atmos']['trash_id'] }}    |
    | [{{ radarr['cf']['dts-x']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dts-x)                     | :warning: -10000 :warning: | {{ radarr['cf']['dts-x']['trash_id'] }}           |
    | [{{ radarr['cf']['atmos-undefined']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#atmos-undefined) |   :warning: 0 :warning:    | {{ radarr['cf']['atmos-undefined']['trash_id'] }} |
    | [{{ radarr['cf']['ddplus-atmos']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#ddplus-atmos)       |   :warning: 35 :warning:   | {{ radarr['cf']['ddplus-atmos']['trash_id'] }}    |
    | [{{ radarr['cf']['truehd']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#truehd)                   | :warning: -10000 :warning: | {{ radarr['cf']['truehd']['trash_id'] }}          |
    | [{{ radarr['cf']['dts-hd-ma']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dts-hd-ma)             | :warning: -10000 :warning: | {{ radarr['cf']['dts-hd-ma']['trash_id'] }}       |
    | [{{ radarr['cf']['flac']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#flac)                       |   :warning: 0 :warning:    | {{ radarr['cf']['flac']['trash_id'] }}            |
    | [{{ radarr['cf']['pcm']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#pcm)                         |   :warning: 0 :warning:    | {{ radarr['cf']['pcm']['trash_id'] }}             |
    | [{{ radarr['cf']['dts-hd-hra']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dts-hd-hra)           | :warning: -10000 :warning: | {{ radarr['cf']['dts-hd-hra']['trash_id'] }}      |
    | [{{ radarr['cf']['ddplus']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#ddplus)                   |   :warning: 25 :warning:   | {{ radarr['cf']['ddplus']['trash_id'] }}          |
    | [{{ radarr['cf']['dts-es']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dts-es)                   | :warning: -10000 :warning: | {{ radarr['cf']['dts-es']['trash_id'] }}          |
    | [{{ radarr['cf']['dts']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dts)                         |   :warning: 0 :warning:    | {{ radarr['cf']['dts']['trash_id'] }}             |
    | [{{ radarr['cf']['aac']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#aac)                         |   :warning: 0 :warning:    | {{ radarr['cf']['aac']['trash_id'] }}             |
    | [{{ radarr['cf']['dd']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dd)                           |   :warning: 15 :warning:   | {{ radarr['cf']['dd']['trash_id'] }}              |

    !!! warning "Scores marked with a :warning: warning :warning: are different to those used in the main public guide"

    !!! danger "The CF with `0` you can choose to add with a score of `0` or just don't add them.<br>The reason why we score them this low is to prevent transcoding as much as possible.<br>The reason why `DTS` has a score of `0` is to make sure, that you don't limit yourself too much."

??? abstract "All HDR Formats + DV (WEBDL) - [Click to show/hide]"
    | Custom Format                                                                                             |                       Score                        | Trash ID                                        |
    | --------------------------------------------------------------------------------------------------------- | :------------------------------------------------: | ----------------------------------------------- |
    | [{{ radarr['cf']['dv-hdr10']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-hdr10)           |   {{ radarr['cf']['dv-hdr10']['trash_score'] }}    | {{ radarr['cf']['dv-hdr10']['trash_id'] }}      |
    | [{{ radarr['cf']['dv']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv)                       |      {{ radarr['cf']['dv']['trash_score'] }}       | {{ radarr['cf']['dv']['trash_id'] }}            |
    | [{{ radarr['cf']['dv-hlg']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-hlg)               |    {{ radarr['cf']['dv-hlg']['trash_score'] }}     | {{ radarr['cf']['dv-hlg']['trash_id'] }}        |
    | [{{ radarr['cf']['dv-sdr']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-sdr)               |    {{ radarr['cf']['dv-sdr']['trash_score'] }}     | {{ radarr['cf']['dv-sdr']['trash_id'] }}        |
    | [{{ radarr['cf']['hdr10plus']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr10plus)         |   {{ radarr['cf']['hdr10plus']['trash_score'] }}   | {{ radarr['cf']['hdr10plus']['trash_id'] }}     |
    | [{{ radarr['cf']['hdr10']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr10)                 |     {{ radarr['cf']['hdr10']['trash_score'] }}     | {{ radarr['cf']['hdr10']['trash_id'] }}         |
    | [{{ radarr['cf']['hdr']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr)                     |      {{ radarr['cf']['hdr']['trash_score'] }}      | {{ radarr['cf']['hdr']['trash_id'] }}           |
    | [{{ radarr['cf']['hdr-undefined']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr-undefined) | {{ radarr['cf']['hdr-undefined']['trash_score'] }} | {{ radarr['cf']['hdr-undefined']['trash_id'] }} |
    | [{{ radarr['cf']['pq']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#pq)                       |      {{ radarr['cf']['pq']['trash_score'] }}       | {{ radarr['cf']['pq']['trash_id'] }}            |
    | [{{ radarr['cf']['hlg']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hlg)                     |      {{ radarr['cf']['hlg']['trash_score'] }}      | {{ radarr['cf']['hlg']['trash_id'] }}           |
    | [{{ radarr['cf']['dv-webdl']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#dv-webdl)           |   {{ radarr['cf']['dv-webdl']['trash_score'] }}    | {{ radarr['cf']['dv-webdl']['trash_id'] }}      |

    !!! danger "The reason why we add `DV (WEBDL)` is because you want maximum compatibility across all devices :warning:"

??? abstract "Movie Versions - [Click to show/hide]"
    | Custom Format                                                                                                           |                           Score                           | Trash ID                                               |
    | ----------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------: | ------------------------------------------------------ |
    | [{{ radarr['cf']['remaster']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#remaster)                         |       {{ radarr['cf']['remaster']['trash_score'] }}       | {{ radarr['cf']['remaster']['trash_id'] }}             |
    | [{{ radarr['cf']['4k-remaster']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#4k-remaster)                   |     {{ radarr['cf']['4k-remaster']['trash_score'] }}      | {{ radarr['cf']['4k-remaster']['trash_id'] }}          |
    | [{{ radarr['cf']['criterion-collection']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#criterion-collection) | {{ radarr['cf']['criterion-collection']['trash_score'] }} | {{ radarr['cf']['criterion-collection']['trash_id'] }} |
    | [{{ radarr['cf']['masters-of-cinema']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#masters-of-cinema)       |  {{ radarr['cf']['masters-of-cinema']['trash_score'] }}   | {{ radarr['cf']['masters-of-cinema']['trash_id'] }}    |
    | [{{ radarr['cf']['vinegar-syndrome']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#vinegar-syndrome)         |   {{ radarr['cf']['vinegar-syndrome']['trash_score'] }}   | {{ radarr['cf']['vinegar-syndrome']['trash_id'] }}     |
    | [{{ radarr['cf']['special-edition']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#special-edition)           |   {{ radarr['cf']['special-edition']['trash_score'] }}    | {{ radarr['cf']['special-edition']['trash_id'] }}      |

    !!! info
        - If you prefer 1080p/2160p WEBDL with IMAX-E then add [{{ radarr['cf']['imax-enhanced']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#imax-enhanced) with the default scores.
        - The reason why we don't add [{{ radarr['cf']['imax']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#imax) is because BHDStudio doesn't add it to their release name. Their motto is: If the source has IMAX then the encode will have it as well.

        !!! danger "Adding `IMAX`/`IMAX Enhanced` will replace the BHDStudio release :warning:"

??? abstract "HQ Release Groups - [Click to show/hide]"
    | Custom Format                                                                                                                        |                      Score                       | Trash ID                                            |
    | ------------------------------------------------------------------------------------------------------------------------------------ | :----------------------------------------------: | --------------------------------------------------- |
    | [{{ radarr['cf']['bhdstudio']['name'] }}](https://raw.githubusercontent.com/TRaSH-/Guides/master/docs/json/radarr/cf/bhdstudio.json) |  {{ radarr['cf']['bhdstudio']['trash_score'] }}  | {{ radarr['cf']['bhdstudio']['trash_id'] }}         |
    | [{{ radarr['cf']['web-tier-01']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#web-tier-01)                                | {{ radarr['cf']['web-tier-01']['trash_score'] }} | {{ radarr['cf']['web-tier-01']['trash_id'] }}       |
    | [{{ radarr['cf']['web-tier-02']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#web-tier-02)                                | {{ radarr['cf']['web-tier-02']['trash_score'] }} | {{ radarr['cf']['web-tier-02']['trash_id'] }}       |
    | [{{ radarr['cf']['web-tier-03']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#web-tier-03)                                | {{ radarr['cf']['web-tier-03']['trash_score'] }} | {{ radarr['cf']['web-tier-03']['trash_id'] }}       |
    | [{{ radarr['cf']['hd-bluray-tier-01']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hd-bluray-tier-01)                    |             :warning: 1100 :warning:             | {{ radarr['cf']['hd-bluray-tier-01']['trash_id'] }} |
    | [{{ radarr['cf']['hd-bluray-tier-02']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hd-bluray-tier-02)                    |             :warning: 1050 :warning:             | {{ radarr['cf']['hd-bluray-tier-02']['trash_id'] }} |
    | [{{ radarr['cf']['hd-bluray-tier-03']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hd-bluray-tier-03)                    |             :warning: 1000 :warning:             | {{ radarr['cf']['hd-bluray-tier-03']['trash_id'] }} |

    !!! warning "Scores marked with a :warning: warning :warning: are different to those used in the main public guide"

    !!! tip
        If you use SQP-1 (1080p) as your main/second Radarr you want to remove the following HQ Release Groups

        - `[{{ radarr['cf']['hd-bluray-tier-01']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hd-bluray-tier-01)`
        - `[{{ radarr['cf']['hd-bluray-tier-02']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hd-bluray-tier-02)`
        - `[{{ radarr['cf']['hd-bluray-tier-03']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hd-bluray-tier-03)`

{! include-markdown "../../includes/cf/radarr-misc.md" !}

{! include-markdown "../../includes/cf/radarr-unwanted-uhd.md" !}

??? abstract "Optional - [Click to show/hide]"
    | Custom Format                                                                                                       |                        Score                         | Trash ID                                          |
    | ------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------: | ------------------------------------------------- |
    | [{{ radarr['cf']['bad-dual-groups']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#bad-dual-groups)       | {{ radarr['cf']['bad-dual-groups']['trash_score'] }} | {{ radarr['cf']['bad-dual-groups']['trash_id'] }} |
    | [{{ radarr['cf']['hdr10plus-boost']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#hdr10plus-boost)       | {{ radarr['cf']['hdr10plus-boost']['trash_score'] }} | {{ radarr['cf']['hdr10plus-boost']['trash_id'] }} |
    | [{{ radarr['cf']['evo-no-webdl']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#evo-no-webdl)             |  {{ radarr['cf']['evo-no-webdl']['trash_score'] }}   | {{ radarr['cf']['evo-no-webdl']['trash_id'] }}    |
    | [{{ radarr['cf']['no-rlsgroup']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#no-rlsgroup)               |   {{ radarr['cf']['no-rlsgroup']['trash_score'] }}   | {{ radarr['cf']['no-rlsgroup']['trash_id'] }}     |
    | [{{ radarr['cf']['obfuscated']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#obfuscated)                 |   {{ radarr['cf']['obfuscated']['trash_score'] }}    | {{ radarr['cf']['obfuscated']['trash_id'] }}      |
    | [{{ radarr['cf']['retags']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#retags)                         |     {{ radarr['cf']['retags']['trash_score'] }}      | {{ radarr['cf']['retags']['trash_id'] }}          |
    | [{{ radarr['cf']['scene']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#scene)                           |      {{ radarr['cf']['scene']['trash_score'] }}      | {{ radarr['cf']['scene']['trash_id'] }}           |
    | [{{ radarr['cf']['x265-no-hdrdv']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#x265-no-hdrdv) :warning: |  {{ radarr['cf']['x265-no-hdrdv']['trash_score'] }}  | {{ radarr['cf']['x265-no-hdrdv']['trash_id'] }}   |
    | [{{ radarr['cf']['av1']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#av1)                               |              :warning: -10000 :warning:              | {{ radarr['cf']['av1']['trash_id'] }}             |

    !!! tip "I recommend to use the the following Custom Formats"
        - `x265 (no HDR/DV)` over the `x265 (HD)`, Read the Why below and don't forget to read the warning,<br>:warning: Only ever include one of them :warning:
        - `SDR` This will help to prevent to grab UHD/4k releases without HDR Formats
        - `AV1` This will help to prevent to grab AV1 releases

    ------

    Breakdown and Why

    - **{{ radarr['cf']['bad-dual-groups']['name'] }}:** [*Optional*] These groups take the original release, then they add their own preferred language (ex. Portuguese) as the main audio track (AAC 2.0), What results after renaming and FFprobe that the media file will be recognized as Portuguese AAC audio. It's a common rule that you add the best audio as first.
    Also they often even rename the release name in to Portuguese.
    - **{{ radarr['cf']['hdr10plus-boost']['name'] }}:** [*Optional*] (use this one only if you have a (Samsung) TV that supports HDR10+ and you don't have a Setup that supports DV or you prefer HDR10+)
    - **{{ radarr['cf']['evo-no-webdl']['name'] }}:** This group is often banned for the low quality Blu-ray releases, but their WEB-DL are okay.
    - **{{ radarr['cf']['no-rlsgroup']['name'] }}:** [*Optional*] Some indexers strip out the release group what could result in LQ groups getting a higher score. For example a lot of EVO releases end up stripping the group name, so they appear as "upgrades", and they end up getting a decent score if other things match.
    - **{{ radarr['cf']['obfuscated']['name'] }}:** [*Optional*] (use these only if you dislike renamed releases)
    - **{{ radarr['cf']['retags']['name'] }}:** [*Optional*] (use these only if you dislike retagged releases)
    - **{{ radarr['cf']['scene']['name'] }}:** [*Optional*] (use these only if you dislike scene releases)
    - **{{ radarr['cf']['x265-no-hdrdv']['name'] }}:** This blocks 720/1080p (HD) releases that are encoded in x265. - More info [HERE](/Misc/x265-4k/){:target="_blank" rel="noopener noreferrer"}.

        **But it will allow x265 releases if they have HDR and/or DV**

        *Being that some NF releases won't be released as 4k, but you want to have DV/HDR releases.*

        In your quality profile use the following score for this Custom Format: `{{ radarr['cf']['x265-no-hdrdv']['trash_score'] }}`

        !!! Danger "Don't use this together with [{{ radarr['cf']['x265-hd']['name'] }}](/Radarr/Radarr-collection-of-custom-formats/#x265-hd), Only ever include one of them :warning:"

    - **{{ radarr['cf']['sdr']['name'] }}:** This will help to prevent to grab UHD/4k releases without HDR Formats.
    - **{{ radarr['cf']['av1']['name'] }}:** This will help to prevent to grab AV1 releases.

{! include-markdown "../../includes/sqp/hd-radarr-resolution.md" !}

{! include-markdown "../../includes/cf/radarr-streaming-services.md" !}
