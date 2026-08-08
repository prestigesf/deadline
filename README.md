# deadline

Source for **claimfreepatch.netlify.app** — the shipping-label page for the
embroidered DeadlineSF patch.

One file, `index.html`, no build step and no dependencies. It uses the same
eight colour tokens as `prestigesf/deadlinesf` `public/index.html`, copied
rather than approximated, so the patch page and the checkout read as one
product. Change the palette in one and change it in the other.

The form is Netlify Forms (`data-netlify="true"`), so submissions land in this
site's **Forms** tab with no backend, no function and no API key.

## The package name is not decorative

The page says the patch is free with the **AB 2013 Gap Audit**. That has to
name a SKU that exists in `prestigesf/deadlinesf` `netlify/functions/catalog.mjs`.
It previously said "Studio Package", which is not one of the eight sold, so it
sent people to buy something that could not be bought. The eight are:

    ab2013_gap_audit            $750
    tier1_intake_applicability  $3,500
    tier2_provenance_install    $7,500
    tier3_control_plane_rush    $12,500
    tier4_monitoring_base       $500/mo
    tier4_monitoring_pro        $1,500/mo
    lifeline_scan               $795
    lifeline_implement          $2,500
