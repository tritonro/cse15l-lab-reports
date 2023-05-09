# Lab Report 3
by Rosario Ortiz

## Alternate Uses for Grep 

### -r 
This option allows you to search for a pattern in all files in a directory (and any subdirectories) recursively, and print any lines that contain the pattern.

example 1
```
$ grep -r biophysics
./technical/plos/journal.pbio.0020067.txt:        College London's physics department and director of a biophysics research unit sponsored by
./technical/plos/journal.pbio.0020012.txt:        Kenyon, professor of biochemistry and biophysics at the University of California at San
./technical/biomed/gb-2001-2-4-research0012.txt:          expression and membrane biophysics
./technical/biomed/gb-2001-2-4-research0012.txt:        biophysics of ion transport. The value of such
./technical/biomed/gb-2001-3-1-research0001.txt:        understanding of the biophysics of water flow across plant
```
 In this example, grep recursively searches every directory in the working directory (docsearch), and returns all the files that contain the given string. Below each file path, grep -r prints the line that contains the string being searched for. 
 
example 2
```
technical/government/Media/Law_Schools.txt:York Law School, University of New Mexico School of Law, Thomas M.
technical/government/Media/Law_Schools.txt:Law Schools and a professor of law at Stanford University, also
technical/government/Media/Raising_the_Bar.txt:High School and Central Michigan University and had a
technical/government/Media/Raising_the_Bar.txt:career, with a law degree from the University of North
technical/government/Media/Helping_Hands.txt:Wesleyan University for pro bono and student services.
technical/government/Media/Survey.txt:Kristin Booth Glen, dean of the City University of New York
technical/government/Media/Survey.txt:Southeastern University in Fort Lauderdale, Fla., is likewise
technical/government/Media/Law-school_grads.txt:It is a source of frustration, said Libby DeBlasio, a University
technical/government/Media/Law-school_grads.txt:half her tuition at Northeastern University's law school in
technical/government/Media/Law-school_grads.txt:At the state's largest law school, the University of Denver,
technical/government/Media/Law-school_grads.txt:By comparison, tuition at the University of Colorado Law School
technical/government/Media/Law-school_grads.txt:University and the University of Colorado to fill the number of
technical/government/Media/Texas_Lawyer.txt:University of Texas School of Law, which is participating in the
technical/government/Media/Texas_Lawyer.txt:Antonio, where St. Mary's University School of Law students man the
technical/government/Media/Kiosks_for_court_forms.txt:A University of California, Irvine, study released Wednesday
technical/government/Media/Terrorist_Attack.txt:at the Manhattan campus of Fordham University School of Law.
technical/government/Media/Terrorist_Attack.txt:University of New York campus in Buffalo on Oct. 15; and at Albany
technical/government/Media/Terrorist_Attack.txt:of the City University of New York School of Law.
technical/government/Media/Terrorist_Attack.txt:Georgetown University Law Center, said the good economic times of
technical/government/Media/Ginny_Kilgore.txt:University of Mississippi School of Law's 2002 Public Service
technical/government/Media/Poverty_Lawyers.txt:36, a 1997 graduate of New York University School of Law.
technical/government/Media/Poverty_Lawyers.txt:When he was at the University of Virginia School of Law in the
technical/government/Media/Avoids_Budget_Cut.txt:from the University of Alabama School of Law because she wanted to
technical/government/Media/Assuring_Underprivileged.txt:LOS ANGELES - As an undergraduate at Cornell University, Laurie
technical/government/Media/Assuring_Underprivileged.txt:University in 1974 and then attended Harvard Law School.
technical/government/Media/Boone_legal_service.txt:the county didn't need it. Drake University ended its funding after
technical/government/Media/Barnes_Volunteers.txt:Emory University political science professor Merle Black said.
technical/government/Media/Texas_Supreme_Court.txt:doctorate in jurisprudence from Southern Methodist University
technical/government/Media/Low-income_children.txt:University of Southern Maine completes a three-year evaluation of
technical/government/Media/Marylands_Legal_Aid.txt:several come to mind: the Terps, the Johns Hopkins University and
technical/government/Media/Marylands_Legal_Aid.txt:law professor at the University of Maryland and a former deputy
technical/government/Media/Attorney_gives_his_time.txt:University of Florida's law school at the same time as Richard.
technical/government/Media/GreensburgDailyNews.txt:his bachelor's degree from the University of Indianapolis in 1978
technical/government/Media/GreensburgDailyNews.txt:and a jurisprudence doctorate from Indiana University-Indianapolis
technical/government/Media/Major_Changes.txt:Michael W. Martin, a Fordham University School of Law professor
technical/government/Media/Wilmington_lawyer.txt:Widener University School of Law. The award was given to Conner
technical/government/Media/CommercialAppealMemphis2.txt:attorneys, 26 office workers and 21 University of Memphis third-
technical/government/Media/CommercialAppealMemphis2.txt:Larry Pivnick, law professor at the University of Memphis Law
technical/government/Media/Valley_Needing_Legal_Services.txt:University.
technical/government/Media/Legal_Aid_attorney.txt:when she entered law school at Georgetown University that she
technical/government/Media/Entities_Merge.txt:University Law School to involve students at the University of
technical/government/Media/Bridging_legal_aid_gap.txt:Lash is associate dean at the University of Southern California
technical/plos/journal.pbio.0030032.txt:        Applied Biosciences from the University of Arizona, who believes his PSM makes him more
technical/plos/journal.pbio.0030032.txt:        University in the Netherlands, for example, students can now add a “science-based business”
technical/plos/journal.pbio.0030032.txt:        the Applied Biosciences PSM program at the University of Arizona.
technical/plos/journal.pbio.0030032.txt:        at the University of Arizona, and others make the case that PSMs may protect students'
technical/plos/journal.pbio.0020183.txt:        University of Bath, United Kingdom.“If you were a single-celled alga sitting in a pond, you
technical/plos/journal.pbio.0020183.txt:        a geneticist at the University of Waageningen in the Netherlands.
technical/plos/journal.pbio.0020183.txt:        parents— argues Joel Parker of the University of Lausanne, Switzerland.
technical/plos/journal.pbio.0020183.txt:        says Brian Charlesworth of the University of Edinburgh. “We've reached the point of two
technical/plos/journal.pbio.0020035.txt:        Khosla laboratory at Stanford University describe significant advances in understanding
technical/plos/pmed.0020067.txt:        testing units at the George Washington University, London School of Hygiene and Tropical
technical/plos/journal.pbio.0030024.txt:        at Washington University in St. Louis, Missouri, likens the current genetic map of the
technical/plos/journal.pbio.0030024.txt:        Arthur Toga, a neuroscientist at the University of California, Los Angeles, and Allen Brain
technical/plos/journal.pbio.0030024.txt:        experiments,” says Nobel laureate and Columbia University neuroscientist Eric Kandel. “The
technical/plos/journal.pbio.0030024.txt:        accommodate environmental differences,” says Rob Williams, neurobiologist at the University
technical/plos/journal.pbio.0020145.txt:        interacting with investigators at the University of California, San Francisco, while taking
technical/plos/pmed.0020103.txt:        according to Stanford University Institutional Review Board guidelines.
technical/plos/pmed.0020103.txt:          Denmark); mouse anti-glucokinase, 1:200 (C. Newgard, Duke University, Durham, North
technical/plos/pmed.0020103.txt:          All animal studies were performed in accordance with Stanford University Animal Care
technical/plos/journal.pbio.0020150.txt:        Magnetic Resonance Imaging Research Center at Columbia University, fMRI represents a
technical/plos/journal.pbio.0020150.txt:        Associate Professor of Psychology at Stanford University, has shown that distinct
technical/plos/journal.pbio.0020150.txt:        Langleben, Assistant Professor of Psychiatry at the University of Pennsylvania School of
technical/plos/pmed.0020062.txt:        Johnson Medical School and Georgetown University, (2) private foundations, such as the
technical/plos/pmed.0020062.txt:        University of New South Wales in Sydney has an active program aimed at increasing cultural
technical/plos/pmed.0020062.txt:        competency, both among medical students at the University and in the country's medical
technical/plos/pmed.0020060.txt:        allowed researchers at the University of Granada to borrow the bones for a DNA study. Being
technical/plos/pmed.0010028.txt:          Institute (NCI; Bethesda, Maryland, United States) and the Los Angeles County/University
technical/plos/pmed.0010028.txt:          approved by Stanford University's Institutional Review Board. Peripheral blood
technical/plos/pmed.0010028.txt:          at the University of Southern California Norris Cancer Center (Los Angeles, California,
technical/plos/pmed.0020115.txt:        PLoS Medicine Seung Kim and colleagues from Stanford University suggest
technical/plos/journal.pbio.0020147.txt:        Princeton University Press, is a work of advocacy in which the authors argue that
technical/plos/pmed.0020210.txt:        University of North Carolina. With funding from the Bill and Melinda Gates Foundation, more
technical/plos/pmed.0020210.txt:        leadership of Dr. Donald Krogstad and colleagues at Tulane University. Here, without an
technical/plos/pmed.0020210.txt:        in Parasitic Diseases at the University of California, San Francisco (UCSF). Here,
technical/plos/pmed.0020210.txt:        described above are now functional or in late planning stages at the University of
technical/plos/pmed.0020210.txt:        Washington, Johns Hopkins University, Harvard University, and the University of Dundee. In
technical/plos/journal.pbio.0020054.txt:        In a recent paper in Science, Michigan State University Amazon expert Mark Cochrane
technical/plos/journal.pbio.0020054.txt:        tools,” charges Ernesto Alvarado, a research scientist at the University of Washington in
technical/plos/journal.pbio.0020054.txt:        techniques, says Amazonian ecologist Carlos Peres at the University of East Anglia in the
technical/plos/journal.pbio.0020054.txt:        lowlands, and major wilderness areas. University of Port Elizabeth botanist Richard
technical/plos/journal.pbio.0020337.txt:        University in Canberra. I am studying the micromechanics of this process from a theoretical
technical/plos/journal.pbio.0020121.txt:        University in Fort Collins. He's been scientifically involved with BSE, since it was first
technical/plos/journal.pbio.0020121.txt:        it you have,” says veterinary pathologist Beth Williams of the University of Wyoming in
technical/plos/journal.pbio.0020121.txt:        States Geological Survey–Wisconsin Cooperative Wildlife Research Unit at the University of
technical/plos/journal.pbio.0020121.txt:        their mating status. University of Wisconsin soil science professor Joel Pedersen has
technical/plos/journal.pbio.0030050.txt:        the pile when it comes to relative brain size”, notes geneticist Bruce Lahn (University of
technical/plos/journal.pbio.0030050.txt:        Paleoanthropologist Ralph Holloway (Columbia University, New York, United States) uses
technical/plos/journal.pbio.0030050.txt:        systems neurobiologist Jon Kaas (Vanderbilt University, Nashville, Tennessee, United
technical/plos/journal.pbio.0030050.txt:        Robin Dunbar (University of Liverpool, United Kingdom), “people thought that the ability to
technical/plos/journal.pbio.0030050.txt:        geneticist Geoffrey Woods (University of Leeds, United Kingdom), wondered whether the genes
technical/plos/journal.pbio.0030050.txt:        Henrik Kaessmann (University of Lausanne, Switzerland) studies the origin of new genes in
technical/plos/journal.pbio.0030050.txt:        neurobiologist Todd Preuss (Yerkes Primate Research Center, Emory University, Atlanta,
technical/plos/pmed.0020161.txt:          Studies Hybridoma Bank (University of Iowa, Iowa City, Iowa, United States); CD73, CD44,
technical/plos/journal.pbio.0020053.txt:        dead yet: in October, researchers at the University of Wisconsin at Madison reported a new
technical/plos/journal.pbio.0020053.txt:        Walsh collaborates with Chaitan Khosla of Stanford University on finding ways to make
technical/plos/journal.pbio.0020053.txt:        genomes,” says Lucy Shapiro of Stanford University School of Medicine. While having full
technical/plos/journal.pbio.0020053.txt:        biochemist Stephen J. Benkovic of Pennsylvania State University. They didn't know the
technical/plos/journal.pbio.0020053.txt:        few held on, like Ry Young of Texas A&M University, who has made phage-induced cell
technical/plos/journal.pbio.0020053.txt:        Rockefeller University. Phage are also antigenic, and the antibodies they stimulate will
technical/plos/journal.pbio.0030056.txt:        University in the United Kingdom. If you think you've sequenced some dinosaur DNA, the
technical/plos/journal.pbio.0030056.txt:        says Michael Bunce, an anthropologist at MacMaster University in Ontario, Canada. Analysis
technical/plos/journal.pbio.0030056.txt:        Brown, the paleoanthropologist at the University of New England in Armidale, Australia, who
technical/plos/journal.pbio.0030056.txt:        But Russell Vreeland, a microbiologist at West Chester University in Pennsylvania and
technical/plos/journal.pbio.0030056.txt:        University of Arizona. “[The criteria] can both hinder the publication of good studies that
technical/plos/journal.pbio.0020440.txt:        questions almost on a weekly basis,” says James Gillooly, of the University of New Mexico,
technical/plos/journal.pbio.0020440.txt:        the University of Aberdeen. “It would provide a common functional basis for all
technical/plos/journal.pbio.0020440.txt:        But in 1932, Max Kleiber, an animal physiologist working at the University of
technical/plos/journal.pbio.0020440.txt:        University of New Mexico, Albuquerque, and his graduate student Brian Enquist, now at the
technical/plos/journal.pbio.0020440.txt:        University of Arizona, Tucson—and a physicist, Geoffrey West of the Santa Fe Institute,
technical/plos/journal.pbio.0020440.txt:        Kozlowski, of Jagiellonian University, Krakow, and Marek Konarzewski of the University of
technical/plos/journal.pbio.0020440.txt:        altitude, and diet, Brian McNab, of the University of Florida, Gainesville, has explained
technical/plos/journal.pbio.0020440.txt:        researchers from Princeton University and the Institute of Zoology in London, published a
technical/plos/journal.pbio.0020440.txt:        the University of Georgia, is one of the architects of another idea causing a stir among
technical/plos/pmed.0010062.txt:          The institutional review board of the University of Wisconsin Medical School approved
technical/plos/pmed.0010047.txt:        says Adrian Hill (University of Oxford, United Kingdom), the lead investigator of the
technical/plos/journal.pbio.0030105.txt:        at the University of California at Berkeley, it brought together a typically motley
technical/plos/journal.pbio.0030105.txt:        underlie these responses? And as the primatologist Frans de Waal (Emory University)
technical/plos/journal.pbio.0030105.txt:        The psychologist Paul Ekman (University of California at San Francisco) brought the
technical/plos/journal.pbio.0030105.txt:        cognitive neuroscientist Ray Dolan (University College London) to study the neural activity
technical/plos/journal.pbio.0030105.txt:        Physiologist Vittorio Gallese (University of Parma) prompted many nods of satisfaction
technical/plos/journal.pbio.0030105.txt:        Alice O'Toole (University of Texas at Dallas) gave to facial characteristics are supposed
technical/plos/journal.pbio.0030105.txt:        Virginia University) described when we view simple movements is ultimately meant to explain
technical/plos/journal.pbio.0030105.txt:        by the conference organizer, Semir Zeki [University College London]). But the richness of
technical/plos/pmed.0020018.txt:          [30,31] and were generous gifts from Liqun Luo (Stanford University). Fugene 6 was
technical/plos/pmed.0020018.txt:          University of Chicago, Chicago, Illinois, United States) were maintained in DMEM, 10%
technical/plos/journal.pbio.0020116.txt:        of the Council chairman, Leon Kass of the University of Chicago, and of the President of
technical/plos/pmed.0010045.txt:          and 30 and on no medications, were studied. The University of Pennsylvania Institutional
technical/plos/pmed.0010045.txt:          University of Pennsylvania for a 60 h stay. Serial blood samples were collected during
technical/plos/pmed.0010045.txt:          cardiovascular diseases, were recruited through the diabetes clinics at the University of
technical/plos/pmed.0010045.txt:          evaluated at the University of Pennsylvania General Clinical Research Center in a fasting
technical/plos/pmed.0010045.txt:          state at 8 AM. The University of Pennsylvania Institutional Review Board approved the
technical/plos/journal.pbio.0020113.txt:        marine biologist from the University of Cape Town (Cape Town, South Africa). Meryl
technical/plos/journal.pbio.0020113.txt:        fished species,” notes Jeff Hutchings, a conservation biologist at Dalhousie University
technical/plos/journal.pbio.0020113.txt:        however, prompted Worm and his Dalhousie University colleague Ransom Myers to question the
technical/plos/journal.pbio.0020113.txt:        Daniel Pauly, a fisheries biologist at the University of Vancouver (Vancouver, British
technical/plos/journal.pbio.0020113.txt:        A review of 89 studies of MPAs by Ben Halpern, a student at the University of
technical/plos/journal.pbio.0020310.txt:        are dispersed,’ says Andrew Balmford, a conservation biologist at the University of
technical/plos/journal.pbio.0020310.txt:        Johan du Toit of the Mammal Research Institute at the University of Pretoria in South
technical/plos/journal.pbio.0020310.txt:        stem this exploitation, argues Paul Ferraro, an economist at Georgia State University in
technical/plos/journal.pbio.0020310.txt:        Sjaak Swart of the Section of Science and Society at Groningen University in The
technical/plos/journal.pbio.0020064.txt:        field, including collaborators Charles Zuker (University of California, San Diego [UCSD],
technical/plos/journal.pbio.0020064.txt:        researchers at the University of Miami (Florida, United States) School of Medicine in 2000.
technical/plos/journal.pbio.0020064.txt:        Commenting on these recent discoveries, taste expert Linda Bartoshuk (Yale University
technical/plos/journal.pbio.0020064.txt:        Physiologist John DeSimone (Virginia Commonwealth University, Richmond, Virginia, United
technical/plos/journal.pbio.0020064.txt:        University, Fort Collins, Colorado, United States) explains the two theories of
technical/plos/journal.pbio.0020064.txt:        (Duke University, Durham, North Carolina, United States), ‘the onus is now on people who
technical/plos/pmed.0010056.txt:        such as the University of California at San Francisco's Tropical Disease Research Unit (San
technical/plos/journal.pbio.0020306.txt:        about a millimetre’, says ecologist Mary Ann Tiffany (San Diego State University,
technical/plos/journal.pbio.0020306.txt:        Richard Gordon, Professor of Radiology at the University of Manitoba in Winnipeg,
technical/plos/journal.pbio.0020306.txt:        explains Michael Sussman, Director of the Biotechnology Center at the University of
technical/plos/journal.pbio.0020306.txt:        chemical engineer Tony Rogers, an assistant professor at Michigan Technological University
technical/plos/journal.pbio.0020306.txt:        Oceanographer Ginger Armbrust (University of Washington, Seattle, Washington, United
technical/plos/journal.pbio.0030129.txt:        (University of California, United States) for 
technical/plos/journal.pbio.0020071.txt:        Their book is one of a series of short introductions, published by Oxford University
technical/plos/journal.pbio.0020267.txt:        Neuropsychiatric Institute of the University of California at Los Angeles (UCLA) (Los
technical/plos/journal.pbio.0020267.txt:        the University of California at Davis Medical Center in Sacramento (California, United
technical/plos/journal.pbio.0020267.txt:        University of Washington in Seattle (UW) (Seattle, Washington, United States) has reached
technical/plos/journal.pbio.0020267.txt:        neuroscientist at San Diego State University (San Diego, California, United States) sees a
technical/plos/journal.pbio.0020267.txt:        the University of Louisville (Louisville, Kentucky, United States) shows that the
technical/plos/journal.pbio.0020267.txt:        Eric Courchesne and colleagues at University of California, San Diego (San Diego,
technical/plos/journal.pbio.0020214.txt:        Institute of Physico-Chemical Biology of Moscow State University in Moscow, Russia. This
technical/plos/journal.pbio.0020214.txt:        University [Moscow, Russia] cycle on oncology and immunology sponsored by LICR;
technical/plos/pmed.0020118.txt:        medical schools of the University of Cambridge and University of California at San
technical/plos/pmed.0020118.txt:        cohort of 77 doctors who graduated from the University of Makere, Uganda, in 1983, 22 had
technical/plos/pmed.0010024.txt:        childhood malaria remains to be defined,” says Nick White (Mahidol University, Thailand),
technical/plos/pmed.0020045.txt:          provided by Fuad Ziyadeh (University of Pennsylvania, Philadelphia, Pennsylvania, United
technical/plos/pmed.0020045.txt:          University Hospital.
technical/plos/pmed.0020090.txt:        PLoS Medicine , John Danesh and colleagues from the University of
technical/plos/journal.pbio.0020161.txt:        of molecular cell biology at the University of Göttingen and president of the Max Planck
technical/plos/journal.pbio.0020161.txt:        mathematical biology at the University of Oxford, president of the Royal Society, and
technical/plos/journal.pbio.0020404.txt:        Lorna Role and her colleagues at Columbia University in New York City. “In 1995, we turned
technical/plos/journal.pbio.0020404.txt:        Sherry Leonard and Robert Freedman of the University of Colorado in Denver, Colorado, have
technical/plos/journal.pbio.0020404.txt:        Paul Newhouse and his colleagues at the University of Vermont in Burlington, Vermont,
technical/plos/journal.pbio.0020404.txt:        Ming Li and his colleagues at the University of Texas in San Antonio, Texas, are
technical/plos/journal.pbio.0020404.txt:        The University of Texas researchers have scoured the literature for genes related to
technical/plos/journal.pbio.0020148.txt:        neurobiologist Judith Eisen (University of Oregon, Eugene, Oregon, United States), ‘who
technical/plos/journal.pbio.0020148.txt:        Developmental Genetics at University College London (United Kingdom). GFP lines can be made
technical/plos/journal.pbio.0020148.txt:        developmental neurobiology group leader at University College London, he plans to analyse
technical/plos/journal.pbio.0020148.txt:        Developmental geneticist Didier Stainier (University of California, San Francisco,
technical/plos/journal.pbio.0020028.txt:        University College of Physicians and Surgeons in New York City. Stein has researched
technical/plos/journal.pbio.0020010.txt:        by my institution, University College London, in joining JSTOR before the JISC deal was
technical/plos/journal.pbio.0020213.txt:        University (Wooster, Ohio, United States), these destructive organisms present an exciting
technical/plos/journal.pbio.0020213.txt:        Adjunct Professor of Mycology and Forest Pathology at the University of California at
technical/plos/journal.pbio.0020213.txt:        Beagle Ristaino of North Carolina State University (Raleigh, North Carolina, United States)
technical/plos/journal.pbio.0020172.txt:        Department of Psychology at Rutgers University to establish the Laboratory of Vision
technical/plos/journal.pbio.0020012.txt:        mathematical modeller at the University of California at Santa Cruz. “Since 1840, life
technical/plos/journal.pbio.0020012.txt:        Kenyon, professor of biochemistry and biophysics at the University of California at San
technical/plos/journal.pbio.0020012.txt:        University of California at Davis and his research, on the effect on life expectancy of
technical/biomed/1471-2350-4-3.txt:            and the University of Alabama at Birmingham, and the
technical/biomed/1471-2172-3-4.txt:          pathogen-free facility at the University of Alabama at
technical/biomed/1471-2172-3-4.txt:          (Applied Biosystems, Foster City, CA; University of
technical/biomed/1471-2172-3-4.txt:          Dr. J. DeGregori (University of Colorado Health Science
technical/biomed/gb-2002-4-1-r2.txt:          Stanford University using standard techniques [ 62]. All
technical/biomed/1471-2466-1-1.txt:        study. All the patients were treated at the University
technical/biomed/1471-2466-1-1.txt:        from April 1, 1995, through March 31, 1998. The University
technical/biomed/1471-2466-1-1.txt:        affiliated with the University of Florida. The study was
technical/biomed/1471-2202-2-9.txt:          University of Cincinnati vivarium in accordance with the
technical/biomed/1471-2091-2-10.txt:          Leiden (University of Chicago) in the pUC18 vector. CD98
technical/biomed/gb-2003-4-4-r24.txt:          Medicine Research Committee of the University of
technical/biomed/1471-213X-2-1.txt:            Use Committee of Columbia University.
technical/biomed/1471-213X-2-1.txt:            provided by Dr. Lester Binder, University of Alabama at
technical/biomed/1471-213X-2-1.txt:            generously provided by Dr. R. Brackenbury (University
technical/biomed/1471-213X-2-1.txt:            University, NY, NY) and used at 1:1000. MAP4 is the
technical/biomed/1472-6882-3-3.txt:          for Complementary and Alternative Medicine (University of
technical/biomed/ar319.txt:          Review Board at the Mayo Clinic and at the University of
technical/biomed/ar319.txt:          at the University of California, Santa Cruz
technical/biomed/1471-2156-4-5.txt:          Transport, Department of Internal Medicine, University of
technical/biomed/1471-2431-2-1.txt:          University in Brno, Czech Republic. Inclusion criteria
technical/biomed/1476-4598-2-22.txt:          Dickinson, San Jose, CA) in the University of California,
technical/biomed/1471-2334-3-9.txt:          Dr. Mark Feinberg (Emory University). The IHD-J strain
technical/biomed/1471-2164-2-8.txt:          University, St. Louis), and the secondary antisera was
technical/biomed/1471-2202-2-8.txt:          Sprague-Dawley Rats (maintained in the University of
technical/biomed/1471-2156-3-10.txt:        University of Minnesota. Originally, the 
technical/biomed/1477-7525-1-9.txt:          proposal was approved by the University of South Florida
technical/biomed/gb-2002-4-1-r1.txt:          University of California Santa Cruz golden path server.
technical/biomed/1471-2407-3-18.txt:        after the Witness Project at the University of Arkansas.
technical/biomed/1471-2229-2-3.txt:          Center, Ohio State University, Columbus OH. Seeds were
technical/biomed/gb-2001-2-7-research0025.txt:          (Baylor University) (version 1) [ 71]; GenBank CDS (NCBI)
technical/biomed/gb-2001-2-7-research0025.txt:          HINT (Ohio State University) [ 73]; EST Assembly Project
technical/biomed/gb-2001-2-7-research0025.txt:          (University of Washington) [ 74]; TIGR Human Gene Index
technical/biomed/gb-2001-2-7-research0025.txt:          MINT and RINT (Ohio State University) [ 73]; EMBL Rodent
technical/biomed/ar130.txt:          University of Iowa (Iowa City, IA, USA). Biotinylated
technical/biomed/ar130.txt:          K Funa (Göteborg University, Gothenburg, Sweden).
technical/biomed/gb-2002-3-7-research0032.txt:          the University of Texas M.D. Anderson Cancer Center and
technical/biomed/1471-2091-2-13.txt:          Center (University of Connecticut)
technical/biomed/1471-2091-2-13.txt:          Zhaxybayeva (University of Connecticut). This program
technical/biomed/1471-2202-3-19.txt:          University of Chicago). The 1.2 kb coding sequence of the
technical/biomed/1471-2202-4-10.txt:          provided by Dr. Eric Gruenstein of University of
technical/biomed/gb-2003-4-4-r26.txt:        42,210 from Washington University and collaborators.
technical/biomed/1472-6882-3-1.txt:          for Complementary and Alternative Medicine (University of
technical/biomed/1471-2180-2-35.txt:          University using protocols approved by the Emory
technical/biomed/1471-2180-2-35.txt:          University Institutional Animal Care Committee. All of
technical/biomed/1471-2415-3-4.txt:          from the University's of Crete ethics committee.
technical/biomed/1471-2466-3-1.txt:          NC). The Committee on Human Research of the University of
technical/biomed/1472-6831-2-2.txt:          the University of Oklahoma Health Sciences Center between
technical/biomed/1477-7827-1-17.txt:          University of Saskatchewan, Saskatoon, Saskatchewan,
technical/biomed/1477-7827-1-13.txt:          admitted to the University of Tennessee Medical Center.
technical/biomed/1477-7827-1-13.txt:          University of London, London, England), for the
technical/biomed/1471-2156-3-17.txt:          kindly provided by M. Linder, Washington University
technical/biomed/1471-2334-1-24.txt:          Priscilla Schaffer (University of Pennsylvania, PA) at
technical/biomed/gb-2002-3-9-research0046.txt:          databases (Affymetrix, Iobion, and Rosetta, University of
technical/biomed/gb-2001-2-8-research0027.txt:          of sequences from the Clemson University rice BAC end
technical/biomed/1472-6874-2-1.txt:        Hospital Weill Medical College of Cornell University from
technical/biomed/1471-2091-3-8.txt:          (Columbia University). All cell types were growth at 37°C
technical/biomed/1472-6793-2-8.txt:          This study was approved by the University of
technical/biomed/1471-213X-2-7.txt:          the Drosophila stock center at Indiana University. D.
technical/biomed/1471-213X-2-7.txt:          the University of Virginia. Other images were obtained
technical/biomed/1476-4598-2-25.txt:          (University of Torino Pavia, Italy). Anti-MHC class II
technical/biomed/1476-4598-2-24.txt:          University, Jena, Germany after appropriate informed
technical/biomed/1476-4598-2-24.txt:          from Columbia University and Instituto Nacional de
technical/biomed/1471-2148-2-14.txt:          Washington University sequencing center. A paper
technical/biomed/1471-2407-1-19.txt:          University Hospital of Cleveland, Case Western Reserve
technical/biomed/1471-2407-1-19.txt:          University, Cleveland, OH [ 23 ] . NRP-152 cells were
technical/biomed/1472-6750-1-13.txt:          University of Texas at Austin) as a template, a 2.7 kb
technical/biomed/1472-6920-1-3.txt:          University of Texas Health Science Center at San Antonio.
technical/biomed/1471-2350-4-4.txt:          accordance with the University of Chicago's Institutional
technical/biomed/1471-2350-4-4.txt:          evaluations performed at the University of Chicago.
technical/biomed/1471-2350-4-4.txt:          University of Chicago's Cardiovascular Genetics Clinic
technical/biomed/rr167.txt:          David P Speert, University of British Columbia. These
technical/biomed/1471-2121-3-15.txt:          from E. J. Corey laboratory at Harvard University. LLnL
technical/biomed/gb-2002-3-9-research0045.txt:          mid-June at the Stanford University Plant Growth
technical/biomed/gb-2001-2-8-research0030.txt:          Thomas Bobik, University of Florida. Where indicated,
technical/biomed/bcr631.txt:          (kindly provided by Dr Terry Hall, University of
technical/biomed/1471-2180-2-32.txt:          and pAD105, generous gifts from Alan Davidson, University
technical/biomed/1471-2202-4-16.txt:          onto FVB background at University of Massachusetts
technical/biomed/1471-2202-4-16.txt:          Mice were maintained at the University of Massachusetts
technical/biomed/1471-2458-3-2.txt:          Committee of the University of California at San
technical/biomed/ar321.txt:          Medical University of South Carolina, Charleston, SC,
technical/biomed/gb-2001-2-4-research0014.txt:          Medicine and Genetics (Wayne State University, Detroit,
technical/biomed/gb-2001-2-4-research0014.txt:          University) directly from the clone set. Arrays were
technical/biomed/rr172.txt:          Kentucky standard cigarettes (1R3F; University of
technical/biomed/1471-213X-3-2.txt:          the PAN Facility (Stanford University, Palo Alto,
technical/biomed/1471-2148-3-18.txt:          and O. Strunk, Technical University of Munich, Germany;
technical/biomed/1471-2172-4-1.txt:          , a gift of Shoshana Levy, Stanford University) for one
technical/biomed/1471-2164-3-15.txt:          by Dr. Salo E. (University of Barcelona).
technical/biomed/1471-2458-2-16.txt:          Family Medicine (DFM) of the State University of New York
technical/biomed/1471-2105-3-12.txt:          WU-BLAST package of Washington University,
technical/biomed/gb-2003-4-2-r16.txt:          BLAT search at the University of California Santa Cruz
technical/biomed/ar409.txt:          (Stanford University, USA).
technical/biomed/1471-2407-2-11.txt:          with NIH and University of California, San Francisco
technical/biomed/1471-230X-1-5.txt:          Eugene Butcher (Stanford University). These cells were
technical/biomed/gb-2001-2-9-research0035.txt:        University of Wisconsin-Madison presents genome data on 
technical/biomed/gb-2003-4-6-r37.txt:          Stanford University). Peripheral zone prostate
technical/biomed/gb-2003-4-6-r37.txt:          Urology, Stanford University) and were established from a
technical/biomed/cc105.txt:        protocol at the University of Pennsylvania Medical Center,
technical/biomed/cc105.txt:        1996 at the University of Pennsylvania Medical Center (an
technical/biomed/cc105.txt:        At the University of Pennsylvania, brain death is
technical/biomed/cc105.txt:        Hospital of the University of Pennsylvania, brain death
technical/biomed/1471-213X-3-3.txt:          http://www.uni-koeln.de/dictyostelium(University of
technical/biomed/cc1498.txt:          Review Board of Erciyes University and informed consent
technical/biomed/cc1498.txt:          Infectious Diseases of Erciyes University Medical School
technical/biomed/1471-2350-3-7.txt:          Department of Neurosurgery at the University Hospital of
technical/biomed/1471-2350-3-7.txt:          Institutional Review Boards of both the University
technical/biomed/1471-2350-3-7.txt:          Hospital of Kuopio and Wayne State University.
technical/biomed/gb-2002-3-2-research0009.txt:          study was recently carried out at the University of
technical/biomed/bcr285.txt:          later modified at the University of Southern California
technical/biomed/bcr285.txt:          25]. The Committee on Human Subjects at the University of
technical/biomed/bcr285.txt:          later modified at the University of Southern California
technical/biomed/1472-6890-1-4.txt:          University of Tennessee Graduate School of Medicine. All
technical/biomed/1471-2172-3-10.txt:          State University.
technical/biomed/gb-2001-2-6-research0018.txt:          the Olfactory Receptor Database (ORDB) at Yale University
technical/biomed/1471-2105-2-9.txt:        University Microchemical Core Facility). Unedited sequence
technical/biomed/cc1538.txt:          After internal review board approval at the University
technical/biomed/1472-6831-3-1.txt:        contract was supervised by the University of Florida
technical/biomed/1472-6831-3-1.txt:        through University Project Number 00032218 and covered all
technical/biomed/1472-6793-2-17.txt:          and Use Committee at the University of Nevada. The
technical/biomed/1472-6793-2-17.txt:          Gunst, Indiana State University, USA). The unbound
technical/biomed/1471-2156-2-18.txt:          analysis were bred at Vanderbilt University Medical
technical/biomed/1477-7827-1-48.txt:          Animal Care and Use Committee of the University of North
technical/biomed/1471-213X-1-6.txt:        Laboratories of Michigan State University, near Hickory
technical/biomed/1471-2490-3-2.txt:        2000 and August 2001 at a University Hospital for suspected
technical/biomed/1477-7827-1-9.txt:          approved by the University of California, San Diego
technical/biomed/1472-6815-2-3.txt:        Uppsala University, Sweden. A majority (59%) of patients
technical/biomed/1472-6815-2-3.txt:        Health & Science University Tinnitus Clinic between
technical/biomed/1472-6815-2-3.txt:        University. Informed consent was obtained in writing from
technical/biomed/ar619.txt:          individuals following Drexel University Institutional
technical/biomed/gb-2002-3-12-research0081.txt:        examples are the University of California Santa Cruz (UCSC)
technical/biomed/1471-2202-2-14.txt:          vicinity of Peking University via newspaper
technical/biomed/1471-2164-3-10.txt:          Freeze of the University of California at Santa Cruz's
technical/biomed/1471-2164-3-10.txt:          University-Saint Louis clone map
technical/biomed/1471-230X-1-10.txt:          cftr gene created at the University of North Carolina [
technical/biomed/1471-230X-1-10.txt:          13 ] , were maintained at the University of Washington
technical/biomed/1471-2296-3-19.txt:          algorithm developed at the University of New Mexico, to
technical/biomed/1471-2105-3-17.txt:        by Stanford University (California) researchers depositing
technical/biomed/1471-230X-3-3.txt:          Jefferson University, PA).
technical/biomed/1471-230X-3-3.txt:          (Stanford University, CA). These cells were cultured in
technical/biomed/1471-2466-2-4.txt:          University and University Hospitals of Cleveland. All
technical/biomed/gb-2003-4-3-r17.txt:          University of Melbourne, Melbourne, Australia.
technical/biomed/1472-6793-2-11.txt:          at Washington State University). Sheep anti-rabbit IgG
technical/biomed/1472-6823-2-2.txt:          Bulgaria; University Hospital of São Paolo, São Paolo,
technical/biomed/1472-6823-2-2.txt:          Brazil; The Catholic University of Korea, Seoul, South
technical/biomed/1471-2091-3-23.txt:          State University Ohio. Forward and reverse PCR primers
technical/biomed/1471-2180-3-10.txt:          Advanced Genetic Analysis Center at the University of
technical/biomed/1471-2407-3-4.txt:          Duke University Medical Center Institutional Review
technical/biomed/1477-7827-1-43.txt:          to re-establish the colony at the University of
technical/biomed/cc2172.txt:          Ethics Committee of Istanbul University Hospital. Written
technical/biomed/cc2172.txt:          intensive care unit at Istanbul University Hospital. The
technical/biomed/1471-213X-1-9.txt:          University of Virginia and then maintained as a breeding
technical/biomed/1471-2164-4-15.txt:          columns and submitted to the Vanderbilt University Shared
technical/biomed/1472-6874-2-13.txt:          Human Studies at the University of Hawaii approved the
technical/biomed/1472-6874-2-13.txt:          Obstetrics and Gynecology, University of Southern
technical/biomed/1471-2105-3-26.txt:          University of Michigan Medical Center. All samples and
technical/biomed/1476-4598-2-2.txt:          Review Board at University of California, San Diego
technical/biomed/1472-684X-2-1.txt:            University of Colorado Health Sciences Center (UCHSC)
technical/biomed/1472-684X-2-1.txt:            rotate through the University of Colorado Hospital
technical/biomed/1471-5945-3-3.txt:          of the University of California, Irvine, approved the
technical/biomed/1471-2164-3-35.txt:          Facility of the University of California at Davis. They
technical/biomed/1471-2164-3-35.txt:          University of Texas at Austin under standard laboratory
technical/biomed/1471-2164-3-35.txt:          University of Texas at Austin Animal Use Committee.
technical/biomed/1477-7827-1-54.txt:          obtained from the histology core at the University of
technical/biomed/1471-2334-2-1.txt:          academic diabetes practice of Wayne State University
technical/biomed/1471-2334-2-1.txt:          an urban (University Health Center, Detroit, MI) clinic
technical/biomed/1471-2334-2-1.txt:          University of Michigan and Wayne State University.
technical/biomed/1471-2334-2-1.txt:          formula [ 25 ] . For the Wayne State University patient
technical/biomed/1471-2210-2-5.txt:          Louis, MO). Insulin was obtained from University Hospital
technical/biomed/1471-2210-2-5.txt:          of New York University and PDGF was purchased from Biomol
technical/biomed/ar774.txt:          University of Michigan Vector Core was used to transduce
technical/biomed/gb-2000-1-1-research002.txt:          (obtained from Brent Ewing and Phil Green, University of
technical/biomed/gb-2000-1-1-research002.txt:          (obtained from Arian Smit, University of Washington
technical/biomed/gb-2000-1-1-research002.txt:          were obtained from Kurt Benirschke (University of
technical/biomed/gb-2000-1-1-research002.txt:          script (obtained from Natalie Kolker, University of
technical/biomed/gb-2000-1-1-research002.txt:          University of Washington Genome Center) was used to
technical/biomed/1471-2334-2-26.txt:          College of Medicine, Istanbul University. Rectal
technical/biomed/1471-2334-2-26.txt:        This study was supported by Firat University Research
technical/biomed/1476-5918-1-2.txt:          the University of Georgia.
technical/biomed/1471-2334-2-27.txt:          Hopkins University. The mouse monoclonal antibody (mAb),
technical/biomed/1476-4598-2-1.txt:          kinase [ 10 ] (Dr. Jean Wang, Biology, University of
technical/biomed/1476-4598-2-1.txt:          the outpatient pharmacy at West Virginia University and
technical/biomed/1471-2180-1-26.txt:          Einstein University, New York, NY [ 20 ] . The cosmid
technical/biomed/1471-2350-2-12.txt:          study was approved by the University of Utah Health
technical/biomed/1471-2350-3-9.txt:            and the University of Alabama at Birmingham. A
technical/biomed/1472-6947-2-7.txt:          using resources such as the University Hospital
technical/biomed/1475-925X-2-1.txt:        of Medical Physics, Warsaw University, and my colleagues
technical/biomed/1475-925X-2-1.txt:        • Prof. Waldemar Szelenberger, Medical University of
technical/biomed/1475-925X-2-1.txt:        Warsaw University
technical/biomed/1475-925X-2-1.txt:        University
technical/biomed/1475-925X-2-1.txt:        Technical University
technical/biomed/1471-2148-2-5.txt:          University of Georgia. Sequences were aligned with Mac
technical/biomed/cc1044.txt:        the Dicle-University Hospital. All patients, whether
technical/biomed/1472-6963-3-1.txt:        review board of Duke University Medical Center.
technical/biomed/1471-2172-2-9.txt:          Lawrence (University of Virginia). The second chamber was
technical/biomed/1472-6793-3-3.txt:          homogenates [ 23 ] . The University of Virginia Diabetes
technical/biomed/1471-2091-3-15.txt:          Kirschbaum at The University of Louisiana at Monroe,
technical/biomed/1471-2180-1-7.txt:          University of Kansas Medical Center, Kansas). To
technical/biomed/cc1497.txt:        University of Wisconsin (UW) liver transplantation program
technical/biomed/1471-2334-2-7.txt:          University, Boston MA) cell lines were grown in
technical/biomed/1471-2334-2-7.txt:          (Harvard University, Boston, MA) [ 10 ] . HP66 (HSV-1
technical/biomed/1471-2334-2-7.txt:          kindly provided by D. Coen (Harvard University, Boston,
technical/biomed/1475-9268-1-2.txt:          approved by the Louisiana State University Health
technical/biomed/1477-7827-1-46.txt:          Thy-1, clone OX-7 [ 49 ] (Dr Alan F. Williams, University
technical/biomed/ar799.txt:          Dr DR Critchley of the University of Leicester, UK.
technical/biomed/1471-2164-3-19.txt:          Stanford University (details can be obtained from:
technical/biomed/1471-230X-1-8.txt:        6 to the University of Michigan Medical Center for further
technical/biomed/1472-6947-2-4.txt:        Management. Portland State University, PICMET
technical/biomed/bcr303.txt:          University) and other reversal agents, including MG, TAM,
technical/biomed/bcr303.txt:            University, College of Physicians and Surgeons, New
technical/biomed/1471-2105-3-23.txt:          approved by the University of Rochester Research Subjects
technical/biomed/1471-2105-3-23.txt:          biopsy. Each subject stayed at the University of
technical/biomed/1471-2105-3-23.txt:          University of Rochester Microarray Core Facility. After
technical/biomed/1471-2121-1-2.txt:          Hann, Vanderbilt University) were grown in Dulbecco's
technical/biomed/1471-2180-1-34.txt:          (Vanderbilt University, TN). Rabbit polyclonal antibody
technical/biomed/gb-2003-4-8-r50.txt:        from the University of California at Santa Cruz (UCSC)
technical/biomed/1471-2202-2-20.txt:          University Bio-Ag vivarium and maintained on a 10-hour
technical/biomed/1471-2202-2-20.txt:          Young University. Upon arrival all animals were allowed 
technical/biomed/1471-2202-2-20.txt:            Iacopino, Marquette University, USA) or human COX-2
technical/biomed/1471-2164-3-24.txt:          the FPC database at Washington University Genome
technical/biomed/1471-2202-3-7.txt:        Emory University, Atlanta, GA).
technical/biomed/1471-2121-3-25.txt:          Macara, University of Virginia, Charlottesville, USA. NIH
technical/biomed/1471-2202-4-6.txt:          Sequence Analysis, BioCentrum-DTU, Technical University
technical/biomed/1472-6882-1-10.txt:          Mayaro. All the plants were identified at the University
technical/biomed/1472-6882-1-10.txt:          University of the West Indies, pers. comm. 2000). If
technical/biomed/1471-2164-4-6.txt:          available from the University of California - Santa Cruz
technical/biomed/1471-2164-4-6.txt:          version of the genomic sequence at University of
technical/biomed/1471-2229-2-9.txt:          Institute) and Dr. Christiane Nawrath (University of
technical/biomed/gb-2002-3-9-research0049.txt:          library [ 37] as described by the Clemson University
technical/biomed/gb-2002-3-9-research0049.txt:          State University.
technical/biomed/1471-2210-1-7.txt:          of Chemical Sciences, University of Illinois. All
technical/biomed/1471-2210-1-7.txt:          Midwestern University's Research and Animal Care
technical/biomed/1471-2180-2-16.txt:          YopE (α-YopE; gift from S. C. Straley, University of
technical/biomed/1471-2121-3-18.txt:          College of Cornell University, NY, NY); anti-FAK and
technical/biomed/1477-7827-1-21.txt:          Building at The Ohio State University. The animal room
technical/biomed/1477-7827-1-21.txt:          State University.
technical/biomed/1477-7827-1-21.txt:          Butcher, West Virginia University, Morgantown, was raised
technical/biomed/1477-7827-1-23.txt:          Automated Sequencer, Oklahoma State University
technical/biomed/gb-2003-4-2-r9.txt:        Genomic Research (TIGR), and Stanford University is
technical/biomed/1475-2883-2-11.txt:          Charles Katholi (The University of Alabama, Birmingham) [
technical/biomed/1475-2867-2-10.txt:          This experiment was conducted at the University of
technical/biomed/1471-2202-2-3.txt:          by the University of Kentucky Institutional Review Board.
technical/biomed/bcr602.txt:          George Washington University Department of Pathology and
technical/biomed/bcr602.txt:          Tissue Bank for Developmental Disorders at the University
technical/biomed/1478-1336-1-4.txt:          (University of California, San Francisco). VP16-RAR-LBD
technical/biomed/1472-6793-2-4.txt:            as a gift from Dr. R. Lynch, University of Arizona, and
technical/biomed/1472-6793-2-4.txt:            of AQP1 (from W.D. Stamer and J.W. Regan, University of
technical/biomed/1471-2091-3-4.txt:          Chemistry at Johns Hopkins University. After confirmation
technical/biomed/1472-6750-2-2.txt:          University. Bacteria were grown on BSM agar [ 21 ] media
technical/biomed/cc1547.txt:          St Peter's University Hospital (New Brunswick, NJ, USA)
technical/biomed/cc1547.txt:          Subjects in Research of St Peter's University Hospital.
technical/biomed/cc1547.txt:          Peter's University Hospital.
technical/biomed/1472-6793-1-11.txt:          sequencing facility at Tufts University sequenced the PCR
technical/biomed/1471-2407-2-9.txt:        Research Group at Wake Forest University (SAM and VH). LDC
technical/biomed/1471-2407-2-8.txt:          Second Affiliated Hospital of Henan Medical University (n
technical/biomed/1476-511X-2-2.txt:          to the University of New Mexico School of Medicine for
technical/biomed/1471-2121-4-3.txt:          Biochemistry, Purdue University).
technical/biomed/1471-2261-2-11.txt:          University . Surgical procedures were carried out
technical/biomed/gb-2001-2-12-research0054.txt:          Washington University Genome Sequencing Center (for 
technical/biomed/ar104.txt:          the University of Pittsburgh Biotechnology Center. For
technical/biomed/1471-2105-3-2.txt:            Noller, University of California, Santa Cruz) and
technical/biomed/1471-2105-3-2.txt:            maintained by us at the University of Texas; these
technical/biomed/1471-2105-3-2.txt:            graphics program XRNA (Weiser & Noller, University
technical/biomed/rr196.txt:          University of Pennsylvania.
technical/biomed/1477-7827-1-36.txt:          admitted to the University of Tennessee Medical Center.
technical/biomed/1477-7827-1-36.txt:          Integrative Physiology, University of Illinois College of
technical/biomed/1471-213X-1-13.txt:          Embryos from the University of Oregon and Vanderbilt
technical/biomed/1471-213X-1-13.txt:          University laboratory colonies were raised at 28.5°C.
technical/biomed/1471-213X-1-13.txt:          16A11 anti-Hu antibody (University of Oregon Monoclonal
technical/biomed/bcr571.txt:          from Dr R Parson of Columbia University, New York,
technical/biomed/1472-6955-2-1.txt:          In addition to Oregon Health & Science University
technical/biomed/1472-6955-2-1.txt:        received by the Oregon Health & Science University
technical/biomed/1471-2105-3-6.txt:          obtained from the University of Winsconsin 
technical/biomed/1471-2202-2-6.txt:          compliance with the Colorado State University Animal Care
technical/biomed/1471-2369-3-6.txt:        Regional University Pathologists, Salt Lake City, UT) in
technical/biomed/1471-2369-3-6.txt:        Division of Endocrinology at the University of Utah using
technical/biomed/1471-2180-2-38.txt:          University Center for Gene Research and
technical/biomed/1471-2210-3-3.txt:          Research Institute of Mashhad University of Medical
technical/biomed/1471-2210-3-3.txt:          with Mashhad University of Medical Sciences, Ethical
technical/biomed/1471-2202-3-14.txt:          were recruited from the vicinity of Peking University and
technical/biomed/1471-2121-3-22.txt:          Zhang (Yale University) and P. Jackson (Stanford
technical/biomed/1471-2121-3-22.txt:          University). The genes were amplified by PCR and cloned
technical/biomed/1471-2121-3-22.txt:          University). The reagents were dissolved in absolute
technical/biomed/1471-2199-2-5.txt:          Nucleic Acid Facility, Stanford University. The mutC,
technical/biomed/bcr570.txt:          Institutional Review Board of the State University of New
technical/biomed/1472-6947-3-5.txt:          Laboratory" meeting, held at the University of Michigan
technical/biomed/cc343.txt:        University of Texas Health Science Center at San Antonio,
technical/biomed/cc343.txt:        intensive care unit of the University Hospital between
technical/biomed/1477-7827-1-27.txt:          University of Virginia. Surface-labeled egg proteins were
technical/biomed/1471-2148-3-4.txt:          of Genetics, University of Washington, Seattle ] or
technical/biomed/1471-2458-3-11.txt:          institutional review boards: the University of
technical/biomed/1475-2875-1-5.txt:          Shenolikar (Duke University), respectively. The
technical/biomed/1475-2875-1-5.txt:          kindly provided by W. Hol (University of Washington,
technical/biomed/1475-2875-1-5.txt:          University, Baltimore, MD). Microcystin-coupled sepharose
technical/biomed/1477-7827-1-31.txt:          by B.R. Downey (McGill University, Montreal, Canada).
technical/biomed/1477-7827-1-31.txt:          protein (StAR) was a gift from D.B. Hales (University of
technical/biomed/1477-7827-1-31.txt:          Bruce Downey (McGill University) and maintained in
technical/biomed/1471-2202-2-5.txt:          ABF2 mice were generated at the University of Tennessee
technical/biomed/bcr605.txt:          The University of California, San Francisco, Committee
technical/biomed/1476-069X-2-9.txt:        Reduction Institute at the University of Massachusetts
technical/biomed/1476-069X-2-9.txt:        Reduction Institute at the University of Massachusetts
technical/biomed/1478-1336-1-3.txt:          obtained from Dr. R. Matusik, Vanderbilt University, TN [
technical/biomed/1478-1336-1-3.txt:          provided by Dr. C. Chang, University of Rochester, NY.
technical/biomed/1478-1336-1-3.txt:          University, Japan [ 32 ] . The plasmid expressing a
technical/biomed/1471-2164-2-4.txt:          Studies, Rutgers University Cell and DNA Repository,
technical/biomed/1471-2210-1-3.txt:          University, Japan.
technical/biomed/1471-2334-1-13.txt:        infection treated at the University Medical Center,
technical/biomed/1471-2334-1-13.txt:        hospital were included in the study. The University Medical
technical/biomed/1471-2334-1-13.txt:        affiliated with the University of Florida. Because of the
technical/biomed/1471-2105-3-4.txt:          25 ] [Stanford University]), t-test (GeneSpring) and
technical/biomed/bcr567.txt:          and Radiotherapy of the University College Hospital,
technical/biomed/bcr567.txt:        25 26 ] . In the New York University Women's Health Study,
technical/biomed/1471-213X-1-11.txt:          from women admitted to the University of Tennessee
technical/biomed/1476-4598-1-6.txt:          King (Thomas Jefferson University, USA). The probe has
technical/911report/chapter-13.4.txt:                chemistry, from California State University, Sacramento. Sufaat did not start on the
technical/911report/chapter-13.4.txt:                5,1996, remarks at George Washington University, he called terrorism "the enemy of
technical/911report/chapter-13.4.txt:            38. Vanderbilt University, Television News Archive, Dec. 22, 1999-Jan. 4, 2000.
technical/911report/chapter-13.4.txt:                Warsaw University, June 15, 2001.
technical/911report/chapter-13.4.txt:                Pakistan along with Abu Zubaydah, studied at Embry-Riddle Aeronautical University in
technical/911report/chapter-13.5.txt:                University Television News Archive, Dec. 13, 22-31, 1999.
technical/911report/chapter-13.3.txt:                Pirenne, A History of Europe, trans. Bernard Miall (University Books, 1956), pp.
technical/911report/chapter-13.3.txt:                against Terrorism," University of Pennsylvania Journal of Constitutional Law, vol. 5
technical/911report/chapter-13.3.txt:                Surveillance Act of 1978," University of Pennsylvania Law Review, vol. 137 (1989),
technical/911report/chapter-13.3.txt:                Authority for National Security Surveillance," American University Law Review, vol.
technical/911report/chapter-2.txt:                runner, climber, and soccer player. He had attended Abdul Aziz University in Saudi
technical/911report/chapter-5.txt:                State University in Greensboro, which he attended with Yousef 's brother, another
technical/911report/chapter-5.txt:                University with a degree in architectural engineering in 1990, Atta worked as an
technical/911report/chapter-5.txt:                University of Hamburg, he promptly transferred into the city engineering and
technical/911report/chapter-5.txt:                planning course at the Technical University of Hamburg-Harburg, where he would
technical/911report/chapter-5.txt:                enrolled at the University of Bonn in a program for technical, mathematical, and
technical/911report/chapter-5.txt:                directive, however, and did not reenroll at the University of Bonn until the
technical/911report/chapter-5.txt:                returned to Hamburg, applying to study shipbuilding at the Technical University and,
technical/911report/chapter-5.txt:                dentistry to aircraft engineering-at the Technical University of Hamburg-Harburg.
technical/911report/chapter-5.txt:                    engineering at the Technical University of Hamburg-Harburg. He spent five months
technical/911report/chapter-5.txt:                    University. A witness has recalled Motassadeq saying that he would kill his
technical/911report/chapter-6.txt:                coordinated. Rice had asked University of Virginia history professor Philip Zelikow
technical/911report/chapter-7.txt:                study at the Center for English as a Second Language at the University of Arizona.
technical/911report/chapter-7.txt:                important al Qaeda figures attended the University of Arizona in Tucson or lived in
technical/911report/chapter-7.txt:                degree from the Imam Muhammad Ibn Saud Islamic University, was married, and had a
(base) rosarioortiz@Rosarios-MacBook-Air docsearch % 
```
 In this lengthy example, grep -r searches all the files in docsearch, including those in its subdirectories, for lines containing "University of *." Running this command may be useful for finding citations or bibliographies in academic papers. 
 
