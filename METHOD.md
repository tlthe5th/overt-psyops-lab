# #OvertPsyops Forensic Scoring & Quadrant Method (Pre-Committed Rules)

To ensure complete transparency of method (*φανερός*) and prevent post-hoc tuning, all logged entries in this laboratory adhere to these fixed definitions.

## 1. The Five-Point Λόγος (Logic) Verification Safeguard
A post is classified as **Verified ἀλήθεια (Truth)** only if it satisfies all five criteria:
1. **Scriptural Alignment:** Verified against primary Greek texts (**Septuagint / LXX** and **Greek New Testament**) without internal contradiction.
2. **Logical Soundness:** Free of fallacies, non-sequiturs, or manipulative framing.
3. **Primary Documentation:** Grounded in verifiable primary records, dates, or direct quotes rather than rumor.
4. **Conscience-Directed (*συνείδησις*):** Aims to illuminate reality rather than provoke cheap outrage.
5. **Devoid of Malice:** Exposes systems and actions (*ἔργα*) without personal cruelty or slander.

## 2. Reach Ratio & Baseline Formula
* **Post Reach Ratio ($R$):**  
  $$R = \frac{\text{Total Views}}{\text{Follower Count at Time of Capture}}$$
* **Account Baseline ($B$):** The **median** Reach Ratio ($R$) across the account's previous 20 normal posts.
* **Relative Reach Performance ($P$):**  
  $$P = \frac{R}{B} \times 100\%$$
  * **Normal Reach:** $P \ge 50\%$ of baseline.
  * **Collapsed Reach (Suppressed):** $P < 50\%$ of baseline (with severe throttling defined as $P < 15\%$).

## 3. The Four-Quadrant Classification
* **Quadrant 1:** Unverified content + Normal reach ($P \ge 50\%$)
* **Quadrant 2:** Unverified content + Low reach ($P < 50\%$)
* **Quadrant 3:** Verified **ἀλήθεια** (Truth) + Normal reach ($P \ge 50\%$)
* **Quadrant 4 (Documented Suppression Signature):** Verified **ἀλήθεια** (Truth) + Collapsed reach ($P < 50\%$)

## 4. Cryptographic Integrity & Timestamping
Every logged entry generates a local **SHA-256 hash** of the screenshot file directly in the user's browser and exports a structured JSON receipt. Receipts committed to `/ledger` are anchored via **OpenTimestamps (`.ots`)** so timestamp verification relies on an independent public ledger rather than Git commit metadata alone.
