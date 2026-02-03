IDEA ONE: June 2024 NJ Voter Registration https://nj.gov/state/elections/assets/pdf/svrs-reports/2024/2024-1105-voter-registration-by-congressional-district.pdf
January 2026 NJ Voter Registration https://nj.gov/state/elections/assets/pdf/svrs-reports/2026/2026-01-voter-registration-by-congressional-district.pdf
We have a special election coming up in NJ-11. The primary is in early February. How does the voterbase look different from the last primary vote? I would take just the 11th district rows from each set. I would note that part of the change is due to redistricting. 

IDEA TWO:I found a data set from the Norfolk Animal Care and Adoption Center (NACC) in Virginia. They have lots of information on the animals themselves (sex, spay/neuter status, breed, color, age) and how they arrived at the shelter (animal control, owner surrender) and what happened to them as they left (adoption, foster). They also have intake and outtake dates.  

I made a pivot table that breaks animals down by species, and the outcomes resulting from each intake category. I found this interesting. Most animals who were brought in to be euthanized were, but what is the story of Peanut, the 14-year-old Parson Russell Terrier who was adopted six weeks later instead?

There’s also a livestock category – they’re all pigs. I wonder what other livestock they maybe get that they don’t just have a pig specific classification. I also am not positive about the best way to go about it, but I’d like to figure out which specific animals are going to the NACC the most often – I noticed a cat named Meatloaf made multiple visits. This could be done using the unique animal IDs. 

I figured it out – I made a pivot table with the animal IDs and counts and then sorted it from highest to lowest. A vizsla named Eddie made 17 visits to the NACC. He seems to have been fostered a bunch of different times. Ten of the visits are labeled as “field trip” for the outcome subtype which I’d like to know more about. I’d be interested in looking into the most common animal names and breeds but I am not sure how to handle the need to filter out a dog like Eddie who is one individual making 17 trips — there aren’t 17 different vizslas named Eddie, but there are a few different dogs named Achilles. I think I should be able to use the animal IDs to filter out duplicates. https://data.virginia.gov/dataset/norfolk-animal-care-and-adoption-center-nacc1 
<img width="260" height="231" alt="Screen Shot 2026-02-03 at 6 36 41 PM" src="https://github.com/user-attachments/assets/e433b9b6-6021-48ca-afda-443ff9f7722e" />

<img width="821" height="230" alt="Screen Shot 2026-02-03 at 6 36 07 PM" src="https://github.com/user-attachments/assets/a7af093b-9245-4ab4-b05e-accf9221c6aa" />

These are animals who visited NACC by breed filtered by the ones named either Lady Penelope, Penelope or Penelope Pitstop. It looks ugly but I expanded it with filters by animal ID – there seems to only be one Rabbit named Penelope, she just made a few stops.


