
# 2

```mermaid
gantt
  title Strategy for Art Residence Development

  dateFormat YYYY
  section Manifest
    Define_Core_Principles :2022, 1yr
    Core_Values :2022, 1yr
    Mission_Statement :2022, 1yr
    Vision :2022, 1yr

  section Home_Restoration
    Arrange_Old_Premises :2022, 1yr
      Assess_Condition :2022, 6mo
      Plan_Restoration :2022, 6mo
    Infrastructure_Development :2023, 1yr
      Landscape_Design :2023, 6mo
      Utilities_Enhancement :2023, 6mo

  section Communication
    Website :2024, 1yr
      Develop_Website :2024, 6mo
      Update_Content :2024, 6mo

    Blogging :2025, 1yr
      Social_Media_Presence :2025, 4mo
      YouTube_Content :2025, 4mo
      Advertising :2025, 4mo

    Events_and_Festivals :2025, 1yr
      Plan_Organize_Events :2025, 6mo
      Participate_Festivals :2025, 6mo

    Guests :2026, 1yr
      Invite_Artists :2026, 6mo
      Collaborate_Bloggers :2026, 6mo

    Presentation :2027, 1yr
      Showcase_Artists_Work :2027, 6mo
      Organize_Exhibitions :2027, 6mo

    %% Dependencies
    Link_Website_Blogging : after Develop_Website, before Social_Media_Presence
    Link_Blogging_Events : after Advertising, before Plan_Organize_Events
    Link_Events_Guests : after Participate_Festivals, before Invite_Artists
    Link_Guests_Presentation : after Collaborate_Bloggers, before Showcase_Artists_Work
  end

  section Admin_Liaison_Funding
    Building_Team :2027, 1yr
      Assemble_Skilled_Team :2027, 6mo
      Coordinate_Tasks :2027, 6mo
    PubOrg :2028, 1yr
      Promote_Art_Residence :2028, 6mo
      Establish_Partnerships :2028, 6mo
    Grants_and_Tender :2029, 1yr
      Research_Apply_Grants :2029, 6mo
      Participate_Tenders :2029, 6mo
    Shop :2030, 1yr
      Set_Up_Shop :2030, 6mo
      Manage_Inventory :2030, 6mo
    Donation :2031, 1yr
      Implement_Donation_System :2031, 6mo
      Seek_Financial_Support :2031, 6mo
      Fundraising_Crowdfunding :2031, 6mo

    %% Dependencies
    Link_Building_Team_PubOrg : after Coordinate_Tasks, before Promote_Art_Residence
    Link_PubOrg_Grants : after Establish_Partnerships, before Research_Apply_Grants
    Link_Grants_Shop : after Participate_Tenders, before Set_Up_Shop
    Link_Shop_Donation : after Manage_Inventory, before Implement_Donation_System
  end




```
