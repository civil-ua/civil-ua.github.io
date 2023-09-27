## Overview

This is the github repo for the Intelligent Imaging and Computational Vision Laboratory (IICV), Shanghai Jiao Tong University. The website uses the static site generator [jekyll](https://jekyllrb.com/) and is based on the [Feeling Responsive jekyll theme](https://github.com/Phlow/feeling-responsive). Development occurs on the dev branch, the live site is located on the master branch. Many thanks to the code bases from [Griffith Lab](http://griffithlab.org), WUSTL.

## License

The code for this site is licensed under an MIT license, images may have specific attribution requirements and are licensed individually under assets/img/image_attribution

```
iicv-sjtu.github.io-master
├─ .gitignore
├─ .ruby-version
├─ assets
│  ├─ css
│  │  ├─ atom.scss
│  │  ├─ fontawesome.all.min.css
│  │  ├─ rss.scss
│  │  └─ styles_feeling_responsive.scss
│  ├─ fonts
│  │  ├─ .fontcustom-manifest.json
│  │  ├─ academicons.eot
│  │  ├─ academicons.svg
│  │  ├─ academicons.ttf
│  │  ├─ academicons.woff
│  │  ├─ fa-brands-400.ttf
│  │  ├─ fa-brands-400.woff2
│  │  ├─ fa-regular-400.ttf
│  │  ├─ fa-regular-400.woff2
│  │  ├─ fa-solid-900.ttf
│  │  ├─ fa-solid-900.woff2
│  │  ├─ fa-v4compatibility.ttf
│  │  ├─ fa-v4compatibility.woff2
│  │  ├─ fontcustom.yml
│  │  ├─ iconfont-preview.html
│  │  ├─ iconfont.css
│  │  ├─ iconfont.eot
│  │  ├─ iconfont.svg
│  │  ├─ iconfont.ttf
│  │  ├─ iconfont.woff
│  │  ├─ iconfont.woff2
│  │  └─ svg-files-for-custom-font
│  │     ├─ .fontcustom-manifest.json
│  │     ├─ archive.svg
│  │     ├─ browser.svg
│  │     ├─ calendar.svg
│  │     ├─ camera.svg
│  │     ├─ chat.svg
│  │     ├─ check.svg
│  │     ├─ chevron-down.svg
│  │     ├─ chevron-left.svg
│  │     ├─ chevron-right.svg
│  │     ├─ chevron-up.svg
│  │     ├─ circle-with-cross.svg
│  │     ├─ circle-with-minus.svg
│  │     ├─ circle-with-plus.svg
│  │     ├─ cloud.svg
│  │     ├─ code.svg
│  │     ├─ cog.svg
│  │     ├─ dropbox.svg
│  │     ├─ edit.svg
│  │     ├─ export.svg
│  │     ├─ eye.svg
│  │     ├─ facebook.svg
│  │     ├─ feather.svg
│  │     ├─ github.svg
│  │     ├─ globe.svg
│  │     ├─ heart-outlined.svg
│  │     ├─ heart.svg
│  │     ├─ home.svg
│  │     ├─ info-with-circle.svg
│  │     ├─ info.svg
│  │     ├─ instagram.svg
│  │     ├─ lab-flask.svg
│  │     ├─ leaf.svg
│  │     ├─ link.svg
│  │     ├─ linkedin.svg
│  │     ├─ mail.svg
│  │     ├─ message.svg
│  │     ├─ mic.svg
│  │     ├─ network.svg
│  │     ├─ orcid.svg
│  │     ├─ paper-plane.svg
│  │     ├─ pinterest.svg
│  │     ├─ price-tag.svg
│  │     ├─ rocket.svg
│  │     ├─ rss.svg
│  │     ├─ soundcloud.svg
│  │     ├─ star-outlined.svg
│  │     ├─ star.svg
│  │     ├─ thumbs-down.svg
│  │     ├─ thumbs-up.svg
│  │     ├─ tree.svg
│  │     ├─ tumblr.svg
│  │     ├─ twitter.svg
│  │     ├─ upload-to-cloud.svg
│  │     ├─ user.svg
│  │     ├─ video.svg
│  │     ├─ vimeo.svg
│  │     ├─ warning.svg
│  │     ├─ xing.svg
│  │     └─ youtube.svg
│  ├─ img
│  │  ├─ apple-touch-icon-114x114-precomposed.pdf
│  │  ├─ apple-touch-icon-114x114-precomposed.png
│  │  ├─ apple-touch-icon-120x120-precomposed.pdf
│  │  ├─ apple-touch-icon-120x120-precomposed.png
│  │  ├─ apple-touch-icon-144x144-precomposed.pdf
│  │  ├─ apple-touch-icon-144x144-precomposed.png
│  │  ├─ apple-touch-icon-152x152-precomposed.pdf
│  │  ├─ apple-touch-icon-152x152-precomposed.png
│  │  ├─ apple-touch-icon-180x180-precomposed.pdf
│  │  ├─ apple-touch-icon-180x180-precomposed.png
│  │  ├─ apple-touch-icon-72x72-precomposed.pdf
│  │  ├─ apple-touch-icon-72x72-precomposed.png
│  │  ├─ apple-touch-icon-76x76-precomposed.pdf
│  │  ├─ apple-touch-icon-76x76-precomposed.png
│  │  ├─ apple-touch-icon-precomposed.pdf
│  │  ├─ apple-touch-icon-precomposed.png
│  │  ├─ favicon-32x32.pdf
│  │  ├─ favicon-32x32.png
│  │  ├─ funding
│  │  │  ├─ CDI_logo.gif
│  │  │  ├─ CDI_logo.png
│  │  │  ├─ CRF_logo.png
│  │  │  ├─ ICTS_logo.png
│  │  │  ├─ mgi_logo.jpg
│  │  │  ├─ mgi_logo_shadow.png
│  │  │  ├─ NCATS_logo.png
│  │  │  ├─ NIH_Master_Logo_Vertical_2Color.png
│  │  │  ├─ US-NIH-NCI-Logo.png
│  │  │  ├─ US-NIH-NHGRI-Logo.png
│  │  │  ├─ V_foundation.png
│  │  │  ├─ WUSTL_Medicine.jpg
│  │  │  └─ WUSTL_Medicine.png
│  │  ├─ image_attribution
│  │  ├─ lab_photo_Aug2022.jpg
│  │  ├─ lab_photo_Aug2022_cropped.jpeg
│  │  ├─ lab_photo_Dec2017_cropped.jpg
│  │  ├─ lab_photo_Dec2017_cropped.png
│  │  ├─ lab_photo_Dec2017_cropped_v2.jpg
│  │  ├─ MalachiAndObi.jpg
│  │  ├─ MG14.jpg
│  │  ├─ msapplication_tileimage.pdf
│  │  ├─ msapplication_tileimage.png
│  │  ├─ news
│  │  │  ├─ AlexWagner_ICTS_EricGreen.png
│  │  │  ├─ AML_Barnell.jpeg
│  │  │  ├─ BALL_Barnell.png
│  │  │  ├─ CARD11_figure_8.png
│  │  │  ├─ CIViC_Hackathon.jpg
│  │  │  ├─ CIViC_NatureCan.jpg
│  │  │  ├─ CIViC_SOP.jpeg
│  │  │  ├─ ctDNA_Barnell.jpg
│  │  │  ├─ DeepSVR.png
│  │  │  ├─ DGIdb4.jpeg
│  │  │  ├─ DGIdb_3.0.png
│  │  │  ├─ ERposBreastCBFB.png
│  │  │  ├─ GCBR.png
│  │  │  ├─ genvisr_Skidmore.jpeg
│  │  │  ├─ GraphicalAbstract_v4.png
│  │  │  ├─ HCC_Skidmore.jpg
│  │  │  ├─ HNSCC_Campbell.jpeg
│  │  │  ├─ ManualReviewSOP.png
│  │  │  ├─ metakb.png
│  │  │  ├─ MVLD_CIViC.png
│  │  │  ├─ neoantigen_review.png
│  │  │  ├─ NTRK1.jpeg
│  │  │  ├─ opencap.jpg
│  │  │  ├─ ProximalVars.png
│  │  │  ├─ pVACtools.jpeg
│  │  │  ├─ RegTools.png
│  │  │  └─ RelapsedSCLC.png
│  │  ├─ obig2.jpg
│  │  ├─ research
│  │  │  ├─ ALL1_GraphicalAbstract_neutral.png
│  │  │  ├─ AML31_Slider_Image.png
│  │  │  ├─ FL_Histone_CoOccurence.png
│  │  │  ├─ GP-127_CIViC_simplified-overview_v2d.png
│  │  │  ├─ HCC32_circos.png
│  │  │  ├─ HCC32_combined.png
│  │  │  ├─ HCC32_DNAJB1_PRKACA.png
│  │  │  ├─ immunogenomics.png
│  │  │  ├─ oscc_pdx_graphical_abstract.png
│  │  │  ├─ SCLC_figure_1b.png
│  │  │  └─ Stat1_slider_image.png
│  │  ├─ Site_Logo2.png
│  │  ├─ Site_Logo3.pdf
│  │  ├─ Site_Logo3.png
│  │  ├─ Site_Logo4.pdf
│  │  ├─ Site_Logo4.png
│  │  ├─ software
│  │  │  ├─ civicpy_logo.png
│  │  │  ├─ civicpy_workflow.png
│  │  │  ├─ CIViC_logo.png
│  │  │  ├─ civic_screenshot.png
│  │  │  ├─ dgidb_logo.png
│  │  │  ├─ dgidb_screenshot.png
│  │  │  ├─ docm_logo.png
│  │  │  ├─ docm_screenshot.png
│  │  │  ├─ genvisr_overview.png
│  │  │  ├─ opencap_logo.png
│  │  │  ├─ opencap_logo2.png
│  │  │  ├─ opencap_screenshot.png
│  │  │  ├─ pvactools_logo.png
│  │  │  ├─ pVACtools_overview.png
│  │  │  ├─ regtools_overview.png
│  │  │  ├─ triomix.png
│  │  │  ├─ vatools_logo.png
│  │  │  ├─ vatools_logo2.png
│  │  │  └─ vatools_screenshot.png
│  │  ├─ team
│  │  │  ├─ adam_coffman.jpg
│  │  │  ├─ akshay_balaji.jpg
│  │  │  ├─ alex_wagner.jpg
│  │  │  ├─ alex_wollam.jpg
│  │  │  ├─ alina_schmidt.jpg
│  │  │  ├─ anamika_basu.jpg
│  │  │  ├─ arpad_danos.jpg
│  │  │  ├─ avi_ramu.jpg
│  │  │  ├─ benjamin_ainscough.jpg
│  │  │  ├─ brian_li.jpg
│  │  │  ├─ bryan_fisk.jpg
│  │  │  ├─ chris_yoon.jpg
│  │  │  ├─ cody_ramirez.png
│  │  │  ├─ connor_liu.jpg
│  │  │  ├─ erica_barnell.jpg
│  │  │  ├─ felicia_gomez.jpg
│  │  │  ├─ gejae_jeffers.jpg
│  │  │  ├─ huiming_xia.jpg
│  │  │  ├─ jace_webster.jpg
│  │  │  ├─ jason_kunisaki.jpg
│  │  │  ├─ jason_saliba.jpg
│  │  │  ├─ jason_walker.jpg
│  │  │  ├─ jasreet_hundal.jpg
│  │  │  ├─ johnathan_song.jpg
│  │  │  ├─ joshua_mcmichael.jpg
│  │  │  ├─ justin_guerra.jpg
│  │  │  ├─ kaitlin_clark.png
│  │  │  ├─ kartik_singhal.jpg
│  │  │  ├─ katie_campbell.jpg
│  │  │  ├─ kelsy_cotto.jpg
│  │  │  ├─ kilannin_krysiak.jpg
│  │  │  ├─ lana_sheta.jpg
│  │  │  ├─ lee_trani.jpg
│  │  │  ├─ lynzey_kujan.png
│  │  │  ├─ malachi_griffith.jpg
│  │  │  ├─ malik_sediqzad.jpg
│  │  │  ├─ mariam_khanfar.png
│  │  │  ├─ matthew_mosior.jpg
│  │  │  ├─ megan_richters.png
│  │  │  ├─ my_hoang.jpeg
│  │  │  ├─ nicholas_spies.jpg
│  │  │  ├─ nischal_khanal.jpg
│  │  │  ├─ obi_griffith.jpg
│  │  │  ├─ peter_ronning.jpg
│  │  │  ├─ robert_lesurf.jpg
│  │  │  ├─ shahil_pema.jpg
│  │  │  ├─ sharon_freshour.jpg
│  │  │  ├─ sidi_zhao.jpg
│  │  │  ├─ susanna_kiwala.jpeg
│  │  │  ├─ sydney_anderson.jpg
│  │  │  ├─ weimin_zhou.jpg
│  │  │  ├─ wentao_chen.jpg
│  │  │  ├─ xichen_xu.jpg
│  │  │  ├─ yangyang_feng.png
│  │  │  └─ zachary_skidmore.jpg
│  │  ├─ touch-icon-192x192.pdf
│  │  └─ touch-icon-192x192.png
│  ├─ js
│  │  ├─ javascript.js
│  │  ├─ javascript.min.js
│  │  ├─ modernizr.js
│  │  └─ modernizr.min.js
│  ├─ mediaelement_js
│  │  ├─ background.png
│  │  ├─ bigplay.fw.png
│  │  ├─ bigplay.png
│  │  ├─ bigplay.svg
│  │  ├─ controls-ted.png
│  │  ├─ controls-wmp-bg.png
│  │  ├─ controls-wmp.png
│  │  ├─ controls.fw.png
│  │  ├─ controls.png
│  │  ├─ controls.svg
│  │  ├─ DO NOT CHANGE THESE FILES. USE -src- FOLDER.txt
│  │  ├─ flashmediaelement-cdn.swf
│  │  ├─ flashmediaelement-debug.swf
│  │  ├─ flashmediaelement.swf
│  │  ├─ jquery.js
│  │  ├─ jumpforward.png
│  │  ├─ loading.gif
│  │  ├─ mediaelement-and-player.js
│  │  ├─ mediaelement-and-player.min.js
│  │  ├─ mediaelement.js
│  │  ├─ mediaelement.min.js
│  │  ├─ mediaelementplayer.css
│  │  ├─ mediaelementplayer.js
│  │  ├─ mediaelementplayer.min.css
│  │  ├─ mediaelementplayer.min.js
│  │  ├─ mejs-skins.css
│  │  ├─ silverlightmediaelement.xap
│  │  └─ skipback.png
│  └─ xslt
│     ├─ atom.xslt
│     └─ rss.xslt
├─ CNAME
├─ Gemfile
├─ images
│  ├─ genvis-dna-bg_optimized_v1a.pdf
│  └─ genvis-dna-bg_optimized_v1a.png
├─ LICENSE
├─ news
│  ├─ archive.html
│  └─ index.html
├─ pages
│  ├─ contact.md
│  ├─ funding.md
│  ├─ join.md
│  ├─ pages-root-folder
│  │  ├─ 404.md
│  │  ├─ atom.xml
│  │  ├─ feed.xml
│  │  ├─ humans.txt
│  │  ├─ index.md
│  │  ├─ robots.txt
│  │  └─ sitemap.xml
│  ├─ positions.md
│  ├─ publications.md
│  ├─ redirected_page.md
│  ├─ research.md
│  ├─ software.md
│  ├─ teaching.md
│  ├─ team.md
│  └─ welcome.md
├─ README.md
├─ _config.yml
├─ _config_dev.yml
├─ _data
│  ├─ authors.yml
│  ├─ language.yml
│  ├─ language_de.yml
│  ├─ navigation.yml
│  ├─ network.yml
│  ├─ services.yml
│  └─ socialmedia.yml
├─ _drafts
│  ├─ gallery.md
│  ├─ page_all_frontmatter.md
│  ├─ page_simple.md
│  ├─ page_without_image.md
│  ├─ page_with_image.md
│  ├─ page_with_table_of_contents.md
│  ├─ post_without_image.md
│  ├─ post_with_image.md
│  └─ video.md
├─ _includes
│  ├─ alert
│  ├─ gallery
│  ├─ list-collection
│  ├─ list-posts
│  ├─ map
│  ├─ next-previous-post-in-category
│  ├─ project
│  ├─ publication
│  ├─ sitemap_collection.xml
│  ├─ software
│  ├─ team_member
│  ├─ _breadcrumb.html
│  ├─ _comments.html
│  ├─ _favicon.html
│  ├─ _footer.html
│  ├─ _footer_scripts.html
│  ├─ _frontpage-widget.html
│  ├─ _google_search.html
│  ├─ _head.html
│  ├─ _improve_content.html
│  ├─ _masthead.html
│  ├─ _meta_information.html
│  ├─ _navigation.html
│  ├─ _pagination.html
│  ├─ _sidebar.html
│  └─ __INSTRUCTIONS.md
├─ _layouts
│  ├─ compress.html
│  ├─ default.html
│  ├─ frontpage.html
│  ├─ news.html
│  ├─ page-fullwidth.html
│  ├─ page.html
│  ├─ redirect.html
│  ├─ video.html
│  └─ xml-style.xsl
├─ _posts
│  ├─ 2017-10-16-NewSite.md
│  ├─ 2017-10-17-VICCsite.md
│  ├─ 2017-10-26-BloodP2C.md
│  ├─ 2017-11-01-ASHachievementAward.md
│  ├─ 2017-12-07-DGIdb_3.0.md
│  ├─ 2017-12-13-Bainscough_Defense.md
│  ├─ 2018-01-16-WagnerICTS.md
│  ├─ 2018-02-01-GomezK12.md
│  ├─ 2018-02-21-ManualReviewSOP.md
│  ├─ 2018-02-28-Kcotto_QE.md
│  ├─ 2018-03-14-WagnerAACR.md
│  ├─ 2018-04-02-WagnerCGC.md
│  ├─ 2018-04-08-Biocuration.md
│  ├─ 2018-04-11-McMichaelBiocuration.md
│  ├─ 2018-07-01-Kkrysiak_ABMGG.md
│  ├─ 2018-08-21-OSCC_PDX.md
│  ├─ 2018-09-04-ERpos_Breast_prognostic_mutations.md
│  ├─ 2018-09-11-RelapsedSCLC_paper.md
│  ├─ 2018-09-28-Kcampbell_Defense.md
│  ├─ 2018-10-06-Hum_Mut_CIViC_MVLD.md
│  ├─ 2018-10-16-CIViC_Hackathon.md
│  ├─ 2018-11-05-DeepSVR_paper.md
│  ├─ 2018-12-03-Proximal_paper.md
│  ├─ 2018-12-24-Griffith_gridiron_2018.md
│  ├─ 2019-03-29-AACR_2019.md
│  ├─ 2019-04-02-U24.md
│  ├─ 2019-06-01-WagnerK99.md
│  ├─ 2019-08-28-Neoantigen_review.md
│  ├─ 2019-08-30-CGC_meeting.md
│  ├─ 2019-09-27-Barnell_ThesisDefense.md
│  ├─ 2019-10-16-OpenCAP_paper.md
│  ├─ 2019-11-05-SEQTEC_course.md
│  ├─ 2019-11-29-CIViC_SOP.md
│  ├─ 2019-12-03-Barnell_30under30.md
│  ├─ 2020-03-06-Kipnis Award.md
│  ├─ 2020-03-19-CIViCpy.md
│  ├─ 2020-04-03-MetaKB_NatGen.md
│  ├─ 2020-04-08-AACRSITAward.md
│  ├─ 2020-04-11-LeahMenshouseAward.md
│  ├─ 2020-04-13-Wagner_Summary.md
│  ├─ 2020-09-18-Richters_GATP.md
│  ├─ 2020-10-01-HNSCC-paper.md
│  ├─ 2021-01-01-pVACtools-paper-AACR.md
│  ├─ 2021-01-08-DGIdb4_paper.md
│  ├─ 2021-01-14-AML_paper.md
│  ├─ 2021-09-01-GenVisR_paper.md
│  ├─ 2021-11-11-Yoon-Poster-award.md
│  ├─ 2022-04-01-Yoon-F30.md
│  ├─ 2022-05-27-CIViC_paper.md
│  ├─ 2022-06-01-HCC_paper.md
│  ├─ 2022-06-02-NTRK-paper.md
│  ├─ 2022-07-01-Gomez_promotion.md
│  ├─ 2022-07-26-Cotto_ThesisDefense.md
│  ├─ 2022-07-27-Campbell-PICI.md
│  ├─ 2022-08-01-Hoang-pathway.md
│  ├─ 2022-08-04-CGC-poster-award.md
│  ├─ 2022-08-08-Yoon_ThesisDefense.md
│  ├─ 2022-09-01-Singhal-T32.md
│  ├─ 2022-09-14-ITCR-elevator-pitch.md
│  ├─ 2022-09-14-ITCR-poster-award.md
│  ├─ 2022-09-22-U24.md
│  ├─ 2022-10-17-B-ALL_paper.md
│  ├─ 2022-10-22-ctDNA_paper.md
│  ├─ 2022-12-15-CIViC_biodata_resource.md
│  └─ 2023-03-22-RegTools_paper.md
└─ _sass
   ├─ foundation-components
   │  ├─ _accordion.scss
   │  ├─ _alert-boxes.scss
   │  ├─ _block-grid.scss
   │  ├─ _breadcrumbs.scss
   │  ├─ _button-groups.scss
   │  ├─ _buttons.scss
   │  ├─ _clearing.scss
   │  ├─ _dropdown-buttons.scss
   │  ├─ _dropdown.scss
   │  ├─ _flex-video.scss
   │  ├─ _forms.scss
   │  ├─ _global.scss
   │  ├─ _grid.scss
   │  ├─ _icon-bar.scss
   │  ├─ _inline-lists.scss
   │  ├─ _joyride.scss
   │  ├─ _keystrokes.scss
   │  ├─ _labels.scss
   │  ├─ _magellan.scss
   │  ├─ _offcanvas.scss
   │  ├─ _orbit.scss
   │  ├─ _pagination.scss
   │  ├─ _panels.scss
   │  ├─ _pricing-tables.scss
   │  ├─ _progress-bars.scss
   │  ├─ _range-slider.scss
   │  ├─ _reveal.scss
   │  ├─ _side-nav.scss
   │  ├─ _split-buttons.scss
   │  ├─ _sub-nav.scss
   │  ├─ _switches.scss
   │  ├─ _tables.scss
   │  ├─ _tabs.scss
   │  ├─ _thumbs.scss
   │  ├─ _toolbar.scss
   │  ├─ _tooltips.scss
   │  ├─ _top-bar.scss
   │  ├─ _type.scss
   │  └─ _visibility.scss
   ├─ _01_settings_colors.scss
   ├─ _02_settings_typography.scss
   ├─ _03_settings_mixins_media_queries.scss
   ├─ _04_settings_global.scss
   ├─ _05_normalize.scss
   ├─ _06_typography.scss
   ├─ _07_layout.scss
   ├─ _09_elements.scss
   ├─ _10_asciidoc.scss
   ├─ _11_syntax-highlighting.scss
   └─ _functions.scss

```