I learned about this command from Chat GPT. 
 
### -l 
This option allows you to search for a pattern in all files in a directory, but print out the filenames containing it rather than the lines themselves. 

example 1 
```
$  grep -l biophysics
# nothing is returned 
```
 a sentence or two about what it’s doing and why it’s useful.
example 2
```
oi ello
```
 a sentence or two about what it’s doing and why it’s useful.
  Citation + URL 

### -c
This option counts the number of lines that match a pattern and prints this number out. 

example 1 
```
oi ello
```
 a sentence or two about what it’s doing and why it’s useful.
 
example 2
```
oi ello
```
 a sentence or two about what it’s doing and why it’s useful.
  Citation + URL 
 
### --include="*.fileType"

This will search for the given pattern in all files with the fiven file extension in the current directory and print out any lines that contain the pattern. The --include option is used to specify the file type to search in.


## ChatGPT 
 The prompts I gave ChatGPT were:
 - Hi ChatGPT ! Can you give me four alternate ways to use grep in terminal ? 
 - Thanks ChatGPT ! Do you have any more ?
 
Its outputs, respectively, were:
- Sure, here are four different ways to use grep in the terminal:

  Search for a pattern in a single file:
    ```
    perl
    Copy code
    grep "pattern" filename.txt
    This will search for the given pattern in the file filename.txt and print out any lines that contain the pattern. 
    ```
    Search for a pattern in all files in a directory:
    ```
    perl
    Copy code
    grep "pattern" *
    This will search for the given pattern in all files in the current directory and print out any lines that contain the pattern.
    ```

   Search for a pattern in all files in a directory recursively:

    perl
    Copy code
    grep -r "pattern" *
    This will search for the given pattern in all files in the current directory and any subdirectories, and print out any lines that contain the pattern.

   Search for a pattern in all files in a directory, but only print out the filenames:

