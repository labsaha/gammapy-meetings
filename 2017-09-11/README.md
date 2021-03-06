# Gammapy Telcon

* Thursday, September 11, 2017 at 10 am
* CTA eZuce, password "gammapydc"
* Anyone interested welcome to join! Contributions welcome!

# Agenda

* Gammapy update (Christoph)
  * "Gammapy - A prototype for the CTA science tools" ICRC 2017 proceeding out (see https://arxiv.org/abs/1709.01751)
  * Progress in the past months: http://docs.gammapy.org/en/latest/changelog.html
  * Would like to cut Gammapy 0.7 release at the end of this week.
* CTA 1DC update (Roberta or Christoph)
  * Released August 30 via email to all CTA members
  * https://forge.in2p3.fr/projects/data-challenge-1-dc-1/wiki
  * http://gammapy.org/goto/#gammapy-cta-1dc-docs
  * Started to write a new notebook: [cta_1dc_introduction.ipynb](http://nbviewer.jupyter.org/github/gammapy/gammapy-extra/blob/master/notebooks/cta_1dc_introduction.ipynb)
  * Plan is to have (at least) two notebooks for next week: introducation & analysis. Help / more notebooks welcome!
  * Started to do a few checks / all-sky maps here: https://github.com/gammasky/cta-dc/tree/master/data
* Sensitivity computation (Bruno)
  * `from gammapy.scripts import SensitivityEstimator`
  * Slides: [Meeting_DC_20180911.pdf](Meeting_DC_20180911.pdf)
* Next steps (All)
  * High-priority developments needed: Background3D class & Model classes with XML
  * CTA PHYS meeting next week (Sep 18-20):
    * https://indico.cta-observatory.org/event/1471/?ovw=True
    * Anyone have time to run a Gammapy analysis and present first impressions?
    * Are there things we can fix in Gammapy quickly this week to support 1DC?
  * Gammapy coding sprint next week (Sep 21-22):
    * See infos at [2017-09_Heidelberg.md](../2017-09_Heidelberg.md) 
    * What should be our main focus and goal(s)? Short discussion now or next week?
  * Anyone willing to be "manager" for writing the
    Gammapy paper?
    * Your role would be to drive the effort by organising discussions, distributing tasks, reviewing pull requests as they come in (i.e. somewhat of an editor role), set a timeline and goal and make sure it gets done.
    * You don't have to have lots of contributions to the Gammapy code or have the time or ambition to produce a lot of text / code examples / figures yourself.
    * The paper should be relatively short and a "minimum complete draft" be ready within ~ a month. Github repo already exists: https://github.com/gammapy/gammapy-paper
