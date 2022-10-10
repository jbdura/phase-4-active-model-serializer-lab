class AuthorpostSerializer < ActiveModel::Serializer
  # attributes :id

  attributes :title, :short_content, :tags
  has_many :tags
  
  def short_content
    "#{self.object.content[0..39]}..."
  end

end
