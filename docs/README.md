<h3>Instructor</h3>
<table style="border-collapse: collapse; border: none;">
    <tr>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/fleischhacker_300x300.png" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Fleischhacker">Fleischhacker's Profile</a>
        </td>
    </tr>
</table>

<h3>Student Profiles</h3>
<table style="border-collapse: collapse; border: none;">
    <tr>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/HomaAghababaei.jpg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Aghababaei">Aghababaei's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/EvgenyBuskin.jpg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Buskin">Buskin's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/ZhiyuanDong.jpeg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Dong">Dong's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/GChen11111.jpg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/GChen">G. Chen's Profile</a>
        </td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/Sean_resized.png" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Guo">Guo's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/chenchuan.jpg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/He">He's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/Run Li.png" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Li">Li's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/Masoud.jpg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Neshastehriz">Neshastehriz's Profile</a>
        </td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/Tunmbi.jpg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Okediran">Okediran's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/ShiChen.png" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/SChen">S. Chen's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/riley.wagner.png" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Wagner">Wagner's Profile</a>
        </td>
        <td style="text-align: center; vertical-align: top; padding: 10px; width: 120px;">
            <img src="images/WentaoBrandyZou.jpg" style="width: 80px; height: 80px; object-fit: cover;"><br>
            <a href="markdownProfilePages/Zou">Zou's Profile</a>
        </td>
    </tr>
</table>

# The Most Ambitious Class on The Internet - FSAN830 Business Process Innovation

This repository documents the 'Innovation Track' of UD's Spring 2025 FSAN830 Business Process Innovation class. Our ambitious goal is to revolutionize horse racing predictions by implementing a state-of-the-art statistical model (BART) within an automated workflow, testing academic theory against real-world market outcomes. Through this public repository, students gain hands-on experience with modern DevOps practices, agile methodologies, and the power of having 'skin in the game' – skills essential for driving real-world innovation. By combining rigorous statistical analysis with industry-standard development practices, we're preparing students to make meaningful impacts in their future careers.

## Our Current Mission - XML to xarray Challenge

Our current mission is to convert race result XML data into a structured xarray dataset for analysis. This will allow us to perform sophisticated queries and analysis on horse racing data, preparing us for our ultimate goal of implementing BART models for race predictions.

### Code Organization

For this challenge, we'll use the following project structure:

```
fsan830spring2025/
├── data/
│   └── sampleRaceResults/
│       └── del20230708tch.xml
├── docs/
│   └── ...
└── students/
    ├── lastname_firstname/
    │   ├── xml_to_xarray.py
    │   └── query_results.py
    └── ...
```

Each student should:
1. Create a folder with your `lastname_firstname` under the `students/` directory
2. Place your Python scripts in this folder
3. Use relative paths in your code (e.g., `../../data/sampleRaceResults/del20230708tch.xml`)

This organization keeps your code separate from other students while maintaining a consistent project structure. When working on your solution:

1. **Sync your fork** with the main repository to get the latest structure:
   - Go to your fork on GitHub
   - Click the "Sync fork" button
   - Click "Update branch" to get the latest changes
   - Pull these changes to your local repository:
     * **Using Cursor**: Click the Source Control icon in the sidebar → Click ••• (More Actions) → Pull
     * **Using command line**: `git pull origin main`