perl
Copy code
grep -l "pattern" *
This will search for the given pattern in all files in the current directory and print out only the names of the files that contain the pattern, rather than the actual lines.

- Sure, here are four more ways to use grep in the terminal:

  Use grep to count the number of lines that match a pattern:

    perl
    Copy code
    grep -c "pattern" filename.txt
    This will search for the given pattern in the file filename.txt and print out the number of lines that contain the pattern.

  Use grep to search for multiple patterns:

    perl
    Copy code
    grep -e "pattern1" -e "pattern2" filename.txt
    This will search for both "pattern1" and "pattern2" in the file filename.txt and print out any lines that contain either pattern.

 Use grep to search for a pattern in a compressed file:

     arduino
     Copy code
     zgrep "pattern" filename.txt.gz
     This will search for the given pattern in a compressed file filename.txt.gz and print out any lines that contain the pattern. The zgrep command is used to search for patterns in gzip-compressed files.

Use grep to search for a pattern in a specific type of file:

      perl
      Copy code
      grep "pattern" --include="*.txt" *
      This will search for the given pattern in all files with a .txt extension in the current directory and print out any lines that contain the pattern.       The --include option is used to specify the file type to search in.

I changed the output in my lab report by omitting ChatGPT's code examples and selecting four of the eight options to include in my report. The outputs I did include were copy- pasted and rephrased slightly to match the format of the report. 
