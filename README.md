۔# Clone repository
git clone https://github.com/mrwasif-dev/Muzamil-MD.git

# Enter directory
cd Muzamil-MD

# Install dependencies
npm install

# Create .env file with your configuration
echo "SESSION_ID=your_session_id" > .env
echo "MONGODB_URL=your_mongodb_url" >> .env
echo "SOURCE_JIDS=jid1,jid2" >> .env
echo "TARGET_JIDS=jid3,jid4" >> .env

# Start the bot
npm start