2. **Set up your development environment**:
   - Clone your updated fork locally (if you haven't already)
   - Create a new branch for this challenge:
     * **Using Cursor**: Click the branch name in the bottom left corner → Select "Create new branch..." → Enter "xml-xarray-challenge"
     * **Using command line**: `git checkout -b xml-xarray-challenge`
   - Create your personal folder under `students/lastname_firstname/`

3. **Develop your solution**:
   - Work on your code in your personal folder
   - Test your code against the shared data file
   - Commit your changes regularly:
     * **Using Cursor**: Click the Source Control icon in the sidebar → Stage changes → Enter commit message → Click ✓ (Commit)
     * **Using command line**: `git add .` then `git commit -m "Your message"`

4. **Submit your work**:
   - Push your branch to your fork on GitHub:
     * **Using Cursor**: In Source Control view → Click ••• (More Actions) → Push
     * **Using command line**: `git push origin xml-xarray-challenge`
   - Update your profile page as described in the submission instructions
   - Create a pull request to the main repository

### XML to xarray Dataset Conversion Guide

Students will convert the provided XML race results file (`data/sampleRaceResults/del20230708tch.xml`) into an xarray dataset with the following dimensions:

1. **TRACK**: Coordinates include:
   - `trackID`: The track identifier (from the `CODE` element in the XML)
   - `trackName`: The track name (from the `n` element under `TRACK`)

2. **RACE_DATE**: The date of the races (from the `RACE_DATE` attribute in the `CHART` element)

3. **RACE_NUMBER**: The race number (from the `NUMBER` attribute in the `RACE` element)

4. **ENTRY**: Information about each horse entry, including:
   - `horse`: Horse name (from the `n` element under `ENTRY`)
   - `jockey`: Jockey name (combining `FIRST_NAME`, `MIDDLE_NAME`, and `LAST_NAME` under `JOCKEY`)
   - `trainer`: Trainer name (combining `FIRST_NAME`, `MIDDLE_NAME`, and `LAST_NAME` under `TRAINER`)

The dataset should also include relevant variables such as:
- Finishing position (`OFFICIAL_FIN`)
- Odds (`DOLLAR_ODDS`)
- Race purse (`PURSE`)
- Race distance (`DISTANCE`)
- Track condition (`TRK_COND`)

#### Implementation Steps:

1. Parse the XML file using Python's built-in `xml.etree.ElementTree` library
   ```python
   import xml.etree.ElementTree as ET
   
   # Path is relative to the repository root
   xml_path = 'data/sampleRaceResults/del20230708tch.xml'
   tree = ET.parse(xml_path)
   root = tree.getroot()
   ```

2. Extract the relevant data for each dimension and variable
3. Organize the data into appropriate data structures
4. Create an xarray Dataset with the proper dimensions and coordinates
5. Save the dataset in a suitable format (e.g., NetCDF)

#### Query Challenge:

Once the xarray dataset is created, students should implement a query that returns the top 3 horses in each race along with:
- Horse name
- Jockey name
- Trainer name
- Finishing position
- Odds

This query should demonstrate the power of xarray for multidimensional data analysis and provide a foundation for more complex analyses in the future.

#### Submission Instructions

To demonstrate completion of this challenge:

1. Update your profile page in the `markdownProfilePages/` directory to include a new section titled "XML to xarray Challenge"
2. In this section, include:
   - A brief explanation (2-3 sentences) of how you approached the XML to xarray conversion
   - A code snippet showing your query implementation for finding the top 3 horses in each race
   - Sample output from your query showing results from at least one race

3. Create a pull request with your updated profile page
   - Title your PR: "XML to xarray Challenge - [Your Name]"
   - In the PR description, briefly mention one insight you gained from working with the racing data

This approach allows you to publicly showcase your work while keeping the submission process streamlined. Your solution demonstrates your ability to work with complex data structures and implement practical queries on multidimensional datasets.

The completed dataset will serve as the foundation for our BART model implementation, allowing us to test academic theory against real-world market outcomes.

## [COMPLETED] Our First Mission - Class Pages

<span style="color:darkred; font-weight: bold">Pull Request Status Update: Several profile pages need corrections from the first round of pull requests. Common issues found:
1. Empty or incomplete profile pages
2. Images not properly formatted (must be exactly 300x300 pixels)
3. Images with incorrect aspect ratios (appearing stretched)

If you see the default horse avatar below instead of your photo, please follow the "Instructions for Profile Updates" section below to submit a new pull request with these corrections.</span>

Our first mission is to start populating this class website that will serve as a central hub for our class. We will use the internet to its fullest extent to accomplish this goal.

> Provide some details about yourself on your profile page and add a picture (80 x 80px). Ensure it includes some notion of your aspirations in using data science and mention any passions that might overlap with the course material.

### Instructions for Profile Updates

If you need to update your profile or image, follow these steps:

1. First, sync your fork with the main repository:
   - Go to your fork on GitHub
   - Click the "Sync fork" button
   - Click "Update branch" to get the latest changes

2. Update your local repository (choose either method):

   **Using Command Line:**
   ```bash
   # Switch to your main branch
   git checkout main
   
   # Pull the latest changes
   git pull origin main
   
   # Create a new branch for your updates
   git checkout -b profile-update-yourname
   ```

   **Using VS Code/Cursor:**
   - Click the Source Control icon in the left sidebar (or press Ctrl+Shift+G)
   - Click the three dots (...) menu
   - Select "Pull" to get latest changes
   - Click the branch name in the bottom left corner
   - Select "+ Create new branch" and name it "profile-update-yourname"

3. Make your updates:
   - Prepare your profile image:
     1. First crop your image to a perfect square (1:1 aspect ratio)
     2. Then resize the cropped image to exactly 300x300 pixels
     3. You can use tools like paint.net, GIMP, or online editors like pixlr.com
   - Place your image in the `docs/images` folder
   - Update your profile page in `docs/markdownProfilePages/YourName.md`
   - Test your changes locally if possible

4. Commit and push your changes (choose either method):

   **Using Command Line:**
   ```bash
   git add .
   git commit -m "Updated profile and image"
   git push origin profile-update-yourname
   ```

   **Using VS Code/Cursor:**
   - In Source Control, review your changes
   - Enter a commit message: "Updated profile and image"
   - Click the ✓ (Commit) button
   - Click "Publish Branch" or "Push"

5. Create a new pull request:
   - Go to the main repository on GitHub
   - Click "New Pull Request"
   - Choose "compare across forks"
   - Select your fork and new branch
   - Submit the pull request

Note: If you're having trouble, feel free to delete your fork entirely, create a new fork, and start fresh with these steps.

## Motivational Video

This video is perhaps the most important background video for the second half of our semester together.

[Link to Video](https://youtu.be/jsBpNCxxlNE?si=4LHByThKyIkbBJx1&t=5500)

<iframe width="560" height="315" src="https://www.youtube.com/embed/jsBpNCxxlNE?si=QiqzbgQRvpnYT1B1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

We will watch the above video in segments throughout the semester.

# Important Papers

* Hugh A. Chipman. Edward I. George. Robert E. McCulloch. *BART: Bayesian additive regression trees.* Ann. Appl. Stat. 4 (1) 266 - 298, March 2010.
* Hill, J. L. (2011). *Bayesian nonparametric modeling for causal inference.* Journal of Computational and Graphical Statistics, 20(1), 217-240.
* Hill, J., Linero, A., & Murray, J. (2020). *Bayesian additive regression trees: A review and look forward. Annual Review of Statistics and Its Application*, 7(1), 251-278.


## Beliefs

Observational Data:
* it is nearly impossible to correctly leverage statistical methods on **observational** data to make reliable predictions about **causal** effects, e.g. confounding, selection bias, garbage can regressions, etc.
* the only way to reliably make causal predictions is to leverage **interventional** data from properly conducted randomized experiments.
* observational data is not useless, but it is important to always be aware of the limitations of observational data and validate any causal predictions with interventional data.
* predictive models, while not perfect, are still useful for making predictions about future outcomes.

Feedback Loops:
* Academic institutions select for ideas that are novel and intellectually appealing rather than proven and resilient, creating an ecosystem where being impressively wrong is often more rewarded than being boringly correct.
* When scholars aren't required to place personal capital or reputation at risk, peer review becomes an exercise in academic aesthetics rather than a meaningful test of an idea's survival value.
* The filtering mechanisms of peer review and real-world implementation are fundamentally different - one selects for theoretical elegance and methodological rigor, while the other ruthlessly eliminates ideas that fail to deliver tangible results.

Goodhart's Law - when a measure becomes a target, it ceases to be a good measure:
* Scholars optimize for what's measurable (citations, h-index, publication count) rather than what's valuable (reproducibility, real-world impact, practical utility), creating an avalanche of technically sophisticated but fundamentally hollow research.
* The academic incentive system has become a perfect example of the very phenomenon it should study - the complete divergence of proxy measures from the underlying quality they were meant to track.

Horse racing will be our laboratory:
* Racing markets represent a rare interventional laboratory where probabilistic predictions face immediate financial consequences - models that fail to capture real relationships are rapidly punished through capital destruction, unlike in traditional academic settings.
* Horse racing data provides a perfect testing ground because the environment combines genuine uncertainty, rapid feedback cycles, and most importantly, skin in the game through betting markets that force probabilistic estimates to survive contact with reality.
* The use of horse racing data cleverly sidesteps the traditional academic trap of optimizing for mathematical elegance over practical validity - a model's success or failure is determined not by peer review, but by its ability to generate predictions that survive in a competitive market environment.

Bayesian Additive Regression Trees (BART):
* BART is a non-parametric regression model that uses Bayesian inference to estimate the relationship between a dependent variable and one or more independent variables.
* BART is, to me, the most promising new development in statistical modeling, it has performed extremely well in causal inference competitions (google Atlantic Causal Inference Competition).

Our innovation:
* We will use BART to make predictions about horse racing outcomes.
* We will then use the predictions to make bets on horse racing outcomes.
* We will then evaluate the performance of the model.
* Through real-world application, we will discover and patch many holes in the academic literature on BART while validating its practical utility.

Why horse racing and not say, the stock market?

* Faster Feedback Cycles
  * Horse races provide immediate feedback - typically within minutes. Stock market strategies often require months or years to validate due to noise and the need for sufficient sample size. This rapid feedback allows for faster iteration and learning.
* Horse racing has fewer confounding variables compared to stocks. 
  * While still complex, the key variables (track conditions, horse history, jockey, etc.) are more bounded and measurable. Stock prices are affected by countless global factors, making it harder to isolate the effectiveness of your modeling approach.
* Market Inefficiencies
  * The horse racing market tends to be less efficient than major stock markets. Large institutional investors and algorithmic traders have largely eliminated easily exploitable patterns in stocks. Horse racing still has more retail participants and potential inefficiencies that a good model could identify.
* Data Quality and Accessibility
  * Horse racing data tends to be more standardized and complete within its domain. While stock market data is abundant, the truly valuable predictive signals are often private or expensive. The playing field is more level in horse racing data.
* Lower Capital Requirements
  * You can test betting strategies with relatively small amounts of capital and get statistically significant results. Testing stock market strategies often requires substantial capital to overcome transaction costs and achieve meaningful sample sizes.
* Independence Between Events
  * Each horse race is largely independent of other races. Stock market moves are highly correlated across securities and time periods, making it harder to build a robust sample size of truly independent observations.




















