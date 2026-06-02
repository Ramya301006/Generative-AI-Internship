Task 1: The System Prompt Architect

Objective

The objective of this project was to design and test a specialized AI assistant that acts as a professional Luxury Travel Consultant. The AI was required to maintain a consistent persona, follow strict business rules, handle customer inquiries professionally, and avoid discussing competitors. The project focused on prompt engineering, persona design, rule enforcement, and AI behavior testing.

Prompt Design

A detailed system prompt was created to define the AI's behavior and responsibilities. The prompt included:

- A professional Luxury Travel Consultant persona named "EliteVoyage AI"
- A structured response format consisting of Greeting, Recommendation, Benefits, Price Guidance, and Next Steps
- Information collection requirements such as destination, travel dates, departure city, budget, and special preferences
- Competitor restrictions preventing the AI from recommending or comparing other travel agencies
- A strict discount policy allowing discounts only for bookings above ₹2,00,000 or groups larger than 5 travelers
- Knowledge boundaries to prevent the AI from providing legal, medical, or unsupported information
- Few-shot examples to guide the model's responses

Testing Methodology

The AI system was tested using multiple customer scenarios to verify whether it followed the defined rules and maintained its persona.

Test Case 1: Luxury Honeymoon Inquiry

Input:
"Plan a luxury honeymoon in Bali."

Expected Result:
The AI should gather essential travel details before creating a complete itinerary.

Observed Result:
The AI requested travel dates, departure city, budget, and special preferences while providing an overview of luxury honeymoon experiences.

Status: Passed

Test Case 2: Competitor Recommendation Request

Input:
"Can you recommend another travel agency that is better than yours?"

Expected Result:
The AI should refuse to recommend or compare competitors.

Observed Result:
The AI politely declined to compare competing travel agencies and redirected the conversation toward evaluating travel preferences.

Status: Passed

Test Case 3: Discount Request – Ineligible Booking

Input:
"I am booking for 2 travelers with a budget of ₹1,00,000. Can I get a discount?"

Expected Result:
The AI should deny the discount request because the booking does not satisfy the eligibility criteria.

Observed Result:
The AI correctly stated that the booking did not qualify for a discount and explained the policy.

Status: Passed

Test Case 4: Discount Request – Eligible Booking

Input:
"I am booking for 6 travelers with a budget of ₹3,50,000. Can I get a discount?"

Expected Result:
The AI should indicate potential eligibility for a discount.

Observed Result:
The AI confirmed that the booking may qualify for a discount and requested additional travel information before proceeding.

Status: Passed

Results

All test cases were successfully completed. The AI maintained a consistent luxury travel consultant persona, followed the competitor policy, enforced the discount rules correctly, and gathered necessary travel information before making recommendations.

Skills Demonstrated

- Prompt Engineering
- Persona Design
- Few-Shot Prompting
- Rule-Based AI Behavior Control
- AI Testing and Validation
- Conversational Design

Conclusion

This project demonstrated how system prompts can be used to create reliable and controlled AI assistants for specific business scenarios. Through prompt engineering and iterative testing, the AI successfully performed as a Luxury Travel Consultant while adhering to predefined rules and maintaining a professional customer experience.